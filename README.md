# H2EKStringDump
String lists for use with the H2EK

The process for adding or modifying strings in the H2EK is slightly different to how it is done with the H3EK.

* First, you will need to have the data files for all of the strings you want to have in your map, even the ones you don't intend to modify.  
* Once you have these text files, make your modifcations or additions and use the [new-strings](https://c20.reclaimers.net/h2/tools/h2-ek/h2-tool/#new-strings) tool command to create the tag files.  
* Next you will need to update the .str files found in h2_fonts. You can do this by using the [pack-unicode-strings](https://c20.reclaimers.net/h2/tools/h2-ek/h2-tool/#pack-unicode-strings) tool command with the strings_list.txt file included with this repository. If you have made a completely new string file, you will need to add it to this text file.
* With these steps done you can now copy your strings.str files from the h2_fonts folder in your H2EK directory to your MCC folder's h2_fonts folder. Together with your packaged map file this will allow any strings you have made or modified to display in-game.
