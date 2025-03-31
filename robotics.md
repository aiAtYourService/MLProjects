#### Gazebo: robot simulation tool
##### installing:
- `sudo apt-get update
sudo apt-get install curl lsb-release gnupg`
##### install gazebo:
- `sudo curl https://packages.osrfoundation.org/gazebo.gpg --output /usr/share/keyrings/pkgs-osrf-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/pkgs-osrf-archive-keyring.gpg] http://packages.osrfoundation.org/gazebo/ubuntu-stable $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/gazebo-stable.list > /dev/null
sudo apt-get update
sudo apt-get install gz-harmonic`
##### run via: 
- `gz sim`

#### ROS: 
- tools and libraries that help build robot applications.
- [documenation](https://docs.ros.org/en/jazzy/index.html)