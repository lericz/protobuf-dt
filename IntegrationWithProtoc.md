protobuf-dt provides integration with protoc, protobuf's compiler, to compile the .proto file being currently edited and generate Java, C++ or Python code from such file. protobuf-dt creates error markers in the editor if protoc finds any errors.

Integration with protoc is **disabled** by default.

**New in v1.2.0!**

If integration with protoc is enabled, the output of protoc will be shown in Eclipse's console:

![http://wiki.protobuf-dt.googlecode.com/git/images/compiler-console.png](http://wiki.protobuf-dt.googlecode.com/git/images/compiler-console.png)


## Configuring protoc integration ##

protoc integration can be configured at the workspace level or project level. Both types of configuration offer exactly the same options.

Before integrating protobuf-dt with protoc, you'll need to download and install the latest [protobuf distribution](http://code.google.com/p/protobuf/downloads/list).

### Workspace preferences ###
To configure workspace-level protoc integration, go to the menu "Window" > "Preferences." In the "Preferences" dialog, open the "Protocol Buffer" element on the tree view on the left-hand side and select "Compiler."

#### 1. Main Tab ####

![http://wiki.protobuf-dt.googlecode.com/git/images/compiler-main-preferences.png](http://wiki.protobuf-dt.googlecode.com/git/images/compiler-main-preferences.png)

In this tab, you can

  1. compile a .proto file (with protoc,) every time it is saved
  1. specify the path of protoc
  1. specify the path of the descriptor.proto file to use when compiling .proto files (optional)

#### 2. Options Tab ####

![http://wiki.protobuf-dt.googlecode.com/git/images/compiler-options-preferences.png](http://wiki.protobuf-dt.googlecode.com/git/images/compiler-options-preferences.png)

In this tab, you can

  1. specify the target language for code generation
  1. specify the folder where to store the generated code

#### 3. Refresh Tab ####

![http://wiki.protobuf-dt.googlecode.com/git/images/compiler-refresh-preferences.png](http://wiki.protobuf-dt.googlecode.com/git/images/compiler-refresh-preferences.png)

In this tab, you can specify whether resources should be refreshed after invoking protoc.

### Project preferences ###

To configure project-specific protoc integration, simply right-click and project and select "Properties" from the pop-up menu. Project-level preferences are exactly the same as workspace-level ones.

### Note ###

By default, the option "Compile .proto files on save" is **disabled** in both workspace and project preferences.

