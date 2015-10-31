# symfony_frontend
Demo with Symfony 2.7, Bower, Bootstrap, jQuery and Gulp

- links: 
    - http://www.ymc.ch/en/symfony-2-6-step-by-step-best-practice-guide-to-building-a-website-including-bower-bootstrap-jquery-and-gulp
    - http://symfony.com/doc/current/cookbook/frontend/bower.html
    - http://es.slideshare.net/mdavis1982/optimising-your-front-end-workflow-with-symfony-twig-bower-and-gulp
    - https://github.com/romanschejbal/gassetic/blob/master/Resources/doc/GasseticAndSymfony2.md
    - https://github.com/mdavis1982/workflow
    
 - commands:    
    - ```$ curl -LsS http://symfony.com/installer > symfony.phar```
    - ```$ sudo mv symfony.phar /usr/local/bin/symfony```
    - ```$ chmod a+x /usr/local/bin/symfony```
    - ```$ symfony new <projectName>```
    
    - ```$ cd projectName/```
    - ```$ php app/console server:run```
    
    - ```$ touch .bowerrc```
    - ```$ npm install -g bower```
    - ```$ bower init```
    - ```$ bower install jquery```
    - ```$ bower install bootstrap```
    
    - ```$ npm install --global gulp```
    - ```$ npm install --save-dev gulp``` 
    
    - ```$ npm install gulp-if```
    - ```$ npm install gulp-uglify```
    - ```$ npm install gulp-uglifycss```
    - ```$ npm install gulp-less```
    - ```$ npm install gulp-concat```
    - ```$ npm install gulp-sourcemaps```