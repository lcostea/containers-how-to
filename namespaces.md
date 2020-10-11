Check the current machine hostname:

`hostname`

Start a process without sharing the `uts` namespace:

`sudo unshare --uts sh`

Check the hostname on the new process:

`hostname`

Lets modify it

`hostname liviu-costea`

And lets see it again. Also run this on another terminal, so you can see the old one.

`hostname`

Then exit and run hostname again to see it actually didn't change

`exit`
`hostname`
