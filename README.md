
# ![GitHub Logo](/images/pitchi-banner.png)

## What is Pitchi?
Pitchi aids in learning the pitch accent patterns in Japanese. It functions much like a dictionary, letting you search through a list of words using the kanji/hiragana/katana, romaji, or translation. The word is then shown in its written form, with the romaji beneath it. Below that, the words pitch accent pattern is drawn with each of the words mora beneath their corresponding pitch accent pattern point. At the bottom, any notes added in for the word are displayed.

## How Do You Make a List For Pitchi?
There are two ways of creating list files for Pitchi. The most straight forward way is to use the built in interface to add words into the currently active list. This menu can be brought up by click the "Add Word" button up at the top right. The only fields that are required are the word itself and its hiragana/katakana. All other fields are optional for adding the forward. However, with no further information, the words romaji, translation, pitch accent patterns, and usage notes will not be displayed. It is heavily reccommended that all fields be filled out when adding new words. It is also important to note that when adding words through this method, the word will be added into whatever list you currently have open (the master list is opened by default).

The other method of creating list files is through INI file creation. Pitchi stopped using the INI file format for lists starting at version 0.4. Since then, the HDF5 format is being used. These files are a little less comfortable to create, so you are also able to convert list files from the INI format to HDF5 through the settings menu. Our GitHub page has a breakdown on how to create these lists in the INI format and a brief introduction into what INI files are for those are inexperienced with them. Converting lists with INI formatting typicaally offers zero issues, providing an easy and accessible means of creating lists manually rather than through the built in interface. However, larger lists can cause issues on certain systems, specifically those with low amounts of memory. It is reccommended to break up larger list files into chunks and convert them individually rather if there are issues when converting.

## How to Install
Download the latest version from the [releases](https://github.com/ChoerrySoul/Pitchi/releases) page and move it into the desired installation folder. Pitchi will create a data directory inside that folder which will contain all required assets, the local list, and the local theme directories.
