
### Step 1: Install the Dependencies:
Linux 
```sh
apt install nodejs npm -y
curl -sL https://deb.nodesource.com/setup_16.x -o nodesource_setup.sh
chmod 777 nodesource_setup.sh
./nodesource_setup.sh
apt install nodejs -y
npm install

```
Windows 
```sh
# https://nodejs.org/en/blog/release/v16.0.0/ get node.js
npm install 
```

### Step 2: Obtain a Bot Token From [Here](https://discord.com/developers) <br> <br>
<kbd>
  <img src="https://zerosnap.000webhostapp.com/2faykzzg.gif">
</kbd>
<b>
  

### Step 3 : Replace the Token in [config.json](https://github.com/ZeroDiscord/Giveaway/blob/master/config.json) <br>
#### That's all! We Are Done! Now Simply host the Bot!

### Run with node
```sh
node index.js
```
### Run with pm2
```sh
npm install -g pm2@latest
pm2 start --name "Giveaway" index.js --watch
```

# Features
## Featuring | Slash Commands 
<kbd>
  <img src="https://zerosnap.000webhostapp.com/ktfoi0f9.gif">
</kbd>
<b>
  
### Interactive Giveaway Creation
  
  <kbd>
  <img src="https://zerosnap.000webhostapp.com/mig6cvt0.gif">
</kbd>
<b>
  
### Featured ✨ Bonus Entries 
<kbd>
  <img src="https://zerosnap.000webhostapp.com/8eblx4sc.gif">
</kbd>
<b>

  
### And Lots More!
- Direct message when the server mentioned for joining is not joined
- Direct message when the server mentioned for joining is joined 
- Direct Message When User Reacts on an ended giveaway
- Direct Message User On Removing Reaction
- Direct Message Winner On Winning
