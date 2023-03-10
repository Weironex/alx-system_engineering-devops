|Filename| Description|
|---|---|
|<code>0-iam_betty</code>| Switch the current user to the user <code>betty</code>|
|<code>1-who_am_i</code>| Prints the effective username of the current user|
|<code>2-groups</code>| Prints the current user is part of|
|<code>3-new_owner<code>| Changes the owner of the <code>file</code> hello to the user <code>betty</code>|
|<code>4-empty</code>| Creates an empty file called <code>hello</code>|
|<code>5-execute</code>| Adds execute permission to the owner of the file <code>hello</code>|
|<code>6-multiple_permissions</code>| Adds execute permission to the owner and the group owner, and read permission to other users, to the file <code>hello</code>|
|<code>7-everybody</cpde>| Adds execution permission to the owner, the group owner and the other users, to the file <code>hello</code>|
|<code>8-James_Bond</code>| Write a script that sets the permission to the file <code>hello</code> as follows:
<li>Owner: no permission at all
Group: no permission at all
Other users: all the permissions</li>
|<code>9-John_Doe</code>| Write a script that sets the mode of the file <code>hello</code> to this:
* -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
