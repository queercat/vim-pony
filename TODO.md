# TODO;
---
the current approach that seems best is to use a custom font and add the proper pony glyph to
write the unicode of that to the status line.

✅: look at how to get fonts setup for WSL  
	- looks like something to do with: [powerline fonts](https://slmeng.medium.com/how-to-install-powerline-fonts-in-windows-b2eedecace58)  
✅: patch those fonts with font forge  
	- figure out how to create font with that  
❌: set that font in linux  
❌: do the unicode in the vim statusline  
	- potential for animation with multiple glyphs?  

# Current Status
---
My approach of doing this is through WSL. Windows has a unique custom font found in Windows/Fonts/segoeuimj.ttf. This needs to be modified to include our glyph.'
