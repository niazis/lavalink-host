# lavalink-host for music bot

## Linux
- download curl
```cmd
sudo apt install -y curl
```

**Note**: _Java v11 or newer is required to run the Lavalink.jar. Java v13 is recommended._ If you are using **sdkman** then _its a manager, not Java, you have to install sdkman and use sdkman to install Java_

**Warning**: Java v14 has issues with Lavalink.

- download or gitclone 
```cmd
git clone https://github.com/brblacky/lavalink-server.git
```
- cd `lavalink-server`

- Run lavalink and install java
`chmod +x start.sh`

To run your script : `./start.sh`
Another option is as follows to execute shell script: `sh start.sh` OR `bash start.sh` Or `sudo bash start.sh`

**pm2**

- install node.js 
```cmd
sudo apt update
```
```cmd
sudo apt install nodejs

```

- install pm2 `npm i pm2`
- run `pm2 start java -- -jar Lavalink.jar`
