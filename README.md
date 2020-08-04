# DesignTemplate
Design Template HTML 5 - Sass - Media Query

to compile sass to css

1- donload Node & setup

2- npm init to create package.json file

3-download node-sass

4- to compile the sass file add the following script to 
package.json scripts 

"scripts": {
    "sass": "node-sass -w scss/ -o dist/css/ --recursive"
  },

5- to run the code type the command "npm run sass" in the terminal 
