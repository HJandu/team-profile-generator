<p align="center">
<img src="/images/banner.jpg"
/p>

## Content 
* [Description](#descr-header)
* [Installation](#install-header)
* [Technologies used](#tech-header)
* [Credits](#cred-header)
* [Deployment](#deploy-header)
* [Team](#coll-header)
* [License](#lic-header)

## <a id="descr-header"></a>Description
This application will take in information about employees on a software engineering team, and it will then generate an HTML webpage that displays summaries for each person. The webpage displays the team's basic info so that a user has quick access to their teams emails and GitHub profiles.


## Installation
The application uses [Jest](https://www.npmjs.com/package/jest) for running the unit tests and [Inquirer](https://www.npmjs.com/package/inquirer) for collecting input from the user. The application will be invoked by using the following command:

```bash
node index.js
```

Make sure to `git clone` the repository `https://github.com/HJandu/team-profile-generator.git`

## Screenshots
When you start the application, you will be prompted to enter the **team manager**’s:
* Name
* Employee ID
* Email address
* Office number

When you haved entered those requirements then you will be presented with a menu with the option to:
* Add an engineer
* Add an intern 
* Finish building the team
You will return to this menu after you have input the details for your chosen team member.

If you select the **engineer** option then you will be prompted to enter the following details:
* Engineer's Name
* ID
* Email
* GitHub username

If you select the intern option then you will be prompted to enter the following details:
* Intern’s name
* ID
* Email
* School

<p align="center">
<img src="/images/input_info.png"
/p>
  

When you have finished building your team, then you will exit the application, and the HTML is generated. See the image below.

<p align="center">
<img src="/images/colouredmain.jpg"
/p>

## Demo Video

[teamGenerator.webm](https://github.com/HJandu/team-profile-generator/assets/116304118/02a28e19-bdbf-4556-a5f0-6da0c52e22a4)

## Tests
In order to run the test, type `npm run test` in the commond-line. 

 ## Credits 

  fs - https://nodejs.org/api/fs.html

  jest - https://www.npmjs.com/package/jest

  inquirer - https://www.npmjs.com/package/inquirer
  
## <a id="lic-header"></a>License:
This project is licensed by [MIT](https://github.com/HJandu/LyricLift/tree/main?tab=MIT-1-ov-file) License. &copy;Hardip Jandu
