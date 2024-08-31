# HamsterScript
### 1. Open Your VPS
```sh
cd Hamster
```
### 2. Edit your env file, input your API ID and API HASH in the spaces provided for it, edit other enviromental variables your taste.
```sh
nano .env
```
If you don't want the bot to increase your pph, add a number to your balance to save. Like the name implies, the bot will not upgrade your pph instead it will save your coins till it gets to the paticular value that you set it to. e.g BALANCE_TO_SAVE= 1000000000 means the bot will save your coins for you till 1000000000, it won't increase your pph. i don't see the point in doing balance to save because the hamster team has said they won't use coins 

### 3. After editing your .env file, save it:
CTRL O

ENTER 

CTRL X
### 4. Install requirements
```sh
python install.py
```
### 5. Run main.py
```sh
python main.py
```
### 6. Create a session
```sh
1
```
Enter a name for your session input any name you like

ENTER

enter your telegram phone number, include your country code while typing it. e.g 2348145698452

ENTER

check your telegram app for otp and input it

ENTER
### 7. Create a screen
```sh
screen -R Hamster
```
### 8. Run main.py again
```sh
python main.py
```
### 9. Run clicker
```sh
2
```
CTRL AD
### 10. Close the VPS and open and run the next script



