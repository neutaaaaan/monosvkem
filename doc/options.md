If your terminal emulator doesn't support italic characters, or you wish to 
disable them, add `let g:Monosvkem = 1` to your .vimrc.  
Vim can be a bit finnicky, so if it doesn't work out of the box, try loading
the colourscheme *after* disabling italics. 


Having function definitions highlighted works for me, it might work for you.
If you want them to be purple, add `let g:Monosvkem_enable_func_defs = 1` to 
your .vimrc.  
Support is *terrible* as I have to add every exception by hand.  
Pull requests are welcome, even if you're using a custom syntax file, plugin, or 
distribution.  
A mention of the stack you're using, a before/after screenshot and a pinky
promise of having made sure that your changes don't break something that used to
work before are all I require.

