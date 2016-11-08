#AngularJs 2 seed for Visual Studio 2015

This Angularjs 2 seed for Visual Studio 2015 targets Angular version 2.1.0 released on Oct 12, 2016. This project is based on official Angular2 Seed project. It relies on TypeScript and SystemJS.
angularjs 2 seed

#Instructions:

-1 Clone or fork the repocitory.
https://github.com/jomendez/AngularJs-2-Visual-Studio-2015
-2 Make sure you have node installed, this code require node v5.x.x or higher and npm v3.x.x or higher, to check what version you are using run node -v and npm -v, in your cmd console.
-3 Open a cmd console, and go to your project root file location and run npm install to install dependencies

#npm behind a corporate proxy

If you are trying to setup the seed behind a proxy, you migth encounter issues of connection refuced, etc. You can use the following command:
With password:

     npm config set proxy=http://<username>:<pass>@proxyhost:<port>
     npm config set https-proxy=http://<uname>:<pass>@proxyhost:<port>
     
or without password:

    npm config set proxy=http://proxyhost:<port>
    npm config set https-proxy=http://proxyhost:<port>


#Fixing errors when using resharper

If you don't have installed resharper in your computer please ignore this section, if you have it intalling, resharper migth cause cause some sintax error validation.

Error:
"Typescript Feature 1.5. Current language level is 1.4".

Solution:
Resharper setting. From the menu bar in VS2015 -> Resharper -> Options -> Code Editing -> TypeScript -> Inspections -> Typescript language level, change to 1.5

Error:
Symbol 'component can not be properly resolved, probably its located in an inaccessible module'

Solution:
You can disabled resharper's typescript inspection for now.
Resharper > Options > Code Inspection > Settings
Find 'File masks' (bottom right) and add *.ts



#Browser support

The Angular 2 seed runs on all major browsers including Internet Explorer 11+, Edge, Firefox, Chrome, Opera and Safari.

License

The Angular 2 seed is released under the MIT license.
