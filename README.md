km-automate-web-database
========================

This macro is a companion to the the article I wrote at [TUAW] about how I use  Keyboard Maestro 6 to automate a web database.

### Step 1:  Create a "Safari Only" group in Keyboard Maestro ###

The first step is creating a "Group" in Keyboard Maestro which is ***only active in Safari***. That way I don't have to worry about this keyboard shortcut conflicting with any other keyboard shortcuts in any other apps.

![](https://raw.github.com/tjluoma/km-automate-web-database/master/Keyboard-Maestro-only-in-Safari.jpg)

Note that all of the macros in the red "brackets" will *only* be active in Safari.

### Step Two: 

Import the [Automate-Web-Database.kmmacros] file.

This will replicate the macro that I describe in my TUAW article.

Note that I do not expect that many people will be able to use this macro directly, it is intended to serve as an example to show people how they can put one together so they can either modify it to suit their needs or create their own using this as 'inspiration.'

Once you have the macro installed in Keyboard Maestro, you should be able to follow the steps to understand what it does. I have tried to add extra commentary where necessary.

[Automate-Web-Database.kmmacros]: Automate-Web-Database.kmmacros





[TUAW]: http://www.tuaw.com/2013/07/18/using-keyboard-maestro-6-to-automate-a-web-database/
