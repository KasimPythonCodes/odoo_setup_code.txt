# odoo_setup_code.txt

sudo add-apt-repository ppa:deadsnakes/ppa 
sudo apt install python3.6

sudo apt-get install postgresql

sudo su postgres

sudo npm uninstall -g less 

sudo npm install -g less@3.10.3

sudo apt-get install -y npm 

sudo ln -s /usr/bin/nodejs /usr/bin/node



sudo npm install -g n

sudo apt-get install --reinstall python3.6-distutils
create database odoo1;

\c odoo1

CREATE USER mydb WITH PASSWORD 'odoo';

GRANT ALL PRIVILEGES ON DATABASE odoo1 TO mydb;

ALTER ROLE kasim createrole createdb;

ALTER ROLE kasim createrole superuser;











addons_path = /home/kasim/Downloads/himanshu_s_code/odoo-11.0/addons, /home/kasim/Downloads/himanshu_s_code/odoo-11.0/customs
db_host = localhost
db_port = 5432
db_user = vivek_3
db_password = odoo
xmlrpc_port = 8001


 

Babel==2.3.4
bcrypt==4.0.1
beautifulsoup4==4.10.0
cffi==1.15.1
cryptography==39.0.0
decorator==5.1.0
docopt==0.6.2
docutils==0.18.1
html2text==2020.1.16
Jinja2==2.8
lxml==4.7.1
MarkupSafe==0.23
num2words==0.5.10
olefile==0.46
paramiko==2.12.0
passlib==1.6.5
pbr==5.9.0
Pillow==4.0.0
psutil==5.8.0
psycopg2-binary==2.9.3
pycparser==2.21
pyenchant==3.2.2
PyNaCl==1.5.0
pyodbc==4.0.34
pyparsing==2.1.10
PyPDF2==1.26.0
python-dateutil==2.5.3
pytz==2016.7
PyYAML==3.12
qrcode==7.3.1
reportlab==3.6.3
requests==2.11.1
six==1.16.0
soupsieve==2.3.2.post1
Werkzeug==0.11.15
wkhtmltopdf==0.2
XlsxWriter==3.0.2
xlwt==1.3.0
