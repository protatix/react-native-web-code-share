
# REACT NATIVE [WEB] CODE SHARE WITH LERNA + TypeScript
## Code sharing between Mobile and Web
As you know, we still can't use symlinked modules in React Native. [Github](https://github.com/facebook/metro/issues/1)
This is the template that you are able to code sharing between React and React Native. Includes **Redux-Saga** with TypeScript.
Tool management with lerna so first you need to install on your computer.

![Demo](https://i.imgur.com/4C1rm2Q.png)

- Install Lerna
```
$ npm i -g lerna
```

### Then install packages
```
$ yarn bootstrap
```

### Start Web Version
```
$ yarn web
```

### Start IOS Version
```
$ yarn ios
```

### Start Android Version
```
$ yarn android
```

### Delete All Node Modules
```
$ yarn clean
```

### Clean Cache, Delete All Node Modules and reinstall again
```
$ yarn reset
```

