## Upgrading Kubuntu (from 23 to 24)

I tend to be very careful about these things, I've been using computers long enough to remember a tine when system upgrades were rarely enjoyable.
But I'm also a software developer, outdated dependencies make me uncomfortable.<br/>
<br/>
So I took a deep breath and pushed the button. And nothing, except an empty error dialog. It's not like I'm the only person who experienced the problem, the answer was a quick Google search away. It turned out I had to run `sudo apt full-upgrade -y' first, then the upgrade-thingamob would happily chug along as if nothing had just happened.<br/>
<br/>
But it kept throwing mean looking dialogs at me about this and that, the kind of information that would have made a nice summary screen at the end of the installation. And the progress bar had seemingly little or no relation to the actual progress most of the time. Speaking of which, now it's asking if I want to remove obsolete packages, 259 of them to be exact, which I'm warned might take several hours. It thankfully didn't, it took about a minute and the progress bar actually worked this time. And we're done, the machine even survived a reboot without incidents.<br/>
<br/>
I mean, I'm grateful and sort of surprised free software managed to get this far, this fast; it's a crazy amount of complexity to deal with. Even Apple under Steve Jobs struggled to make these kinds of system upgrades seemless, not to mention Windows. So that's not what this is about at all.<br/>
<br/>.
And I could theoretically get involved and try to fix these issues myself, but I would rather channel that energy into getting other people excited about the idea. Bacause it's not rocket science from here, this is almost good enough. Just a tiny bit more empthy for the user and determination to make it seemless would make it perfact.<br/>
<br/>
Thank you!<br/>