# mqtt-node-cli
mqtt.js node command line tool

Source code taken and adapted from: https://www.emqx.com/en/blog/how-to-use-mqtt-in-nodejs

Additional material to learn from: https://www.donskytech.com/mqtt-node-js/

1. Create new project
```bash
npm init -y
```

2. Install dependencies
```bash
npm install mqtt commander --save
```

3. Add start script to package.json
```bash
"scripts": {
  "start": "node index.js"
}
```