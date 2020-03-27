# TW-Trashbin
Trash bin tools in Tiddlywiki. Delete tiddlers and restore them easily


## Mechanism
Trash plugin has two parts

* Move to trashbin
* Restore from trashbin

### By moving a tiddler to trash bin it means

* A new data tiddler created
* The title of data tiddler is the title of objective tiddler prefixed with `$:/trashbin/`
* All the fileds of objective tiddler is moved into a new data tiddler
* The objective tiddler is deleted


### By restoring a tiddler from trash bin, it means
* A new tiddler is created
* Its title is taken from the title index in data tiddler
* All other index/value are copied to newly created tiddler fields respectively. This means every index creates a field
* The data tiddler is deleted


# Tutorial
* Open the https://kookma.github.io/TW-Trashbin/
* Go to tutorial and see a demo of most features

# Installation
For dtails on how install Shiraz plugin in your wiki, have a look at https://kookma.github.io/TW-Trashbin/#Install