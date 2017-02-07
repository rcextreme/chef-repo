# chef-repo

This is the Chef-repo I maintain for my learning exercises.  It's very plain.
To use it just clone it to your workstation.  Then you can run the Cookbooks using chef-client local-mode or load the Cookbooks to a Chef server.

These are the chef.io Tutorials I followed to learn Chef:

<h1>https://learn.chef.io/tutorials/learn-the-basics/</h1>

<p>choose your server environment - Ubuntu 14.04</p>
<p>choose your operating environment - Vagrant and Virtual Box</p>
<ol>Set up a virtual machine to manage (With Vagrant and Virtual Box)</ol>
<li> Ensure your workstation (Windows laptop in this case) supports Virtualization<li>
2. Install the Chef DK on your Windows Workstation (this includes a git and a ssh client)
3. Install Oracle's VirtualBox
4. Install Hashicorp's Vagrant
5. Download an Ubuntu 14.04 VM image onto Vagrant:  
     $vagrant box add bento/ubuntu-14.04 --provider=virtualbox
6. Bring up an Ubuntu instance in Virtual Box using Vagrant and its image: 
     $vagrant init bento/ubuntu-14.04   (this generates the Vagrantfile)
     $vagrant up 
7. Connect to your Ubuntu instance
     $vagrant ssh
8. Install ChefDK on your Ubuntu instance
Configure a resource
1. Set up your working directory
   $ mkdir ~/chef-repo
2. Create an /tmp/MOTD file using Chef's file resource
3. Run chef-client in local mode a second time to display how chef maintains the file
4. Delete the /tmp/MOTD file using a second Chef file resource with the 'delete' action
Configure a package an service


https://learn.chef.io/tutorials/manage-a-node/

https://learn.chef.io/tutorials/local-development/   ( aka get started with Test Kitchen )

https://learn.chef.io/manage-a-web-app/

https://learn.chef.io/tutorials/inspec/

https://learn.chef.io/tutorials/chefspec/

https://learn.chef.io/tutorials/verify-style/

https://learn.chef.io/automate/

https://learn.chef.io/tutorials/compliance-assess/

https://learn.chef.io/tutorials/compliance-remediate/

https://learn.chef.io/skills/beyond-essentials-1/ what happens during knife bootstrap

https://learn.chef.io/skills/beyond-essentials-2/ what happens during a chef client run

https://learn.chef.io/skills/beyond-essentials-3/ what is the security model used by chef

