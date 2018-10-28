# Common Technical Questions With Answers

## Installfest

### I don't have Windows, Linux, or a Mac. How do I install things?

* Another option is Cloud9, which, as the name suggests, is an
  environment that runs on the cloud. With Cloud9 you don't have
  to install anything!

### I can't open the `.box` file!

* That's ok! You're not supposed to. Make sure it is in the right
  directory, though.

### Why can't I get Vagrant to work?

* Is the `.box` file in the correct folder?
* Are you in the correct directory? Try typing `pwd`.
* It's sometimes hard to tell if Vagrant is working. You might actually be in
  it already! If your console has colors, and the prompt will be `RailsBridge-VM:/vagrant$`

### I got and error that says `No usable default provider could be found for your system.` when trying to run `vagrant up`
* Make sure you installed Vagrant/Virtual box. You may have ejected them by mistake
  if you do already have them installed.

## Saturday Workshop

### I tried running my server but it isn't working!

* Check to see if you are in Vagrant.
* Type `pwd` to make sure you are in the right directory.
* Check if you are in the console.
* Check to see if a server is already running.

### Why isn't the console working?

* Check to see if you're in the console and not the server or in a Bash shell.
* Check to see if you're in Vagrant.
* Check to see if you're in the correct directory.

Common errors occur with typos, including putting extra spaces when typing
commands into the console.
