# Prerequisites
######
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


###
  496  cd .ssh/
  497  ls
  498  ls
  499  cat id_rsa
  500  cat id_rsa.pub
  501  clear
  502  ls
  503  ssh -i ./id_rsa -T git@github.com
  504  export GIT_SSH_COMMAND="ssh -i ~/.ssh/id_rsa"
  505  cd ..
  506  ls
  507  ls
  508  ls
  509  pwd
  510  ll
  511  mkdir Desktop/actions/
  512  cd Desktop/actions/
  513  ls
  514  git clone https://github.com/hieunguyen0202/hprofile.git
  515  git clone git@github.com:hieunguyen0202/hprofile.git
  516  ls
  517  cd hprofile/
  518  ls
  519  unset GIT_SSH_COMMAND
  520  git config core,sshCommand "ssh -i ~/.ssh/id_rsa -F /dev/null"
  521  git config core.sshCommand "ssh -i ~/.ssh/id_rsa -F /dev/null"
  522  cat .git/config
  523  git config user.name hieugnuyen0202
  524  git config user.email hieugnuyen0202@gmail.com
  525  cat .git/config
  526  code .
  527  history
