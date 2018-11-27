# vagrant_a

### Purpose of the repository 
- The repository uses Ubuntu-xenial64 box already uploaded in `vagrant` cloud and sets the hostname to "bananas3".

#### List of files in the repository

File name                            | File description 
------------------------------------ | --------------------------------------------------------------
`Vagrantfile` | file with sript that defines machine and software requirements and sets the name of the box to "bananas3".
`scripts/provision.sh` | script that installs `nginx`

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
- Check if hostname is "bananas3".
- Check if `nginx` is installed.
- Check if IP is 192.168.56.56.
- Check if port forwarding is set up.
