---
layout: default
---

Side note: I've been connecting back with my early loves of technology. Expect to see more on Linux, LISP, hacker ethic type stuff. If you haven't, for some reason, read anything by [Paul Graham](http://paulgraham.com), start with [Hackers and Painters](http://paulgraham.com/hackpaint.html).



## MacOS

	 pbpaste | cat -n | sort -nr | awk '{print $2}' | pbcopy

## Linux

	xclip -o | cat -n | sort -nr | awk '{print $2}' | xclip -i

