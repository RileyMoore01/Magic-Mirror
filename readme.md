# Magic Mirror

My very own version of a magic (smart) mirror. <br />
Capabilites:
- Controlling your Spotify
- Viewing your favorite stock prices, changes, and profit since your purchase price
- Full weather forecast including tempatures for the next few days, wind, sun rise/set, and 'feels like tempature'
- Calendar with upcoming events
- Clock counting down to the second with date, day, and year
- Facial Recognition for authorized users
- New york times headline pop ups
- New dad joke every minute


<details>
  <summary><strong>Installation</strong></summary>
  
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
  <summary><strong>Hardware</strong></summary>

  - Raspberry Pi 4B (4GB)
  -  Sim card for os and software
  -  Monitor to display smart mirror
  -  Way film or glass
  - Wood for mirror frame
  - (Optional) Camera for facial recognition 
</details>

<details>
  <summary><strong>References</strong></summary>
  - <a href='https://www.youtube.com/watch?v=A3TRxFzt7SA'>Youtube ref with product links</a>
</details>
