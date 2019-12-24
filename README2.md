Start an sass project with
```
npm init -y
npm node-sass
mkdir scss
mkdir dist
```

Inside package.json 
```
 "scripts": {
    "sass": "node-sass scss/ -o dist/css/ --recursive"
  },
```
I did not get it to work with the -w flag. I decided to worry about that on the next project.

run sass with
```
npm run sass
```