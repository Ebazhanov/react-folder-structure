Best project structure for your React App
-----------------------------------------
> the idea of this repo is to show how you can structure files by using folders
```
├── node_modules (.gitignore)
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src
│   ├── assets
│   │   │   ├── images
│   │   │   └── logo.svg
│   ├── constants
│   │   └── environment.js
│   ├── components
│   │   ├── app
│   │   │   ├── App.css
│   │   │   ├── App.js
│   │   │   └── App.test.js
│   │   └── index.js
│   ├── utils
│   │   ├── ...
│   │   └── index.js
│   ├── index.css
│   ├── index.js
│   ├── serviceWorker.js
│   └── setupTests.js
├── .gitignore
├── package.json
└── README.md
└── yarn.lock
```
