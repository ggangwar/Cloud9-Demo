# Cloud9-Demo
Added SSH key for this Cloud9 environment into Github profile

# Created python virtual environment:
python3 -m venv ~/.Cloud9-Demo

# Activated python virtual environment.
source ~/.Cloud9-Demo/bin/activate

# To deactivate environment:
deactivate

# edit ~/.bashrc file and create alias:
vim ~/.bashrc
# go to end of ~/.bashrc file and add following:
alias demo="cd /home/ec2-user/environment/Cloud9-Demo && source ~/.Cloud9-Demo/bin/activate"
# source ~/.bashrc file
source ~/.bashrc

