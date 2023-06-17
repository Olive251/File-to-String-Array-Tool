# fileToStrArray

I was constantly needing to do this so I thought I'd practice some of Python text-editing and made this tool. Not sure if anyone else is going to have need for this but I hope someone else can find it useful!

To use this tool you can use chmod to make it executable, otherwise you'll need to use py/python3 commands to run
> example:  py fileToStrArray file.txt

I made this tool mostly out of frustration with a weird amount of large text blocks I've needed to turn into string arrays over the last few months.

The script will by default copy the text onto the clipboard, but it can also write the array to a new file as well

> py fileToStrArray file.txt -f

The above would copy the text to the clipboard and create a new file called "file_asArray.txt"
