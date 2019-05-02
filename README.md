# node-serialport-testing

## Project setup
```
yarn install
```

### Error reproduction
1. clone this repository
2. run `yarn install`
3. run `yarn electron:build:windows` on Mac or Linux
4. copy `node-serialport-testing Setup 0.1.0.exe` to Windows and install
5. and you can see this error:

```
A JavaScript error occurred in the main process

Uncaught Exception:
Error: \\?\C:\Users\MyUser\AppData\Local\Temp\4deb32d9-50e4.....bf7b.tmp.node is not a valid Wind32 application.
```

### Run electron
```
yarn electron:serve
```

### Build multiple platforms electron
```
yarn electron:build:windows
yarn electron:build:macos
yarn electron:build:linux
yarn electron:build:all
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
