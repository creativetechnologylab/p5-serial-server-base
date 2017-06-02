# P5 serial server base code

Base HTML/JS code using the Node.js based [P5 serial server](https://github.com/vanevery/p5.serialport) library to proxy the serial port data into the browser.

### Running P5 serial server library
1. Make sure you have a p5 serial server library install:
```
sudo npm install -g p5.serialserver
```
Requires admin privileges.

2. Run the P5 serial server in CLI/terminal:
```
p5serial
```

Currently spits data out into a `<p>` tag but P5 library is available and ready if you want to draw on screen using that.
