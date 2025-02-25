# Welcome
The Screen Reader Package is a set of files meant to be used in conjunction with a screen reader, for the Pokeymanz Tabletop RPG.

It contains the following elements:
* A screen-reader friendly trainer sheet
* A screen-reader friendly editable PokePC sheet
* A custom dictionary for the screen reader's voicebank

## Trainer Sheet 
The consists of a **Trainer Sheet** (a .odt file), a **Pokemon Template** (a .odt file), and a **PC Box folder**. When statting out a new Pokemon, make a copy of the Pokemon Sheet Template, fill it out with the necessary info, and then put it the PC box folder. Repeat this process for any new Pokemon your trainer obtains along the way.

## Pokemon PC Sheet
Much like the Trainer sheet, the PokePC file consists of the **PokePC Sheet** and the **Partner Sheet**, both as .odt files. The Partner Sheet is only necessary for Pokemon PCs with the *Partner* edge, and can otherwise be ignored.

## Custom Dictionary
Since proper nouns aren't supported in a default voicebank, a custom pronunciation dictionary is used to allow screen readers to correctly process aspects such as Pokemon names and acronyms.

To install it, copy the default.dic file to `%AppData%\Roaming\nvda\speechDicts`, overwriting the existing dictionary if prompted

Note - if you have an existing custom dictionary, you should instead copy the contents of "default.dic" and append it to the file of the same name in the SpeechDicts folder instead

## Contributions
Currently, this project only has native support for the `NVDA` screen reader. If you have able and willing to add support for additional screen readers, feel free to submit a pull request on the github repository here: 

https://github.com/ftc0102/Pokeymanz-screen-reader-package/pulls
