dallenjs
=========

Creates the environment for the a new minecraft server to be run. To be exact, it:
- installs git, java, and screen
- downloads the lates build tools jar from spigot
- compiles the given version of spigot (or pulls it from cache if already built)
- creates a new folder for the server with properties, eula signed, and start script


Designed to be run under a user account, so the user can be easily specified in the vars