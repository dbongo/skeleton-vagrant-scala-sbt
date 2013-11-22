Skeleton - Vagrant + Ansible + Scala + SBT
===

This is another installment in my multi-part series of project skeletons.  This one sets you up for a generic Vagrant + Ansible development environment for a Scala project.  It includes:

* An amazing Vagrantfile that will cue up Anisble for devops goodness and get you Scala and SBT installed for you
* An Ansible inventory file that works with a stock Vagrant set up
* A vagrant.yaml file that contains the tasks you want to execute on vagrant up

Notes:

1. This is set up for a basic Scala project on Ubuntu with a base box name "precise64"
2. If you clone this, you have to go in and make a lot of changes to build.sbt.  You can also use g8 with BTBurke/sbt.g8 to set up a new build.sbt with your info.
3. Technical Details:
 - Installs Oracle Java 7
 - Installs Scala 2.10.3 and SBT 0.13.0 (you can change this by specifying other version numbers in the vars section at the top of vagrant.yaml)

See others in the series!

* For you frontend people - [Skeleton-Angular-D3-Bootstrap-Yeoman](https://github.com/BTBurke/skeleton-angular-d3-bootstrap-yeoman) with CoffeeScript and a bunch of other whizbang excitement

* For Pythonistas - [Skeleton-Vagrant-Ansible](https://github.com/BTBurke/skeleton-vagrant-ansible)

