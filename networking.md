Networking
==========

The networking protocol uses [NetSockets](https://netsockets.codeplex.com/) to communicate.
If you do not wish to use NS, you must reimplement it for the platform you are using.
We use NS because it is simple to code in. We don't know about the portability, but it should run on mono.
Check [Toaster](https://github.com/leetnet/Toaster) and [Octowaffle](https://github.com/leetnet/Octowaffle) projects to find out more about how you can implement it, while we create this document.

The default port is 13370.
