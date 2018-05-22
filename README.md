# command-line-cheatsheet
A simple command line cheatsheet.

# Directory navigation

Files are stored in a tree:
    
    one.txt         two.txt   three.txt       four.txt     five.txt
    |              /                   \         |        /
    |             /                     \        |       /
    branch_to_the_left                  branch_to_the_right                  six.txt
           \                                    |                           /
            \                                   |                          /
             \______________________________    |    _____________________/
                                            \   |   /
                                             \  |  /
                                              \ | /
                                              trunk

You can climb the tree, but only branches can hold your weight. Branches are sometimes 
called "directories," sometimes "folders." Leaves are called "files." By convention, 
the "trunk" branch is called the "root directory" or "root folder" instead.

Notice that some metaphors are getting mixed here. Files and folders can be nested in
a way that works just like a tree! But that's harder to visualize in two dimensions,
or for deeply nested "folders."

Wherever you are in the tree, you can move up and down, and find information about the
branches and leaves above you and below you. Here are the basic commands you'll need:

    Command                 Mnemonic                                Action
    
    pwd                     Present Working Directory               Display your location in the tree.
    cd dir_name             Change Directory                        Move to the branch in the tree called dir_name.
    ls                      LiSt                                    Display the other branches and leaves in the tree.

Suppose you start at `trunk` above. `ls` will display the two branches (folders)
and one leaf (file) attached to the trunk. `cd branch_to_the_left` will move you onto that
branch. `ls` will then show the two leaves (files) attached to that branch.
