NODE environment configuration

a)Download node from nodejs.org

b)Type command --> node -v to find out the version

c)Type cpommand --> node and type console.log('test') should give the below
test
undefined

d)npm init will generate a package.json with bare dependencies and project metadata

e)Install gulp dependencies --> npm install --save gulp@3.9.0 gulp-connect@2.2.0 gulp-open@1.0.0 
   
       gulp --> build processor
       gulp-connect --> Runs a local dev server       
       gulp-open --> open url in a web browser
       
  
f) Create src code for active development and dist for writing files with build process

d) install browserfy dependencies its middleware --> npm install  --save browserify reacitfy vinyl-source-stream

   browserify --> module bundler for JS
   reactify --> compile jsx to js
   vinyl-sourec-stream --> use conventional text streams with gulp

