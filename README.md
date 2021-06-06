# glava-config
Glava Configuration

![alt text](https://github.com/duchys/glava-config/blob/master/example.png?raw=true)

# Dependencies
glava

# Installation
cd /tmp
git clone https://github.com/Duchys/glava-config.git
cd glava-config
cp bars.glsl rc.glsl ~/.config/glava/.

# Post Installation
rm -rf /tmp/glava-config

# Initial startup
glava --desktop

# Command to use for automatic startup (firstly you have to set the automatic startup process, based on your DE)
# The 10 second sleep is used to wait for your desktop to be already set up
sh -c 'sleep 10 && glava --desktop'
