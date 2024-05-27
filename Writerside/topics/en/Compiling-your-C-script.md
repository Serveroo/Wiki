# Compiling your C script

The purpose of this page is to enable you to compile your C script.

- Activating the Windows subsystem for Linux

Open the ‘Enable or disable Windows features’ window and tick the *Windows subsystem for Linux* box.
![features.png](fonctionnalites.png)

- Updating WSL

Open a Powerhsell window as administrator. Enter the following command:
![wsl.png](wsl.png)

- Install Ubuntu 24.04

In Microsoft Store, install Ubuntu 24.04.
![ubuntu.png](ubuntu.png)


- Setting up an Ubuntu account

Launch the Ubuntu 24.04 application then create your account by entering a username and password.
![account.png](compte.png)

- Installing GCC

Move to the tmp folder by running the following command: ```` cd /tmp/ ````.
Then install gcc :
![gcc.png](gcc.png)

- Adding the C script

Go to file explorer, Ubuntu 24.04, then Linux, then tmp and copy your C file.
![doc.png](doc.png)

- Compiling the script

Run the following command: ```` gcc main.c -o main ````

> **Explanation**
>
> main.c is the name of the script in C
-o main is used to name the output file, in this case main
>
{style=‘note’}

You can find the compiled file in the same folder as your script:
![compiler.png](compiler.png)