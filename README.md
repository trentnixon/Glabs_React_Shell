## Glabs Australia React Shell

This is a baseline React Template for Glabs Australia Atom Templates.
The Template is a basic shell and Structure use to host client builds and bespoke applications.
Current Version 0.4.0

### Download, Install, Edit, Integrate,Build, Stage and  Deploy

- Clone This Repo in VSC
- npm install :Fetch Package dependencies.
- Edit CDN/Server Paths
- Theming Template
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

### Example Image,
http://react-shell.surge.sh/assets/images/Picture%205.png
### Example link
[Live Demo ](http://react-shell.surge.sh/).



## Adding an Application

The template allows for easy integration of any client react applications as developed by Glabs. Applications are downloaded separately and manually installed.
- 1: Clone base application from git.
- 2: Move Application files to Template Structure:
```
-src
    -js
        -Application
```
Each Application should come with a ReadMe file for any specific Application Installation steps

- 3: Link Application to the Template
```
    -src
        -js
            -pages
                -Main.js : Line 6
                // Application
                import Default from "../Application/Default/Default";
    
                Imported Component Name can also be amended from “Default” to “Application Name of choice”
```
- 4: Move Application.json
	```
	Move Application.json file found in 
            
            -js
                -Application
                    -json/Application.json” 
            to 
            -Public
                -Json” 

            Overwrite or append to file in this folder
            Load.js will be hooked up to read this file.
```
- 5:Include new path to Application Reducers and uncomment Reducer Instance
```
	-src
        -reducer
            -index.js
        Update the APP path to the   Application Name]/reducer file
        //import APP from "../js/[Application Name]/reducers/Application.js";
    
        Uncomment Line:8
        //APP:APP
```
- 6:Hook up Actions
```
	Insure path to “store” is correct
```







## Theming Template and Applications
What The shell has (theming, header,footer etc)





Purpose of file.



Adding content to the template
Editing the theme
How to Set up files for Application
GA Code





Set up for Deployment






