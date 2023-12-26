
# Kurīnā
## Table of Contents
* **About**
* **Donate**
* **Usages**
  * **Install**
  * **Example**
* **License**
## About

Command line tool to clear python cache.
This will fully work on the Linux command line.

## Usages
To use it is very easy, just follow the instructions carefully and carefully.
#### Install
First, please clone this repository
```sh
git clone https://github.com/hxAri/Kurina
```
Change the current working directory
```sh
cd Kurina
```
##### Install as Command
Move Kurina to the binary directory.
```sh
mv kurina /usr/bin/kurina
```
And then make it as executable
```sh
chmod +x /usr/bin/kurina
```
or install with **update-alternatives** command
```sh
sudo update-alternatives --install /usr/bin/kurina kurina $(pwd)/kurina 0
```
It will make it as auto mode

## Example
To use it is quite easy, just continue the location of your Python project.
```sh
kurina /path/to/project-name
```
or, clear your current working directory
```sh
kurina
```

## Donate
Give spirit to the developer, no matter how many donations given will still be accepted<br/>
[paypal.me/hxAri](https://paypal.me/hxAri)

## Licence
All Kurīnā source code is licensed under the GNU General Public License v3. Please [see](https://www.gnu.org/licenses) the original document for more details.