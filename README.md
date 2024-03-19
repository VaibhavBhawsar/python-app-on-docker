 Id CommandLine
  -- -----------
   1 git --version
   2 git config --global user.name "vaibhavbhawsar"
   3 git config --global user.email "bhavsarvaibhav001@gmail.com"
   4 git login
   5 git clone https://github.com/VaibhavBhawsar/python-app-on-docker.git
   6 ls
   7 cd .\python-app-on-docker\
   8 git status
   9 code .
  10 python project.py

     New-Item Dockerfile
    code Dockerfile
   6 docker build -t vaibhavbhawsar/pythonapp .
   7 docker images
   8 docker run vaibhavbhawsar/pythonapp
 10 docker push vaibhavbhawsar/pythonapp