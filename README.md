# System Information

Useful to track resource usage on your operating system or vps etc.

# Install node

Visit [https://nodejs.org/en/download](https://nodejs.org/en/download) to download nodejs and npm.

# Install build dependencies if on linux

`sudo apt-get install build-essential`

# Install dependencies

`npm install`

`npm install -g pm2`

# Run

`pm2 start app.js --name watcher`

# Stop

`pm2 stop watcher`