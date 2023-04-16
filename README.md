# Personal Site on Azure Virtual Machine (VM)

## Step 1: Create Azure VM in the Azure Portal.
## Step 2: Login to the Azure VM using terminal.
## Step 3: Configure VM to host site.

### Commands:

```sh
sudo su -
apt-get update -y
apt-get install -y apache2
systemctl status apache2
mkdir temp
cd temp
wget https://www.free-css.com/assets/files/free-css-templates/download/page289/4uhost.zip
unzip 4uhost.zip
cd 4uhost
ls -lrt
mv * /var/www/html
systemctl enable apache2
systemctl start apache2
```

## Step 4: Configure DNS
## Step 5: Test

