# Magic Mirror

My very own version of a magic (smart) mirror. <br />
Capabilites:
- Controlling Spotify


<details>
  <summary>Installation</summary>
  
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
  1.) <a href='https://github.com/lavolp3/MMM-AVStock'>Stock Prices</a><br/>
  2.) <a href='https://github.com/skuethe/MMM-Spotify'>Spotify</a><br/>
  3.) <a href='https://github.com/brucetony/MMM-Dad-Jokes'>Dad Jokes</a><br/>
  4.) <a href='https://github.com/EbenKouao/MMM-SmartTouch'>Smart Touch</a><br/>

</details>

<details>
  <summary>Hardware</summary>

  1.) Raspberry Pi 4B (4GB)
  2.) Sim card for os and software
  3.) Monitor to display smart mirror 
  4.) 2 Way film or glass
  5.) Wood for mirror frame
  6.) (Optional) Camera for facial recognition 
</details>
