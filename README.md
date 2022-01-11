# sources-list-gen

A sources.list generator for Ubuntu.

Simply run:
```
sudo apt install git
```
```
git clone https://github.com/supernany/sources-list-gen.git
```
```
cd sources-list-gen
```
If you can’t get git, run:
```
wget -c https://github.com/supernany/sources-list-gen/archive/refs/tags/sources-list-gen.tar.gz
```
```
tar -xzf sources-list-gen.tar.gz
```
```
cd sources-list-gen-1.7
```
Then run:
```
bash sources-list-gen
```
Select your server and run:
```
sudo cp -v ~/sources.list /etc/apt/ && sudo cp -Tv ~/sources.list /etc/apt/sources.list.save
```
