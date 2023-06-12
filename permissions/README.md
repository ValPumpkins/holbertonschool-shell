<h1>Shell, Permissions</h1>
<h2>Scripts Description</h2>
<ul>
<li><strong>0-iam_betty</strong> : Switches the current user to the user betty</li>
<li><strong>1-who_am_i</strong> : Prints the effective username of the current user</li>
<li><strong>2-groups</strong> : Prints all the groups the current user is part of</li>
<li><strong>3-new_owner</strong> : Changes the owner of the file hello to the user betty</li>
<li><strong>4-empty</strong> : Creates an empty file called hello</li>
<li><strong>5-execute</strong> : Adds execute permission to the owner of the file hello</li>
<li><strong>6-multiple_permissions</strong> : Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello</li>
<li><strong>7-everybody</strong> : Adds execution permission to the owner, the group owner and the other users, to the file hello</li>
<li><strong>8-James_Bond</strong> : Sets the permission to the file hello as follows: Owner: no permission at all / Group: no permission at all / Other users: all the permissions</li>
<li><strong>9-John_Doe</strong> : Sets the mode of the file hello to -rwxr-x-wx</li>
<li><strong>10-mirror_permissions</strong> : Sets the mode of the file hello the same as olleh’s mode</li>
<li><strong>11-directories_permissions</strong> : Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files will not be changed</li>
<li><strong>12-directory_permissions</strong> : Creates a directory called my_dir with permissions 751 in the working directory</li>
<li><strong>13-change_group</strong> : Changes the group owner to school for the file hello</li>
<li><strong>14-change_owner_and_group</strong> : Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory</li>
<li><strong>15-symbolic_link_permissions</strong> : Changes the owner and the group owner of _hello to vincent and staff respectively (_hello is a symbolic link)</li>
<li><strong>16-if_only</strong> : Changes the owner of the file hello to vincent only if it is owned by the user guillaume</li>
</ul>
