# Mock Server 

![mock-manual](https://github.com/joon610/readMEImg/blob/master/mock-server/mock-manual.gif)

## you can make simple API server.

1. make root directory.
2. make child directory and add json(index.json) files in child directory.
<img src="https://github.com/joon610/readMEImg/blob/master/mock-server/mock-directory.png" width="50%" height="50%">
3. open Mock-Server and select root directory
4. you can get API list!
<img src="https://github.com/joon610/readMEImg/blob/master/mock-server/mock-server.png" width="30%" height="30%">
 Directory becomes a API server as follows 
    - /Users/jungdong-joon/Downloads/root        ==  http://loacalhost:9000/
    - /Users/jungdong-joon/Downloads/root/nice1  ==  http://loacalhost:9000/nice1
5. click Api Address and then get index.json file.
<img src="https://github.com/joon610/readMEImg/blob/master/mock-server/mock-api.png" width="50%" height="50%">


<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/joon610/mock-server/releases" data-icon="octicon-cloud-download" data-size="large" aria-label="Download ntkme/github-buttons on GitHub">Download</a>

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn dev
```

### Compiles and minifies for production(electront)
```
build:electron
```

