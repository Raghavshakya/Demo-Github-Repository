cd /opt/

sudo dnf update -y

sudo dnf install git nginx -y

sudo systemctl start nginx

sudo systemctl enable nginx

ls -ld /var/www/html

mkdir -p /var/www/html

git clone https://github.com/Raghavshakya/Demo-github-reository.git

dir

cd Demo-github-repository/

git status

mkdir raghav

chmod 655 raghav

cd raghav/

vi index.html
<h1>CI CD Working Successfully</h1>

ls

git add demo.txt

git status

git commit -m "change by raghav"

git branch

git push

ssh-keygen -t rsa -b 4096

ll

cat ~/.ssh/id_rsa.pub

sudo dnf install nodejs -y

node -v

npm -v

npm init -y

vi .gitignore

-------------

node_modules

.env

---------------

git branch

git status

git add .gitignore

git commit -m "raghav"

git branch

git remote add origin  https://github.com/Raghavshakya/my-github-reository.git

git remote -v

git config --global pull.rebase false

git pull origin main --allow-unrelated-histories

git push -u origin main
