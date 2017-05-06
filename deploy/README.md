# Localhost Setup

1. Install 3rd party roles: `ansible-galaxy install -r requirements.yml`
2. Configure settings and IPs in `inventories/*`
3. Test connection: `ansible all -m ping -i inventories/<env>`

# Deployment

`ansible-playbook -i inventories/<env name> ansible.yml`

# Server Setup

1. Buy Domain Name

2. Setup App

3. Create Git Repo

4. Create Server

5. Cert SSL Cert and Download Cert Files

Only needed if setting up a new box or new SSL cert. (per this tutorial https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04)

1. SSH to any app node and install (certbot)[https://certbot.eff.org]
1a. Add the node to DNS entry so that certbot can generate the cert using a temporary web server.
1b. Download the generated certbot files:
  scp -i <your ssh key> -r root@<your IP>:/etc/letsencrypt/live/<your domain> .
  (i.e. scp -i depkey -r root@46.101.227.108:/etc/letsencrypt/live/nickmanning.co .)

6. Ensure enough swap for running `npm install`

```
sudo fallocate -l 1G /swapfile
ls -lh /swapfile
sudo chmod 600 /swapfile
ls -lh /swapfile
```

(from https://www.digitalocean.com/community/tutorials/how-to-add-swap-space-on-ubuntu-16-04)

7. Configure Ansible Playbook

1. update `inventories/*`
2. update `vars/base.yml`
3. add the server's SSH pub and private keys to `.` and `roles/app/files`
4. add downloaded SSL cert keys `fullchain.pem` and `privkey.pem` to `roles/app/files`
5. customize templates in `roles/app/templates`