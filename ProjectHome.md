# What is Neatx #

Neatx is an Open Source NX server, similar to the commercial NX server from [NoMachine](http://www.nomachine.com/). If you're not familiar with NX, these links might help:

  * [NoMachine's “Getting Started With NX”](http://www.nomachine.com/documents/getting-started.php)
  * [NoMachine's “Introduction to NX technology”](http://www.nomachine.com/documents/intr-technology.php)
  * [Wikipedia article on NX technology](http://en.wikipedia.org/wiki/NX_technology)

# History #
Neatx was developed by Google for an _internal project_. That _project is now finished_, and the source was released for the community to use/develop/benefit from. **There is no active development at this time**.

<a href='Hidden comment: 
A couple of Google employees are doing sporadic releases and maintenance in their spare time.
'></a>

# What Works #

  * Session creation
  * Session suspension
  * Session resumption
  * Session shutdown
  * Gnome/KDE/Application/Console sessions
  * Floating Window/Virtual Desktop sessions
  * Fullscreen/Resolution/Keyboard preferences
  * Session shadowing (though only sessions belonging to you)

# What Doesn't Work #

  * Terminating a session from the session list
  * Windows/VNC sessions
  * Sound, printer tunneling, Samba tunneling
  * [Local session sharing](http://www.nomachine.com/fr/view.php?id=FR10C01069)
  * Load balancing

# Mailing list #

You can use [neatx@googlegroups.com](http://groups.google.com/group/neatx) for both user discussions and development questions.

# Getting Neatx #
<a href='Hidden comment: 
At the moment, we"re not doing releases as we"re constantly fixing small things as people try out the codebase. In the meantime, the best way to get neatx is to [http://code.google.com/p/neatx/source/checkout check it out from svn].
'></a>
There are no releases. Please use the [code from our Subversion repository](http://code.google.com/p/neatx/source/checkout).