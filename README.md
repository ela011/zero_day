We review topics such as:

Vagrant:

What is a zero-day? The term "zero day" refers to a newly discovered software vulnerability and not patched yet, it's the time since it is found until it is "fixed." If hackers manage to exploit that security hole at that time, that is known as a zero-day attack.

What is a virtual machine? What is Vagrant? VM is a version control box and environments, Vagrant do this, like a VirtualBox but better haha. Think about it! Vagrant starting a Ubuntu virtual machine using vagrant up

Who wrote Vagrant? Original author: Mitchell Hashimoto. Developers: HashiCorp (Mitchell Hashimoto and John Bender)

Use Vagrant:

Install VirtualBox: Download VirtualBox from this link
Install Vagrant: Download Vagrant from this link
Open the command prompt
Add the Ubuntu 14.04 (Trusty) image to your box list:
C:\dir> vagrant box add ubuntu/trusty64
C:\dir> vagrant init ubuntu/trusty64
C:\dir> vagrant up
C:\dir> vagrant ssh
