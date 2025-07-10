how to deploy the applicayion using ec2

sudo su

yum update
yum install git
git clone
ls
cd filename
yum install python3-pip
python3 -m pip install -r requirements.txt
python3 -m pip install --ignore-installed streamlit
python3 -m streamlit run app.py
nohup python3 -m streamlit run app.py # it is permenent working
ps aux
ps -ef
sudo su
kill <id>
once kill id, after that have to below process
cd filename
python3 -m streamlit run app.py
nohup python3 -m streamlit run app.py # it is permenent working
