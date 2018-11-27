# vagrant_a

### Purpose of the repository 
- The repository uses Ubuntu-xenial64 box already uploaded in `vagrant` cloud and sets the hostname to "bananas3".

#### List of files in the repository

File name                            | File description 
------------------------------------ | --------------------------------------------------------------
`Vagrantfile` | file with sript that sets the name of the Ubuntu-xenial box to "bananas3".


### How to use this repository. 
- Install `virtualbox` by following this [instructions](https://www.virtualbox.org/wiki/Downloads).
- Install `vagrant` by following this [instructions](https://www.vagrantup.com/docs/installation/).
- Clone the repository to your local computer: `git clone git@github.com:nikcbg/vagrant_a.git`.
- Go to the cloned repo on your computer: `cd vagrant_a`.
- After that execute the commands in the table below.

Command execution                    | Command outcome
------------------------------------ | --------------------------------------------------------------
`vagrant up` | to power up the xenial VM.
`vagrant ssh` | to log in to the xenial VM.


### TO DO:
- Check if hostname is "bananas3"
