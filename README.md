# remjs

    
## install from github

    $ npm install git@github.com:linliyang/mobile-remjs.git --save
        

## fis.config

    //非模块化
    fis.match('/node_modules/mobile-remjs/**', {
        isMod: false,
        useSameNameRequire: false
    });
    
## usage

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
        <script src="/node_modules/mobile-remjs/w.js?__inline"></script><!--ignore-->
    </head>