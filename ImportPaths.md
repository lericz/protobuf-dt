If all your .proto files are stored in a single folder, you can stop reading now.

On the other hand, if your .proto files are stored in more than one folder and they import each other across folders, you will need to tell protobuf-dt all the source folders for your .proto files, otherwise type resolution and hyperlinking won't work.

Configuration must be made at the project level. Simply right-click a project and select "Properties" option from the pop-up menu. Once the properties dialog shows up, select the node "Import Paths" under "Protocol Buffer" on the tree view. You should see a page like this one:

![http://wiki.protobuf-dt.googlecode.com/git/images/importPaths.png](http://wiki.protobuf-dt.googlecode.com/git/images/importPaths.png)

Select the option "Look for imported files in directories" and add as many folders as necessary. Then click the OK button.

