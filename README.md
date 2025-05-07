So You Found My Bash Scripts...
…and you actually want to use them? Brave soul.

First off—do you really need these tools? Probably not. But hey, if you're still curious or just like tinkering, no worries—I’ve got you covered. 😊

🐧 A Quick Heads-Up
All of these scripts were written for Linux, and they expect a properly set up Linux environment. That means:

You should have a working Linux system (obviously).

The tools each script relies on must be installed and accessible.

You need appropriate permissions to run the commands the scripts use.

If you're using something like Arch Linux, I’m assuming you know what you’re doing. (And if not, how did you even get Arch running?) Either way, make sure your system is correctly configured before you try these scripts. Otherwise, things might break, and you’ll be yelling at the terminal for no good reason.

✅ Prerequisites
Before using the scripts, make sure:

Your OS is set up properly.

Dependencies used in each script are installed.

Your user has the necessary permissions.

🚀 How to Use
Using one of my scripts is pretty simple:

Open your ~/.bashrc file using your favorite editor (like nano, vim, etc.):

"sudo nano ~/.bashrc"

Paste the function/script you want to use at the end of the file.

Save the file and then reload it with:

"source ~/.bashrc"

Done! You can now use the script as a command from anywhere in your terminal.

For example, to use my docker-shutdown tool (which lists and shuts down all or specific Docker containers), just run:

"docker-shutdown"

❓ Need Help?

Maybe you are using windows and still want to use my tools, for this case i strongly advice you to use WSL to do so, yes in theory you could get it working using something like git-bash.
But that comes with a LOT of overhead and complications so save urself the hastle and just install WSL ;)

If something's not working or you're confused, don’t worry—ChatGPT will probably be more than happy to help you debug things. 😉

Have fun, and maybe—just maybe—these tools will come in handy.
