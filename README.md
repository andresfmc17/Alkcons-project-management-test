# ALKCONS YII2 TEST ( PROJECT MANAGMENT )

## Project Detail

The goal of this test / tutorial is to develop a web app for managment of any type of proyects and its objectives to succed. 

At the same time to learn YII2 Framework and Basic MySql Queries at PDO style.

### Project Requirements

- git
- virtual box
- vagrant


### Installation
#### 
- Fork project-management-test repository, yii gii
- Clone git clone project- Setup work enviroment, Go to /vagrant/config/vagrant-local.yml and change your github token `github_token: <your-personal-github-token>`, follow this instruction (https://help.github.com/articles/creating-an-acce-token-for-command-line-use/)
- Add domain `project-managment.dev` on host file
- Run Vagrant up
- Run Vagrant ssh
- Create a database as `project_managment`
- Go to path /enviorments/dev/common/config/main-local.php and change dns data
- run in command line `composer install`

### Objectives

#### A Project

##### A.1 - Create Section of Projects ( CRUD ) this include a new Model, View and Controller (MVC)use `gii` command (http://www.yiiframework.com/doc-2.0/guide-start-gii.html, yii gii)

============================================================================== 

#### B Project Detail 

##### B.1 - Create Section for Project Detail 
- Create ProjectDetailController.php in /backend/controllers/ <here>
- Create Model ProjectDetailForm.php /backend/models/ <here>
- Create view /backend/views/project-detail/index.php
- Install Plugin `composer.phar require  unclead/yii2-multiple-input "~2.0"` you can read plugin instruction (https://github.com/unclead/yii2-multiple-input)
- The view of project detail should Create/Update and Delete Project Details Records.

##### A.2 Update backend/views/project/index.php and add a new button in gridview to see the project details section

#### A.3 project detail section should only display those details of the selected project.

