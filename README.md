## Fixing the Adobe programs failure after open up! English and Portuguese!
![about-12 3 1] (https://github.com/user-attachments/assets/4930b730-3d47-4e05-b547-f019ae9965de)

**Latest working macOS**: 15.0
<br>
**Current OpenCore**: 1.0.1

## English tutorial below

- Step 1 - You need to go in (https://brew.sh) and copy the code line of installation that are specified in the printscream below:
 
 ![about-12 3 1] (https://github.com/user-attachments/assets/bd290a38-4efc-4820-af98-57ac5224c6ba)

- Step 2 - You need to open your terminal (it's the cmd prompet for macos) and paste the code, press enter, put your password and wait.

 ![about-12 3 1] (https://github.com/user-attachments/assets/8091373b-24f2-40d0-a7bd-0af5336b9032)

- Step 2.1 - You need to press enter again when he shows this messages and wait.

 ![about-12 3 1] (https://github.com/user-attachments/assets/eed8895e-b419-4c2c-ab06-6d834e510854)

- Step 2.2 - When it finishes the installation will it show the follow message:

 ![about-12 3 1] (https://github.com/user-attachments/assets/673b0b13-6ce4-4da6-81a4-4fa9c5f5a222)

- Step 3 - Now in the same terminal window, copy the following command to install the required script and wait for the installation to be completed (it may take a while).

 ##
 		brew install nodejs

- Step 4 - Now copy and paste in the same terminal the following command, push enter and wait for the installation to be completed.

 ##
		npm install -g amdfriend

- Step 5 - Close the actual terminal.

- Step 5.1 - Open another terminal from scratch and copy the command below and paste on terminal (DO NOT PRESS ENTER YET!)
 ##
 		sudo amdfriend --dry-run --directories

- Step 5.2 - To fix the bug for the apps, now we need to copy the directory of installation of each one, in this tutorial we are going to use the Photoshop app as example, to other apps you should do the same process

	- Go into the application folder, then click in the left arrow beside the application icon that you wanted to fix, this will open another folder and what you gonna see it's exaclty like the example below:

	![about-12 3 1] (https://github.com/user-attachments/assets/5298e2af-f5fb-47cc-a223-02a663485a99)

    - Now, drag this .app archive that you are selecting and put in the terminal that are already open with the parcial command already pasted. In this step, your terminal should be like this:

  ![about-12 3 1] (https://github.com/user-attachments/assets/e0dc9694-5eb9-4073-aa3a-715a3bc2b779)

 	- Now add the rest of the command below:

 	##
			| grep "Routines found" 

	- After this, press enter, put your password, push enter again and just wait. At the end, your terminal has to be like this:

	![about-12 3 1] (https://github.com/user-attachments/assets/459c3941-6637-4ac4-a0ca-71e7389f5e2c)

- Step 5.3 - The final step, now we are going to effective do the patch and fix the bug in the app that you have choosed. The only thing you need to do is change the command line, removing "--dry-run" and putting "--in-place --sign" in place. The rest of the command should stay the same as before!

	- Press enter and wait, it may take some time

	- At the end, your terminal should be like this:

	![about-12 3 1] (https://github.com/user-attachments/assets/30d77c51-1eb1-4dec-a52d-48cb0f22f248)

- Your adobe application should work fine right now! :)

# Extra

 - We know things can change beyond time pass by, everytime the homebrew updates, the apps we have correct can maybe bug again, the only thing you need to do is go in the homebrew website again (https://brew.sh), copy the installation code, put in the terminal and press enter, it will recognize the older version already installed and will update it.


## Tutorial em português

- Para o tutorial em português, deixo com vocês o tutorial do grande professor de hackintosh Gabriel Luchina, dono da comunidade Universo Hackintosh!

	- Tutorial: (https://www.youtube.com/watch?v=mvoXT3uhDLo&t=305s)

# Extra

 - Sabemos que as coisas podem mudar com o passar do tempo, toda vez que o homebrew for atualizado, os aplicativos que nós corrigimos podem talvez falhar novamente, a única coisa que você precisa fazer caso isso ocorra é entrar no site oficial do homebrew (https://brew.sh), copiar o código de instalação, colar no terminal, apertar enter e aguardar. Ele irá reconhecer a versão anterior instalada e vai atualiza-la!

## Thanks/Credits
- [Gabriel Luchina] From Universo Hackintosh and his video tutorial
- [Gabriel Cerqueira] From Universo Hackintosh 

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
