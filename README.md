## 4D Commands Sublime Editor Snippets

#### Installation on Sublime Text 3

###### Instructions

1. Open the Sublime Text packages folder

    `~/Library/Application\ Support/Sublime\ Text\ 3/Packages` or "Sublime Text > Preferences > Browse Packages..." on Mac
    `%AppData%\Sublime Text 3\Packages\User` or "Sublime Text > Preferences > Browse Packages..." on Windows

2. Download the repository and put it in the "User" folder

### Usage

You have a snippet for each 4D commands available.

In addition you also have each 4D Tags available as a snippet.

If you want the snippets list to show while you are typing make sure to add those settings :

```
	"auto_complete":true,
	"auto_complete_selector": "text.html,text.html.basic comment.block.html, text.xml,text.xml comment.block.xml"
```
In your user settings file.

You can find 2 version of the snippets which you can use at your convenience.

1. With Params : The attributes are there and using the "Tab" key you can navigate through them.
2. Without Params : Only the name of the 4D command will be there after validation a snippet.

You can use one or both if you sometime like to have the attribute and sometime not.

The space of the command are replaced by "_" because Sublime don't recognize a space as a part of the snippet. For example if you want to get the `LISTBOX INSERT COLUMN` you can type `listbox_insert` and you will get the command in the list

For more information please refere to [4D Doc - 4D Transformation Tags](https://doc.4d.com/4Dv17R3/4D/17-R3/4D-Transformation-Tags.300-3907284.en.html#2880084)

### Contributing

1. Fork it.
2. Create your feature branch (`git checkout -b my-new-feature`).
3. Test your changes to the best of your ability.
4. Update the documentation to reflect your changes if they add or changes current functionality.
5. Commit your changes (`git commit -am 'Added some feature'`).
6. Push to the branch (`git push origin my-new-feature`).
7. Create a new pull request.
