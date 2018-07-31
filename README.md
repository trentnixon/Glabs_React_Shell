## Glabs Australia React Shell

This repo is a basic React shell for Glabs Australia. Its purpose is to help with the templating of repetitive components for Immersive Client work.

Current Version 0.4.0

### Download, Install, Edit, Integrate,Build, Stage and  Deploy

- Clone This Repo in VSC
- npm install :Fetch Package dependencies.
- Edit CDN/Server Paths
- Integrate with Client Application.
- Stage in Surge
- Deploy to Composer


## Clone Repo

Clone using VSC:
> https://github.com/trentnixon/Glabs_React_Shell.git

 ## Install
> npm install

Only libraries to run basic functions will be installed at this point. No Application specific files will be downloaded.






 ## Start Instance

Start the development server on your local host

 > npm start


## Production/Build Dependency edits

When running the Build Command, webpack will use the $cdn/$http variable as its path. Three Instances will need to be amended to the server location
```
App.js
Line: 23:
App.scss
Line :59
_Theme_Fonts.scss
Line : 3
```
## Produce Build Files
 > npm run build




What The shell has (theming, header,footer etc)

Example images,
http://react-shell.surge.sh/assets/images/Picture%205.png
  Example link
[Live Demo ](http://react-shell.surge.sh/).



Purpose of file.
This is a baseline React Template for Glabs Australia Atom Templates.
The Template is a basic shell and Structure use to host client builds and bespoke applications.


Adding content to the template
Editing the theme
How to Set up files for Application
GA Code





Set up for Deployment






