install om Termux

apt update && apt upgrade
pkg install wget
pkg install git
pkg install openjdk
pkg install openjdk-17
git clone https://github.com/GiantSriracha/ddos.git
cd ddos
java ddos.java
