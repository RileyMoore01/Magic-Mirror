# Magic Mirror
## Installation
**Python**
```
sudo apt update
sudo apt upgrade -y
```
```
sudo apt install python3 python3-pip -y
python3 --version
```

**Libraries**<br />
***Magic Mirror***

1.) Download node.js
```
sudo apt-get install -y curl
```
```
curl -fsSL https://deb.nodesource.com/setup_22.x -o nodesource_setup.sh
```
```
sudo -E bash nodesource_setupsh
```
```
sudo apt-get install -y nodejs
```
```
node -v
```

2.) Check if git is installed by run 'git'

3.) Clone the magic mirror repository
```
git clone https://github.com/MagicMirrorOrg/MagicMirror
```

4.) Enter the MagicMirror folder
```cd MagicMirror```

5.) Install the application
``` npm run install-mm```

6.) Copy the config file
```cp config/config.js.sample config/config.js```

7.) Start the application
```npm run start```
```npm run server```


## Modules
1.) <a href='https://github.com/lavolp3/MMM-AVStock'>Stock Prices</a>
