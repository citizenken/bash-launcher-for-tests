![alt tag](./blt.png)

Bash Launcher for Tests (BLT)
==================
BLT is a cross-environment test execution platform. Written purely in Bash, BLT works with Windows (via Gitbash or Cygwin), OSX, and Linux.

BLT is an application that establishes an environment in which a test script is executed. Test scripts are comprised of a series of modules, which can be used or not depending on a user's specifications. Such modules include Git functionality, test execution on remote machines, and Reviewboard integration for the posting of test results.

Installation
==================
To install, clone this repo into a temporary directory and execute the following command:
`./install_blt`

This will copy the BLT script to /bin, and will establish a local location for the BLT repository. BLT will update itself automatically, thereby negating the need for Git version control.

After installation, the cloned repository will be deleted.
