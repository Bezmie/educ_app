# Educ_app

### Webpack:

Common:
``````
  context => src
  output  => dst
        
  clean dst            with 'CleanWebpackPlugin'
  copy files from src  with 'CopyPlugin' to dst
       
  scss  => css
  alias => @ = __dirname + src
``````

Serve environment:
  ``````
  webpack-dev-server with browser-sync
  source-maps
  ``````
Prode environment:
  ``````
  minifies html,css,js
  hashing file js, css
  ``````

### Needs
  Node.js
### Preps
  ```
  npm i
  ```
### Start
Serve Mode
  ```bash
  npm run serve
  ```
Prode Mode
  ```bash
  npm run build
  ```