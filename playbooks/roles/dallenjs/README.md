dallenjs
=========

Creates the environment for the DallenJS repo to run. To be exact, it:
- installs git, nginx, mysql, and nvm
- installs node version 10 lts
- installs all the npm packages for dallenjs server and client
- builds the dallenjs client
- configures nginx to serve the client
- configures the secrets and configs for dallenjs server
- sets up the database so dallenjs server can use it
- creates the service for dallenjs server to be easily started
