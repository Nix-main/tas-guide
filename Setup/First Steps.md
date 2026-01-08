# First Steps
#### So, I have Linux, now what?
Now that you have Linux installed, you should have access to a Linux command prompt. If this is your first time using it, assuming you're using Debian or a Debian based distribution (such as Ubuntu), I recommend running the following commands: 
`sudo apt update `
`sudo apt upgrade `

The first command will update your package sources so you're fetching the latest version of everything, and the second command will update everything for you to ensure that you've got it all up to date.
After that, you should install the libTAS file. I recommend installing the latest "interim" build, which is a build that happens automatically when changes are pushed to the repository, as it often has updated features compared to the main releases. The files can always be found here. If you're on a debian-based distribution as mentioned above, you should install the file ending in `.deb`, for anything else, the file ending in `.AppImage` will work instead.

If you're not using WSL2, you should install these things in your Linux installation. If you are, installing them on Windows is fine. If you open File Explorer and scroll down on the left, you should find that you can now access a Linux file system. Place the files under `home/your_linux_username`, as that is the default terminal location.