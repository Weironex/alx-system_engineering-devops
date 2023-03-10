|Filename| Description|
|---|---|
|<code>0-iam_betty</code>|Switch the current user to the user <code>betty</code>|
|<code>1-who_am_i</code>|Prints the effective username of the current user|
|<code>2-groups</code>|Prints the current user is part of|
|<code>3-new_owner<code>|Changes the owner of the <code>file</code> hello to the user <code>betty</code>|
|<code>4-empty</code>|Creates an empty file called <code>hello</code>|
|<code>5-execute</code>|Adds execute permission to the owner of the file <code>hello</code>|
|<code>6-multiple_permissions</code>|Adds execute permission to the owner and the group owner, and read permission to other users, to the file <code>hello</code>|
|<code>7-everybody</cpde>|Adds execution permission to the owner, the group owner and the other users, to the file <code>hello</code>|
|<code>8-James_Bond</code>|Sets the permission to the file <code>hello</code> as follows: <code>"Owner: no permission at all", "Group: no permission at all", "Other users: all the permissions"</code>|
|<code>9-John_Doe</code>|Sets the mode of the file <code>hello</code> to this: <code>"-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello"</code>|
|<code>10-mirror_permissions</code>|Sets the mode of the file <code>hello</code> the same as <code>olleh</code>’s mode|
|<code>11-directories_permissions</code>|Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users|
|<code>12-directory_permissions</code>|Creates a directory called <code>my_dir</code> with permissions 751 in the working directory|
|<code>13-change_group</code>|Changes the group owner to <code>school</code> for the file <code>hello</code>|
|<code>100-change_owner_and_group</code>|Changes the owner to <code>vincent</code> and the group owner to <code>staff</code> for all the files and directories in the working directory|
|<code>101-symbolic_link_permissions</code>|Changes the owner and the group owner of <code>_hello</code> to <code>vincent</code> and <code>staff</code> respectively|
|<code>102-if_only</code>|Changes the owner of the file <code>hello</code> to <code>betty</code> only if it is owned by the user <code>guillaume</code>|
  |<code>103-Star_Wars</code>|Plays the StarWars IV episode in the terminal|
