
# _ng5-material-toolbar-demo_ Angular5 sample project for Angular Material Toolbar
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)


_ng5-material-toolbar-demo_ is an Angular5 sample project for programmers who want to use Angular Material Toolbar.

_Video Explanation_

<https://youtu.be/mDjibEEcVXI> (Engilsh)

<https://youtu.be/MDOxe5G6zqI> (Japanese)

_Full Source Code_
<https://github.com/Ohtsu/ng5-material-toolbar-demo>

## Overview 
    
At first, please refer to "Angular Material Getting started" page as follows. 
    
<https://material.angular.io/guide/getting-started>
 
This project is based on the steps explained in the page. 

The following "Step" number is based on the page. 

### Installed Libraries and Settings 

   - @angular/material (Step 1)

   - @angular/cdk (Step1)

   - @angular/animations (including the modification of 'src/app/app.module.ts' file) (Step2)

   - Add following modules  (step3)
        - MatButtonModule,
        - MatCheckboxModule,
        - MatCardModule,
        - MatRadioModule,
        - MatDialogModule,
        - MatFormFieldModule,
        - MatInputModule,
        - MatToolbarModule,
        - MatIconModule,
        - MatMenuModule

   - Add default theme(indigo.pink.css) to styles.css file (step4)

   - hammerjs (including the modification of 'src/main.ts' file (step5)

   - Add the official Material Design Icons (modification of 'index.html' file) (Step6) 


 

## Prerequisite

   - Git
   - Node.js
   - TypeScript2
   - Angular5
   - Angular/cli
   - Angular/material



## Installation

To install this program:

   - Make your own directory and change into it.

```bash
$ mkdir mydir
$ cd mydir
```
   - Make the clone as follows.

```bash
$ git clone https://github.com/Ohtsu/ng5-material-toolbar-demo.git
```

   - Change into _ng5-material-toolbar-demo_ and run "npm install".

```bash
$ cd ng5-material-toolbar-demo
$ npm install 
```


#### Check Your Program

If you start local server as follows, you can get the first page in your browser by accessing **http://localhost:4200**.


```bash
$ ng serve
```


  - ***default Page*** 

  <img src="https://raw.githubusercontent.com/Ohtsu/images/master/ng5-material/ng5-material-toolbar-01.png" width= "640" >

  - ***English Page*** 

If you want to check English page, start local server as follows, 

```bash
$ npm run start:en
```

  <img src="https://raw.githubusercontent.com/Ohtsu/images/master/ng5-material/ng5-material-toolbar-11.png" width= "640" >

  - ***Japanese Page*** 

If you want to check Japanese page, start local server as follows, 

```bash
$ npm run start:ja
```

  <img src="https://raw.githubusercontent.com/Ohtsu/images/master/ng5-material/ng5-material-toolbar-21.png" width= "640" >

#### Stop Local Server

Input **Ctrl+C** and **y+Return** to stop the local server.




## Version

   - ng5-material-toolbar-demo : 0.1
   - Angular5     : 5.0.0
   - @angular/cdk : 5.0.0-rc0
   - @angular/material : 5.0.0-rc0,
   - hammerjs : 2.0.8
   - @angular/cli : 1.5.0



## Reference

- "Agular Material Getting started",
<https://material.angular.io/guide/getting-started>

- "Custom Library for Agular5",
<https://www.udemy.com/draft/1461368/>

- "Angular5用独自ライブラリの作成",
<https://www.udemy.com/draft/1450138/>

## Change Log

 - 2018.2.8  version 0.1.5 uploaded


## Copyright

copyright 2018 by Shuichi Ohtsu (DigiPub Japan)


## License

MIT © [Shuichi Ohtsu](ohtsu@digipub-net.com)
