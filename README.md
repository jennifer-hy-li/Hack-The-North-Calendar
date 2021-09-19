## Downloading Steps
1. download vscode
2. have node.js installed
3. open a new file
4. clone the github into your local machine
    a. do this by typing "git clone https://github.com/jennifer-hy-li/Hack-The-North-Calendar.git" into the terminal
    b. get into the app.js folder by typing "cd hack-the-north-calendar" into the terminal
    c. "npm install" into terminal
5. "npm run start" into the terminal. this will open a new tab in your browser of the webpage
    
## Contents
```
src
├── App.js          # main React app
├── index.css       # root-level styling
└── index.js        # React entrypoint (where React gets inserted into the page)
```

## Config
### Styling
Root page styling is done in `src/index.css`. All component styling is done through [`styled-components`](https://styled-components.com/docs/basics#getting-started) (example in `src/App.js`).

### Page Metadata
To customize the font, page title, page icon, etc. you can customize the page skeleton over in `public/index.html`. 

All fonts are served through [Google Fonts](https://fonts.google.com/), you can pick and choose your own over there!

### Deployment
[Vercel](https://vercel.com/) is the recommended way to deploy this site to the internet. [Current deployment](https://min-react.vercel.app/)
