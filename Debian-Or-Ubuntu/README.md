### Installing brave browser in Debian,Ubuntu and their derivatives 
  
 
  >brave is a popular browser, but you cannot download it directly from the distribution repositories. To help you with installing brave, I have made a shell script to do all the necessary for you :smiley:


To install Brave browser **copy the following as a whole** and paste and run this in you'r terminal 

`cd $HOME/Downloads && wget https://raw.githubusercontent.com/James-Willer/Random-solutions/main/Scripts/install_brave_deb.sh && chmod a+x install_brave_deb.sh && ./install_brave_deb.sh`


>Do you use Github Desktop? Here, this is the current version 😉 (**Copy as whole and adjust the comments if you need to**)

`sudo wget https://github.com/shiftkey/desktop/releases/download/release-2.9.4-linux1/GitHubDesktop-linux-2.9.4-linux1.deb`

 Uncomment below line if you have not installed gdebi-core before

 sudo apt-get install gdebi-core 

`sudo gdebi GitHubDesktop-linux-2.9.4-linux1.deb`
