# Responsive Webpage Template based on Flexbox
Webpage Template Created with Pure &amp; Advanced HTML &amp; CSS with the help of Flexbox.
***
## Project Status :

__`COMPLETE`__ :fire: 


[![Netlify Status](https://api.netlify.com/api/v1/badges/369ac658-c6ba-4034-bc69-b10583a96b9e/deploy-status)](https://app.netlify.com/sites/flexboxtemplate/deploys)


## Environments Required :
* [Nodejs](https://nodejs.org/en/download/)
* [Npm](https://www.npmjs.com/package/download)
* [Git](https://git-scm.com/downloads)
## Check for proper Installation :

    $ node -v
    $ npm -v
    $ git --version
    
## Developer Dependencies :
* `node-sass` [:link:](https://www.npmjs.com/package/node-sass)
* `autoprefixer` [:link:](https://www.npmjs.com/package/autoprefixer)
* `live-server` [:link:](https://www.npmjs.com/package/live-server)
* `npm-run-all` [:link:](https://www.npmjs.com/package/npm-run-all)
* `postcss-cli` [:link:](https://www.github.com/postcss/postcss-cli)


## SASS Compiler :
1. Scripts :
   * Compiled CSS :
   
         node-sass sass/main.scss css/style.comp.css 
   * Live SASS Compiler :
            
         node-sass sass/main.scss css/style.css -w
   * Live Server :
   
         live-server
   * Live SASS Compiler + Live Server (Parallel Flow) :
   
         npm-run-all --parallel devserver watch:sass
   * CSS Prefixer for Browser Compatibility :
   
         postcss --use autoprefixer -b 'last 10 versions' css/style.concat.css -o css/style.prefix.css
   * Compress CSS Code :
   
         node-sass css/style.prefix.css css/style.css --output-style compressed
   * Build Mode (Compile SASS + CSS Prefixer + Compress CSS) - Sequential Flow :
   
         npm-run-all compile:sass prefix:css compress:css

2. Install Clients :

        $ git clone https://github.com/notsonoobie/Modern-Responsive-Web-Template.git
        $ npm install

3. Run SASS Compiler :

       $ npm run compile:sass
4. Production Mode :

       $ npm run build:css
5. Development Mode :

       $ npm run start
***
## *Project Description* :

This is a Website Template build with the help of Flexbox and Advanced CSS Features which is fully responsive to several view-ports. This project is powered by Prof. Jonas Schmedtmann (Github [@jonasschmedtmann](https://github.com/jonasschmedtmann)). This project is fully packed with new/advanced CSS Tricks &amp; Syntax. SASS Preprocessor is used which will help to achieve Usability, Scalability, &amp; Maintainability.
The `main.scss` file  will be compiled to `style.css` inside `css` Directory using NPM SASS Compiler which passes through AutoPrefixer &amp; Compressor.

## Table of Contents :

1. Navigation - Navigation Button which remains at a fixed position on extreme right side of the page.
2. Header - Contains Header Elements & Contents
3. Main - Contains Main Elements &amp; Contents of the Webpage.
4. Responsive Design - The website if fully Responsive for Small Phones, Landscape Tablets, Portrait Tablets, Desktop &amp; Big Desktops.

## **NOTE** :

You can use the template under ISC License but mention of Author ( Rahul Gupta [@notsonoobie](https://github.com/notsonoobie) ) is appreciable.
***
   
   ## *Contact Me*

:phone:   +91-89288-85199

:e-mail:  swastikmedical74@gmail.com

:octocat:  [notsonoobie](https://github.com/notsonoobie)

***

&copy; Rahul Gupta ([notsonoobie](https://github.com/notsonoobie)) -- Thank You! :nerd_face:
