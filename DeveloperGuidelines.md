# Introduction #

This page details the rules that need to be followed when contributing code or documentation to the Neatx project.

The first requirement is that either your and/or your employer needs to sign the [individual](http://code.google.com/legal/individual-cla-v1.0.html) or [corporate](http://code.google.com/legal/corporate-cla-v1.0.html) contributor license agreement. Which one is needed depends on your particular case.

Only project members have commit rights to the repository. In order to become a project member, you need to do significant contributions first. Also, you need to have a [Gmail](http://www.gmail.com/) account. Since the code.google.com project hosting site has the same rights for both wiki and code, we cannot give write rights only to the wiki, therefore all contributors must go through the same join process.

# Code #

All code **must** be sent to the [neatx@googlegroups.com](http://groups.google.com/group/neatx) mailing list for review first. After you get a positive review, usually indicated by a _LGTM_ response, you can commit your changes (if you have the appropriate rights) or a member of the project will do it for you.

## Source tree organization ##

Development of new features for the next version (`X.Y`) goes on in `/trunk/neatx`. Bug fixing and backporting on existing versions goes on in branches, `/branches/neatx/neatx-X.Y`.

Every released tarball has to be made from a tag (`/tags/neatx/neatx-X.Y.Z`) using `make distcheck`. More information on how to build releases can be found in [doc/DEVNOTES](http://neatx.googlecode.com/svn/trunk/neatx/doc/DEVNOTES).

# Committing changes #

Once you got a positive confirmation for your patch, it can be committed to trunk. The commit message **must** contain a line starting with `Reviewed-by:` and the usernames of the people who reviewed it. If the patch is a bugfix it may need backporting to older branches.

# Wiki updates #

Wikis can be updated by members directly. Unfortunately, non-members need to send their wanted changes to the mailing list.