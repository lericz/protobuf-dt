Please follow these instructions to get and compile the source code:

  1. Download [Eclipse](http://eclipse.org/downloads/index-developer.php) "for RCP and RAP Developers"
  1. Get the latest version of Xtext and EMF SDK
  1. Get protobuf-dt source from the [Git repo](https://code.google.com/p/protobuf-dt/source/checkout)
  1. Create the folder "src-gen" in both projects `com.google.eclipse.protobuf` and `com.google.eclipse.protobuf.ui`
  1. Go to project `com.google.eclipse.protobuf` and navigate to the file `GenerateProtobuf.mwe2` (in the package `com.google.eclipse.protobuf`, in the `src` folder)
  1. Right-click `GenerateProtobuf.mwe2` and select "Run As" > "MWE2 Workflow"

That will generate the Xtext-based infrastructure needed. Now the source code is complete, simply run the project `com.google.eclipse.protobuf` as an "Eclipse Application."

Enjoy!

