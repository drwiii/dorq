------------------------------------------------------------------

        oooooooooo.                ooooooooo.
        `888'   `Y8b    .oooooo.   `888   `Y88.   .oooooo.
         888      888  d8P'  `Y8b   888   .d88'  d8P'  `Y8b
         888      888 888      888  888ooo88P'  888      888
         888      888 888      888  888`88b.    888     .888
         888     d88' `88b    d88'  888  `88b.  `88b   `888b
        o888bood8P'    `Y8bood8P'  o888o  o888o  `Y8bood8P'Yb

------------------------------------------------------------------

INTRODUCTION

This is a convenience script for the ircII EPIC v3 and v4 chat clients.

If you are used to doing things the default greyscale way in ircII, this 
script allows you to take control of advanced features to have a more 
understandable experience.

It was started in the mid-1990s by StRoBe (Douglas Winslow), who was a 
regular user and eventual channel operator of the popular Undernet IRC 
channel #chatzone.  He would go on to become a user and network operator
of SlashNET, the IRC network of Slashdot.


NECESSITY

One day, when the up-and-coming mIRC chat client added us as a default 
IRC channel, there became hundreds of users online in our channel at any 
time.  The problem being that many saw the size of this formerly happy 
channel as a target of trolling, crapflooding, ping floods, and attacks.

This was not easy to deal with when most of us only had a text-mode UNIX 
IRC client, and the few operators who used mIRC were not online when 
necessary.

An existing over-engineered script called PhoEniX was rewritten from the 
ground-up to form DoRq.  Most of that script's complaints were addressed 
in this rewrite.  A helpful clonebot detection script from a friend was 
added.  Command compatibility allowed people to upgrade without having 
to relearn many commands.


INSPIRATION

If you have seen the notification shade on modern systems such as 
Android, ircII DoRq used a feature of EPIC known as a second status bar, 
and did some creative work and timing to add a status notifier area on 
the righthand side of the screen.

The script in its latest December 1997 revision would feature a 
groundbreaking innovation in client/server scripting called RML (the 
Run-time Markup Language).  This very resource-light 'not-quite-HTML' 
code allowed users to create simple and colorful active documents which 
would be shown in a user's IRC (chat) client.

The inspiration for starting RML's design was the realization that 
online systems such as QuantumLink, Prodigy, and America Online, as well 
as internet gopher and teletext all had qualities which could be made 
with the advanced scripting architecture that ircII EPIC provided.

This was an ideal solution for a script which was already becoming known 
as the color-coded, sound-filled, and easy way to chat with Linux or 
UNIX.  Channel operators of high-volume properties could depend on 
having an on-line help system accessible via easy-to-remember commands 
to review the exact command they needed to take care of necessities.


FUTURE BOUND

RML is an active language, in that it also allows scripting extensions.  
If you are used to utilizing the App Stores of today, you should know 
that in this fledgling system of many years ago, new software and 
updates could be downloaded via an online remote repository much like 
the filebase services of the dial-in online systems mentioned.

 * RMLI Help

	This module allowed the help menus to be stored on a remote
	server so they could be updated with new material. The main
	reason for this, however, is that the size of scripts was of
	concern to some.  The non RMLI version of the script has the
	help file built in.

 * RMLI File

	ircII is a text-based event driven system, so this module
	allowed a user to download uuencoded files from the server.
	This was so new themes with sounds and more script modules
	could be bootstrapped onto the client-side on the user's
	terms.

 * RMLI Headliner

	This filled an array with headlines.  Built in sources are
	news and weather.  An innovative timestamp command allowed
	the client to receive an audio notification when new headlines
	were downloaded.  The server side of this sourced Reuters
	headlines from Yahoo! and weather from the NWS, and it did
	this using an ircII script made to operate in non-server mode.

 * ircII EPIC CDROM

	The scripting code was extended to interface with the Linux
	command line CD player to read TOC information, which then
	pulled music tracklists from the internet CDDB.  The user
	can control their CD player from the ircII EPIC client, with
	the tracklist integrated into the notification and status
	areas as appropriate.
	(This module is separate from the others, and it detects how
	to present itself outside of the DoRq environment.)

In 2018, after a hiatus of twenty years, RML was dusted off and extended 
to support typefaces, positioning, and graphics, and it is compatible 
with software on the PC, Android devices, and Raspberry Pi.


SUMMARY

IRC was the first client/server protocol I learned, and ircII EPIC was 
the first scripting language I can remember utilizing in a software 
release.  If it were not for dropping out of school and reading 
printouts of RFC1459 and PhoEniX, I would not have enjoyed Linux as much 
as I did.
