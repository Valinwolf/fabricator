I don't know about anyone else out there, but I'm lazy and I like Construct. This repository is for a control script that will install/update, start, stop, restart, reset your Construct server. Note this script is designed with ***Fedora*** in mind.

## Installation
1. git clone https://github.com/Valinwolf/fabricator.git
2. ./install

## Usage
#### Implemented Commands
`start` _takes 0 arguments_
>Start the Construct daemon

 

`stop` _takes 0 arguments_
>Stop the Construct daemon

 

`restart` _takes 0 arguments_
>Restarts the Construct daemon if it is running or starts it if it is not

 

`update` or _takes 0 or 1 arguments_
>Updates or installs the Construct daemon
>
>_**Note:** When installing for the first time, use `install` so it installs the dependencies too._

 - _arg1: \[Optional] If included, the value must be `--debug` and will enable a debug build_

 

`install` _takes 0 or 1 arguments_
>Installs the Construct daemon and all it's dependencies

 - _arg1: \[Optional] If included, the value must be `--debug` and will enable a debug build_

 

`reset` _takes 0 arguments_
>Wipes all server config

 

`set` _takes 2 arguments_
>Sets a variable important to the install, update, or launching of Construct

 - _arg1: Name of the variable to be changed_
 - _arg2: Value to change the variable to_
