# READ ME

Hi, I'm NeoShop owner from GreyHack! This is my repository with basic scripts that any of you can take from here for free. The coolest and most advanced scripts you can buy in my store inside the game for in-game currency/cryptocurrency.

The scripts presented here will be useful if you don't know how to program or if you want to understand the game programming mechanics by parsing someone else's code. For such purposes, I later comment on the entire code to make it easier to understand it.

### How to install scripts

Soon I will create an in-game repository with these programs and post the ip address here. Then you will only need to do `apt-get address [ip]` and download any of these programs `apt-get install` (for example, `apt-get install wifite`). But for now...

I took care to make it more convenient. You don't need to compile each script individually. You will only need to copy the code of the programs you need and put it in the in-game code editor, and then save the code of each program in a separate folder (for example, src).

Manually you will need to compile only one script - "compile_in_bin". To do this, open the terminal, go to the directory with the code, write in the terminal: `build compile_in_bin.src /bin`

Then just write `compile_in_bin` in the terminal and the script will automatically compile all the other scripts to the desired folder

# Description/small instruction of all scripts

### wifite
![image](https://github.com/ValKop/greyHack-scripts/assets/60344304/19ab160f-1e93-428c-a166-f9618987dcbf)


Automatic wifi hacking utility. Just run it and follow the instructions

P.S. Do not interrupt the collection of ack. The program will automatically finish collecting

---
### shelldecipher
![image](https://github.com/ValKop/greyHack-scripts/assets/60344304/0d8a0b36-943b-4dfb-8083-1d01572ace97)


A script for decrypting passwords from the terminal. Saves all obtained matches **encrypted_password:decrypted password** into */home/[username]/.saved_decryptions* file. 

Just type `shelldecipher` into the terminal and press *Enter*. Then enter ONE password using the format **<login>:<encrypted password>** or just **<encrypted password>**, then press *Enter*. Then you can enter another password using the same algorithm, press *Enter* and so on until you have entered all passwords. When you run out of passwords to decrypt, just type **0** (the number zero, not the letter O)

If the script does not find such a password in the *.saved_decryptions* file, it will decrypt the password on its own and write it into the file. After decrypting all the passwords, the script displays them in a convenient format in the terminal

---
### compile_in_bin
![image](https://github.com/ValKop/greyHack-scripts/assets/60344304/cd8c59fa-7b31-4196-857f-12b0f23c473a)


Compiles all .src files from the directory where you are located
