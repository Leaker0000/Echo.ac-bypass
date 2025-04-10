Hey,

Echo.ac and similar tools check if certain .exe files (based on their hashes) have ever run on your system. They do this by reading your Prefetch folder, where Windows keeps track of executed applications. Normally, this can be done without any extra software.

However, Echo.ac uses an external program to collect this data and send it to their servers. Based on that info, they decide whether cheats have been used or not. I took a closer look at the tool they use – and here’s the funny part: it’s actually a public tool from GitHub, and they didn’t even bother to modify it. No changes, no credits, nothing – super lazy and obvious.

This tool runs under the name ntfsDump.exe and stays active in the background. So if you’re using a detected cheat and want to avoid it showing up in Echo’s scan, you could literally just rename your cheat to ntfsDump.exe – yeah, it really works (pretty hilarious).

If that’s not your thing, just make sure to close the Echo scan tool while it’s running. You can also find the original source code of the program they’re using below.

Nice try, joshe – maybe next time do your homework.

