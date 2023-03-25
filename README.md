# OvershadowLinux
Overshadow Linux is an open-source UNIX OS written in 100% Python (excluding the kernel, of course). It's goal is to allow mid-level coders to create small .sh scripts of small Python scripts / packages.
### Contibuting to the Kernel
If you'd like to contribute to the Overshadow Linux kernel, we reccomend the following process:
- Read the Kernel section below.
- Fork the repository.
- Make changes / write code.
- Send a pull request to the main repository with a changelog. The pull request should contain a CHANGELOG.txt file.
- Done!
### Kernel
The Overshadow kernel is still in the earliest stages of development. Currently, we're working on the OS itself and will finish the kernel once the OS is ready. The kernel is simple -- all it does is run a Python script. Our goal with this is to allow high-level coders to help with the kernel and once we have the kernel, allow Python coders of all levels make improvements to the OS. If you want to help with the kernel, it should do the following:
- Run a Python script.
- Have a Bash interface for using Bash commands via Python.
- Should have a tiny starting script that asks for 2 inputs (the SSID and the network password) and connects to a WiFi network with this. This can be in Python or Bash, but note that it must set an boolean ENV variable of similar that the main Python script can access to know if the device is connected to the internet or not.
- Display some ASCII art (we'll provide it) and a % done thing at boot.
### Contributions ro the Python script(s) 
These are welcome, but currently we do not accept the following changes:
- Changes that won't be of use to users and do not solve any bugs.
- Changes to the package manager -- of course, bugs and syntax improvements are welcome.
- Changes to the shell scripts -- if you want to do that, read 'Contibuting Bash Apps' below.
### Contributing Bash Apps
Have an app idea? You can code it in Python or Bash. Keep in mind that you may not be able to see your app in action until we finish the kernel if you code it in Bash. We welcome:
- Games (if you can even make one in Bash)
- Utilities (anything, really)
- Custom package manager (Note: ALL the packages must be provided via a link or files for review. We'll then upload the files to our CDN and you'll (or we'll) create a custom command for pulling the packages.
