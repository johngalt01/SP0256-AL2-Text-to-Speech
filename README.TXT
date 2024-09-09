This is a Text to Speech converter for the SP0256-AL2 speech chip.
It is very Alpha and I'm sure contains bugs and mistakes.

Designed for the Altair-Duino I/O Bus speech processor card.
64kb required. Best use on a Harddrive but will work off Floppy Disk if you have the Disk Controller card.
CP/M 2.2. serial port 127

SAY.COM is the main program you run and enter either a word or a line of text to convert.

The converted phonics are saved in TEXTTEMP.TXT then output through READSAY.COM

READSAY.COM Will read converted phonics text inside the TEXTTEMP.TXT file

TEXTTEMP.TXT is a temp file that is erased and recreated when SAY.COM is run.

you can copy TEXTTEMP.TXT to another file and save the contents which you can use inside of 
your own program where you want to use speech or you can replay them through READSAY.COM in the future
by copying the file name back to TEXTTEMP.TXT

the rest of the included files in the LIBRARY Archive are needed to support SAY. 
BRUN is needed to run all the programs.

READTEXT will play any saved Text to Speech converted file. you can even include Escape code effects.

Update: 08/20/2024
