Flynt
Dynamically building CodeIgniter.



About


The main goals of the Flynt project are to create a dynamic environment on the command line that allows a user to quickly and easily build or modify an existing CodeIgniter framework, and have no dependencies other than CodeIgniter and the ability to use it. It is important to know that the project is comprised entirely of free and open source software, released under the GPLv3 Licence.

CodeIgniter is an open source, object-oriented PHP framework that aims to be light and powerful; making the most out of any systems resources to make web applications run smoothly. Flynt uses the newest releases of CodeIgniter, which can be found at the official website: http://www.codeigniter.com/.


Installation


There are multiple ways to install and use Flynt depending on the system you are currently using. 



Using Flynt


Using Flynt is as simple as opening your preferred terminal and inputting:

 $~ flynt 

This will bring you to the Flynt Prompt, where from here on out all commands will be executed, with the syntax of:

 *flynt ~ {command} {intent} {arguments} 

If you have an empty directory that you would like to build a brand new CodeIgniter instance in, you would run:

 *flynt ~ new CI ./new_dir 

Where ‘new’ is the command that initiates file writing, ‘CI’ is the intent, in this case we are creating a new CodeIgniter instance, and ‘./new_dir’ is the argument for the command, in this case the name of the directory to perform the creation of the new instance relative to the directory that Flynt was originally run from.

