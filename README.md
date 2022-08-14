# **AJAX Project setup steps:**

1. Create a new file named .gitignore and add the file paths that needs to be ignored:
````angular2html
/.idea
/.parcel-cache
/node_modules
````

2. Create a first commit:
```angular2html
git init
git add .
git commit -m 'commit name here'
```

3. Create a new repository:
```angular2html
git remote add origin git@github.com: your-git-username-here/project-name-here.git
git branch -M main
git push -u origin main
```

4. Create a feature branch:
```
git checkout -b feature/feature-branch-name-here
```

5. Create a new folder named `src` and add `index.html`, `main.js` and `styles.css`to the folder. 


6. Link the JS and CSS file to the HTML file (don't forget to set the type attribute):
````angular2html
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="./styles.css">
    <title>Title</title>
</head>
<body>
  <script src="main.js" type="module"></script>
</body>
</html>
````

7. Initialization of Node Package Manager (and enter through the basic setup):
```
npm init
```
8. Install developer bundler package Parcel:
```angular2html
npm install parcel --save-dev
```
9. Add start command to scripts object in the package.json file in order to run parcel:
```angular2html
"scripts": {
   "start": "parcel src/index.html",
},
```
10. Run your project:
```angular2html
npm run start
```






