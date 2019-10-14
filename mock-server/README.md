# Mock Server 

![mock-manual](https://github.com/joon610/readMEImg/blob/master/mock-server/mock-manual.gif)


## you can make simple API server.

1. make root directory.
2. make child directory and add json(index.json) files in child directory.
![mock-directroy](https://github.com/joon610/readMEImg/blob/master/mock-server/mock-directory.png)
3. open Mock-Server and select root directory
4. you can get API list!
![mock-server](https://github.com/joon610/readMEImg/blob/master/mock-server/mock-server.png){: width="50%" height="50%"}
5. Directory becomes a API server as follows 
    - /Users/jungdong-joon/Downloads/root        ==  http://loacalhost:9000/
    - /Users/jungdong-joon/Downloads/root/nice1  ==  http://loacalhost:9000/nice1
6. click Api Address and then get index.json file.
![mock-server](https://github.com/joon610/readMEImg/blob/master/mock-server/mock-api.png){: width="50%" height="50%"}


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

