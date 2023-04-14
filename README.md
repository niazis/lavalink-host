# lavalink-host for music bot

## Ubuntu Installation

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
