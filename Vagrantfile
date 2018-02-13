Vagrant.configure("2") do |config|
	 config.vm.define "box1" do |box1|

         box1.vm.box="ubuntu/trusty64"

         box1.vm.network :forwarded_port, guest: 22, host: 10122, id: "ssh"

 end

  config.vm.define "box2" do |box2|

         box2.vm.box="scotch/box"

         box2.vm.network :forwarded_port, guest: 22, host: 10222, id: "ssh"
 end
end

#!/bin/bash

# Script to add a user to Linux system

if [ $(id -u) -eq 0 ]; then

read -p "Enter username : " username

read -s -p "Enter password : " password

egrep "^$username" /etc/passwd >/dev/null

if [ $? -eq 0 ]; then

echo "$username exists!"

exit 1

else

#This is another edit! Mwahahaha!!!
#This is Svetlana's change!

#Kyle, the user script needs to be changed. You are missing a block for 'else' statement.  Fix it ASAP (just kidding:) Hopefully you can see my comments.
