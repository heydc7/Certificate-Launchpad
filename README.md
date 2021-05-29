<div align="center">
  
![banner](images/banner.png)

# Welcome to Certificate Launchpad :rocket:

Automatically Send Custom Named Certificates via Email

[![forthebadge](https://forthebadge.com/images/badges/it-works-why.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)


![Issues](https://img.shields.io/github/issues/dhanrajdc7/Certificate-Launchpad)
![Pull Requests](https://img.shields.io/github/issues-pr/dhanrajdc7/Certificate-Launchpad)
![Forks](https://img.shields.io/github/forks/dhanrajdc7/Certificate-Launchpad)
![Stars](https://img.shields.io/github/stars/dhanrajdc7/Certificate-Launchpad)
[![License](https://img.shields.io/github/license/dhanrajdc7/Certificate-Launchpad)](https://github.com/dhanrajdc7/Certificate-Launchpad/blob/master/LICENSE)
  
</div>

# Intro
After any event, sending certificates to attendees or participants is very frustrating & difficult task. So, this is where Certificate Launchpad comes in! Certificate Launchpad simplifies the process of sending Bulk Custom Certificates to Bulk Emails of Participants. 

# Demo
![demo](https://user-images.githubusercontent.com/39642060/119229315-11217c00-bb35-11eb-8b76-c386248f2321.png)


# Getting Started
- Clone this repo `git clone https://github.com/dhanrajdc7/Certificate-Launchpad`
- Suggested IDE: `JetBrains PyCharm IDE`
- Install all dependencies from `requirements.txt` by using `pip install -r requirements.txt`
- **Copy `.env.sample` and rename it `.env`** using
  - `copy .env.sample .env` on Windows
  - `cp env.sample .env` on Unix-based Operating systems
  
# Setting Up Gmail
- `Sign In` -> Select `Manage your Google Account` -> Go to `Security` -> Turn on `Less secure app access`
- Add your Email ID & Password in `.env`
- SMTP Gmail Daily Limit - 1000
- Add `Subject` & `Body` in `.env`

# Data
- Add Attendees/Participant Data in Excel Sheet in above format & Modify Name of file in `.env`

| NAME | EMAIL |
| ---- | ----- |
| Dhanraj Chavan | dc6707914@gmail.com |

# Certificate Template
- Import your Certificate Template to project directory
- Rename template name Or Change template name in `.env`

# Adding Name to Certificate
![banner](images/axis.png)
- Identify the `Starting Point` in your Certificate Template & Add it in `.env`
- If the name length is larger than 20, then the name will be converted to shortened form.

# All Set
- Run the code to send certificates to mails
- Wrong or Incorrect emails will be printed at the end

# Questions?
Drop your message in [Discussion Section](https://github.com/dhanrajdc7/Certificate-Launchpad/discussions)

# Want to Contribute?
Take a look at [Contributing Guide](https://github.com/dhanrajdc7/Certificate-Launchpad/blob/main/CONTRIBUTING.md)

# Enjoying this Project? 
If you like this project & you want to support, buy me a coffee. Give ⭐️ to this project to spread a word!

# Project Admin
<div align="center">

<a href="https://github.com/dhanrajdc7"><img src="https://avatars.githubusercontent.com/u/39642060?v=4" width=150px height=150px /></a> 
  
### **Dhanraj Chavan**

[<img src="https://image.flaticon.com/icons/png/512/185/185983.png" width="35" padding="10">](https://www.youtube.com/codingpotter/)
[<img src="https://image.flaticon.com/icons/svg/185/185964.svg" width="35" padding="10">](https://www.linkedin.com/in/dhanrajdc7/)
[<img src="https://www.flaticon.com/svg/static/icons/svg/1312/1312142.svg" width="35" padding="10">](https://www.twitter.com/codingpotter)
[<img src="https://image.flaticon.com/icons/svg/185/185985.svg" width="35" padding="10">](https://www.instagram.com/codingpotter/)

<a href="https://www.buymeacoffee.com/codingpotter"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=codingpotter&button_colour=5F7FFF&font_colour=ffffff&font_family=Cookie&outline_colour=000000&coffee_colour=FFDD00"></a>
  
</div>
