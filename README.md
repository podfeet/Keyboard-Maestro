# Keyboard-Maestro
I'm a fan of Keyboard Maestro, but if you bork a macro, you have to figure out how to get it back to it's working state. I wanted a way to have version control. The problem is that Keyboard Maestro is one giant xml file.

Dan Thomas created a macro for Keyboard Maestro that separates your macro groups into folders, and creates individual macros in those group folders that you can then see as separate xml files. This means you can then use git to do version control.

Dan's macro: [github.com/dagware/DanThomas/](https://github.com/dagware/DanThomas/blob/master/MacroRepository/MacroRepository.md)

I was inspired to do it by Rob Griffith's explanation on [robservatory.com/...](https://robservatory.com/archiving-and-version-control-for-keyboard-maestro/)
