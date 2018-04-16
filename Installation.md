## Installation

Copy this boilerplate in your home folder to use it with ease.

- __`$ git clone git@github.com:CodeDotJS/commandline-boilerplate.git`__

Now delete the useless files and folders to avoid cloning the boilerplate repository everytime you are developing something.

- __`$ cd commandline-boilerplate && sudo rm -rf .git && rm -r Installation.md`__

Create an empty repository on GitHub and clone it.

- __`$ git clone git@github.com:userName/dummyrepo.git`__

- __`$ cd dummyrepo`__

Now, copy the content of boilerplate to the cloned repository.

- __`$ cp -a ~/commandline-boilerplate/. .`__

There are two dots in the end, the __`.`__ at end of the __`commandline-boilerplate/`__ is a specific cp syntax that allow to copy all files and folders, included hidden ones. The second __`.`__ keeps the copied content in the current directory, here it's __`dummyrepo`__
