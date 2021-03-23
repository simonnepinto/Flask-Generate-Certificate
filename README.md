<div align="center">
<img src="https://raw.githubusercontent.com/vigneshshettyin/Flask-Generate-Certificate/main/static/images/logo.png" alt="Logo" width=100 height=100>
</div>

# 🚀 Certificate Generation and Verification System
Certificate Generation and Verification System project aims in developing a computerized system to maintain and generate the certificate. It has an admin login through which the admin can monitor the whole system. It also has a facility where users after logging in to their account can monitor and generate a certificate for their particular user. Admin will manage user logins, will have the option to deactivate any user. Every time any changes are done an automated email will be sent depending on the update. Overall this project is being developed to help the users in the best way possible and also to reduce human efforts.
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/vigneshshettyin/Flask-Generate-Certificate)
[![GitHub forks](https://img.shields.io/github/forks/vigneshshettyin/Flask-Generate-Certificate.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/vigneshshettyin/Flask-Generate-Certificate/network/)
[![GitHub stars](https://img.shields.io/github/stars/vigneshshettyin/Flask-Generate-Certificate.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/vigneshshettyin/Flask-Generate-Certificate/stargazers/)
[![Issues](https://img.shields.io/github/issues/vigneshshettyin/Flask-Generate-Certificate.svg?logo=github)](https://github.com/vigneshshettyin/Flask-Generate-Certificate/issues)
[![MPL-2.0 License](https://img.shields.io/github/license/vigneshshettyin/Flask-Generate-Certificate.svg?style=flat-square)](https://github.com/vigneshshettyin/Flask-Generate-Certificate/blob/master/LICENSE)
<!--[![CodeFactor](https://www.codefactor.io/repository/github/vigneshshettyin/flask-generate-certificate/badge)](https://www.codefactor.io/repository/github/vigneshshettyin/flask-generate-certificate)-->
[![GitHub watchers](https://img.shields.io/github/watchers/vigneshshettyin/Flask-Generate-Certificate.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/vigneshshettyin/Flask-Generate-Certificate/watchers/)
![GitHub contributors](https://img.shields.io/github/contributors/vigneshshettyin/Flask-Generate-Certificate)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)


Feel free to use it as-is or customize it as much as you want.

But if you want to **Contribute** and make this much better for other developer have a look at [Issues](https://github.com/vigneshshettyin/Flask-Generate-Certificate/issues).


If you created something awesome and want to contribute then feel free to open Please don't hesitate to open an [Pull Request](https://github.com/vigneshshettyin/Flask-Generate-Certificate/pulls).

## Tech Stack:
<img alt="CSS3" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/> 	<img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img alt="Python" src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/> <img alt="JavaScript" src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white"/> <img alt="jQuery" src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"/> <img alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/> <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/> <img alt="SQLite" src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white"/> <img alt="Heroku" src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white"/>


# Getting Started 🚀

## How To Use 🔧

There are two ways of using the project:

## 1. Conventional Way

**1.** Clone this repository to your local drive
 ```shell
$ git clone https://github.com/vigneshshettyin/Flask-Generate-Certificate.git
```

**2.** Change directory into the cloned repository  
 ```shell
$ cd Flask-Generate-Certificate
```

**3.** Setup virtual environment
 ```shell
$ py -m venv env
$ .\env\Scripts\activate
```

**4.** Install requirements from requirements.txt  
 ```shell
$ pip3 install -r requirements.txt
```

**5.** Setup SQLite
 ```shell
$ py
>> from app import db
>> db.create_all()
```

**6.** Run the development server
```shell
$ flask run
```

Now open your favorite browser and go to http://127.0.0.1:5000/
You will find the application running there.

## 2. Using Docker

* Install [Docker](https://docs.docker.com/engine/install/), from the given link.

* Once Docker is installed, use the following two commands to run the app in the root dicrectory:
  * `docker-compose build` , This command will build the project
  * `COMPOSE_HTTP_TIMEOUT=200 docker-compose up`, This command will run the container.
  
* You can open the project on `localhost:5000` on the machine.

Note: If you are using docker-desktop on Windows Or WSL2 i.e Windows Subsystem For Linux, you can use the GUI Options to run the containers
## Live Deployment 📦 

Click Here to view the deployment!
 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://cgvcertify.herokuapp.com/)
<br>
<br>
When you are done with the setup, you should host your website online.
We highly recommend to read through the:<br>
- [Deploying on Heroku](#).<br>
- [Deploying on AWS](https://github.com/vigneshshettyin/Flask-Generate-Certificate/blob/main/Documentation/aws.md).<br>
- [Deploying on Azure](#).<br>
- [Deploying on Google Cloud](#).<br>
- [Deploying on Digital Ocean](#).<br>

## Mockup & Demo 🛠️

<table><tr><td valign="top" width="50%">

[![MAC](http://img.youtube.com/vi/6ZH4bZP1RgE/0.jpg)](http://www.youtube.com/watch?v=6ZH4bZP1RgE "MAC MOCKUP")

</td><td valign="top" width="50%">

[![MAC](http://img.youtube.com/vi/Ys2iFw8Bypk/0.jpg)](http://www.youtube.com/watch?v=Ys2iFw8Bypk "MAC DEMO")

</td></tr></table>  


## Illustrations
- [UnDraw](https://undraw.co/illustrations)


## Open Source Events Project is associated with:
<img align="right" src="static\images\events.png" width = "100" height = "80"><b>GirlScript Summer of Code</b>

- GirlScript Summer of Code is the 3 month long Open Source program  conducted by GirlScript Foundation, started in 2018, with an aim to help beginners get started with Open Source Development while encouraging diversity.

## License 📄

This project is licensed under the MPL-2.0 License. See the [LICENSE](./LICENSE) file for details



## For the Future 
If you can help us with these. Please don't hesitate to open a [Pull Request](https://github.com/vigneshshettyin/Flask-Generate-Certificate/pulls).

## Cool Developers🚧

<a href="https://github.com/vigneshshettyin/Flask-Generate-Certificate/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=vigneshshettyin/Flask-Generate-Certificate" />
</a>



