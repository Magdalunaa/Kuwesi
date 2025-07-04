1. set up keyd and make it handle your keyboard layout. ```man keyd``` explains how to do this
2. move ```kuwesi``` somewhere inside ```/etc/keyd/```
3. include ```kuwesi``` in your keyd config
4. set up keybinds for switching to kuwesi and another layout (or just use kuwesi eternally?)

 the kuwesi file includes four layouts: ```kuwesi```, ```kuwesi-anglemod```, ```kuwesi-altpunct``` and ```kuwesi-combined``` (angle mod + alt punctuation). 
 the latter two need keyd unicode input to be set up and may not work in all programs
