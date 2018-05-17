# WebProgrammingP2
Phase 2 Web Programming

| ejs file      | path            | Description      |Login Required     |
| ------------- |-----------------|------------------|-------------------|
| home.ejs      | /MyWallet       |page before login | No                |
| signup.ejs    | /MyWallet/signup|sign up page      | No                |
| register.ejs  | /registered     |success register  | Yes(for newSignUp)|
| login.ejs     | /MyWallet/login |login page        | No                |
| Login_home.ejs| /MyWalletHome   |HomePageAfterLogin| Yes               |
| home_user.ejs | /home           |User Home Page    | Yes               |
| goal.ejs      | /home/goal      |goal              | Yes               |
| expenses.ejs  | /home/expenses  |manage expenses   | Yes               |
| report2016.ejs| /home/report2016|report 2016       | Yes               |
| report2017.ejs| /home/report2017|report 2017       | Yes               |
| report2018.ejs| /home/report2018|report 2018       | Yes               |


**navigation1.ejs** - navigation bar for pages before login<br/>
**navigation2.ejs** - navigation bar for pages after login<br/>
        
|-- app.js<br/>
|-- package.json<br/>
|-- package-lock.json<br/>
|-- node_modules<br/>
|-- public **(all css files)**<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- goalall.css<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- myWalletcss.css<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- image **(all images)**<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- goal1.png<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- jumbotron1.png<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- slideshow1.png<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- slideshow2.png<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- slideshow3.png<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- wallet.ico<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- wallet.png<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- js **(all js file except app.js)**<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- myWalletjs.js<br/>
|-- views **(all ejs file)**<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- goal.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- home.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- Login_home.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- report2016.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- report2017.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- report2018.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- signup.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- register.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- home_user.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- login.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- expenses.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- partials<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- header.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- footer.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- navigation1.ejs<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- navigation2.ejs<br/>
|-- models **(all Schema)**<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- user.js<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- expenses.js<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- goal.js<br/>
