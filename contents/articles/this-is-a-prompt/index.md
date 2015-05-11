---
title: This is a prompt
author: smithamax
date: 2014-05-25
license: cc-by-sa
template: article.jade
---
This is a command prompt

	$

You can get to it from your Mac by opening the `Terminal` Application

Your prompt might look something like this

	[bobs-macbook:~] bob%

This is the OS X default prompt, it shows some information about the current state and then a `%` as the prompt character, kind of like punctuation. 

However traditionally we use `$` to signify a user prompt and `#` to signify a 'root' user prompt.

For now let it be known that when I right `$` I am indicating a prompt.

## Moving on.

Lets learn our first command. Type `pwd` then &lt;return&gt;

	$ pwd
	/Users/dom
	$

Notice how that `/Users/dom` was printed out and then we where once again prompted with our command prompt.

> The **pwd** utility writes the absolute pathname of the current working directory to the standard output.

In other words when we're using the terminal (or more technically a unix shell) we have a directory what we're in when we execute commands (like `pwd`). These are the same directories (or folders) you're used to in Finder. To see this we can open the current working directory in finder like so.

    $ open .

Your home directory should open in Finder. `.` is shorthand for the current working directory but we could also have opened `/Users/dom` for the same result.

To navigate between directories and list there content we can use the `cd` and `ls` commands

	$ ls
	Desktop
	Documents
	Downloads
	Music
	Pictures
	Public
	
	$ cd Music
	
	$ pwd
	/Users/dom/Music
	
	$ ls
	iTunes
	