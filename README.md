Allows you to quickly restrict Alfred searches to a specific folder

# Installation

    git clone git://github.com/sabberworm/Quick-Folder-Search.alfredworkflow.git "~/Library/Application Support/Alfred 2/Alfred.alfredpreferences/workflows/user.workflow.194B4B63-F905-40C3-AAA1-365A38D2570A"

The [name](https://github.com/sabberworm/Quick-Folder-Search.alfredworkflow/blob/d403eb7234458e506e76a5a022b54d32f3845335/info.plist#L123) of the checked out workflow folder is important because Alfred does not allow relative paths in file filters.

# Usage

  * Find a folder in Alfred and run “Quick Folder Search” on it. A search field will pop up.
  * To search again in the previously selected folder, type `qfs «searchterm»`.

You can use the `qfs` filter as long as you want until you decide to make a new folder your search folder using “Set as Quick Search Folder”.
