# vim
vim, Linux text editor  

**Created**: *Sat 190823 05:03 PM GMT*  
**Updated**: *Sat 190823 05:03 PM GMT*  

-----

## Vim, history

Vim, is a version of the previous Vi editor/only IMproved; hence, the name Vim.  

Vi, means Vi-sual.  

**NOTE**: When you type in: vi...what, acutally, loads is: Vim.  

-----

## Vim, Linux text editor  

In order to launch Vim text editor inside of Linux...; then, simply, type:  

> vim  

...and, the Vim text editor enviroment will, now, open.  

At first, you will find yourself being stuck in 'command mode'...;      
-(which can be very highly confusing to people who are beginners...?!)-  
where you will NOT be able to enter any text.  

In order to enter text type:  

>i  

...which, now, puts you in 'insert mode'; where you can begin typing in keyboard characters.       

File navigation is done by...  
Pressing the [Enter] key will take you to the next line downwards.       
Pressing one of the arrow keys...will take you either:      
left/right/up/down  
...where you can continue editing the file from that specifically chosen point.    

When you are finished typing in...; and, wish to save the file you have typed in...;     
then, press the [ESC] key...; this will put you back into 'command mode'.  

>:wq fileName  

...will both (w)rite the file/and, also, (q)uit from out of the editor/as well as, specifying a fileName to write.    

-----

You can also open Vim text editor by specifying a fileName:  

>vim fileName

...if the file already exists; then, that file will open ready for futher editing.    
If the file does NOT already exist; then, that file will be newly created.    
After editing the file...; and, you wish to quit using Vim...just use:  

>:wq  

...which will both (w)rite to the file/and, also, (q)uit Vim...; returning you back to the command prompt.  

-----

If you wish to 'overwrite' a file that already exists...; then, use:  

>:wq! fileName  

...and, the specified fileName contents will be overwritten.  

-----

If you are editing a file...; and, then, do change your mind...;  
not wishing to save anything that you have typed in...; then, use:  

>q!  

...this (q)uits Vim; and, returns you straight back to your usual command prompt...without saving.   

-----

## Links

### YouTube

What Vim Is and Why You Should Learn It - (Channel: Linux Training Academy)  
- https://www.youtube.com/watch?v=CM7UP-un1vc&t=59s  

Vim Tutorial for Beginners - (Channel: freeCodeCame.org)  
- https://www.youtube.com/watch?v=RZ4p-saaQkc  


