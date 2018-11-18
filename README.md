# Angular-GettingStarted-0
2018 11 01 MV: APM-START repo for Pluralsight course "Angular: Gettings Started" : https://app.pluralsight.com/library/courses/angular-2-getting-started-update/table-of-contents

# BEGIN MVOGT LOG...

## 2018 11 01 1100p 
CREATED (manually) new cloud repo /markvogt/Angular-GettingStarted-0

COPIED URL

LAUNCHED VScode fresh

CLONED cloud repo to local repo
* EXECUTED >git.clone 
* PASTED URL
* CREATED new local repo dir at OneDrive markevogt@outlook.com/Development/GitHub/Angular-GettingStarted-0
* DOWNLOADED ZIP of entire cloud repo from DeborahK repo
* UNZIPPED
* COPIED only /APM-Start/ folder to local repo (above)

RAN >npm install

RAN >npm audit fix

RAN >npm start 

=> WORKS !!! 

UPDATED readme.md 

COMMITTED to local repo

PUSHED to cloud repo

PAUSED for night !!

## 2018 11 04 MEV
CONTNUED lesson

TRIED to simply open local repo on htp envy and run >npm start, but generated an error message (something I'm forgetting?)

REMEMBERED ! NEED to cd into the \APM-Start DIRECTORY before launching the >npm start command !!!!!

CD-ed into .\APM-Start

RE-TRIED >npm start

=> worked :-) ! 

## 2018 11 05 MEV

CONTNUED lesson...

LEARNED about Angular Components, Angular Modules, Angular Decorators...

REMOVED AngularCLI-generated guts of App.Component.ts file

RE-CODED App.Component.ts from scratch (imports, decorators, class declaration, properties)

REMOVED AngularCLI-generated guts of index.html file

RE-CODED index.html 

=> WORKED :-) ! 

COMMITTED + PUSHED

PAUSED for night...

================================================================

## 2018 11 17 700a CST MV: 

CONNTINUED tutorial; REVIEWED lessons so far; BEGAN work on more complex lessons re: creating components, routes...

INSTALLED (Twitter) Bootstrap 4.1.3 and current FontAwesome using >npm install bootstrap fontawesome    

=> some warnings about some jQuery-related dependencies requiring manual installation, but tutorial explain warnings can be IGNORED because 

are only using a subset (the STYLING features) of the entire Bootstrap library... 

RAN >npm audit fix       in order to resolve some of the 12 resulting "vulnerabilities" (9 low, 3 high)

=> fixed ZERO vulnerabilities :-( . LIKELY due to the missing dependences needed for a FULL install of Bootstrap & FontAwesome... 

ADDED COMPONENT: "product-list.component" 

CREATED product-list.component.html 

CREATED table in product-list.component.html

ADDED dynamic population to table using *ngIf and *ngFor  Angular system directives - VERY ELEGANT :-) VERY POWERFUL :-) 

=> ALL WORKS FINE !!! 

NEXT: need to learn how to: 

MAKE a REST call into SharePoint Online (o365) from this Angular SPA

RETURN the list of SPList Items in a JSON response document; and 

LOOP through this JSON (I THINK) one row at a time, and populate the Angular7 dynamic HTML table using the SPLIST as the data source ! 

PAUSING FOR THE NIGHT 

===========================================================

## 2018 11 18 639a CST MV: 

CONTINUED tutorial... 

LEARNED about Interpolation, Property Binding, Method Binding; 

ADDED property binding to IMG element...

ADDED method binding to Hide/Show Image button...

=> ALL WORKS :-) 

SAVED | COMMITTED | PUSHED...

