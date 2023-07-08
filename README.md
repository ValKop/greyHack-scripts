# READ ME

Hi, I'm please from GreyHack! This is my repository with basic scripts that any of you can take from here for free. The coolest and most advanced scripts you can buy in my store inside the game for in-game currency/cryptocurrency.

The scripts presented here will be useful if you don't know how to program or if you want to understand the game programming mechanics by parsing someone else's code. For such purposes, I later comment on the entire code to make it easier to understand it.

### How to install scripts

You can copy each script individually, go into the in-game code editor, paste the copied code, and compile each into /bin/<your convenient script name>. __BUT...__ 

I made sure to make it more convenient. You don't have to compile each script individually. The hardest part will be copying the code from here and pasting it into the in-game code editor, then saving all the code in a separate folder. You will only need to compile one script - "compile_in_bin". 

Compile this script in /bin/, then use the terminal to go to the directory where you saved all the scripts and write `compile_in_bin *` . The script will automatically compile all the other scripts into the desired folder

# Description of all scripts/small instruction

## shelldecipher

A script for decrypting passwords from the terminal. Saves all obtained matches **encrypted_password:decrypted password** into */home/<username>/.saved_decryptions* file. 

Just type `shelldecipher` into the terminal and press *Enter*. Then enter ONE password using the format **<login>:<encrypted password>** or just **<encrypted password>**, then press *Enter*. Then you can enter another password using the same algorithm, press *Enter* and so on until you have entered all passwords. When you run out of passwords to decrypt, just type **0** (the number zero, not the letter O)

If the script does not find such a password in the *.saved_decryptions* file, it will decrypt the password on its own and write it into the file. After decrypting all the passwords, the script displays them in a convenient format in the terminal

This script uses the game's decryption capabilities, which the game developers intentionally slowed down. But in my in-game store you can buy a script with a self-written decryption algorithm that will instantly decrypt what you need ;)
