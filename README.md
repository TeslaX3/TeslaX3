TeslaX3 - a fork of Litecoin version with fast block time and faster confirmations (2 confirmations needed instead of 6). Like Litecoin it uses scrypt as a proof of work scheme.

	- 30 minute block target
	- Difficulty retargets every 2 minutes
	- Total coins will be around 17.5 million. 
	- Each block will have 33 coins per block then decrease 10% per month for the first 2 years. After 2 years block reward will then decrease by 10% every few years
	- The default ports are 1943 (connect) and 1856 (json rpc).


Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of TeslaX3.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 
