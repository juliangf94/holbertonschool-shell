| **`0-iam_betty`** | 

This script switches the current user to the user `betty` using the `su betty` command, meeting the 8-character limit. |

| **`1-who_am_i`** | 

This script prints the **effective username** of the current user using the `whoami` command. |

| **`2-groups`** | 

This script prints all the **group names that the current effective user is a member of, using the **`groups`** command. |

| **`3-new_owner`** |  

This script changes the **owner of the file `hello` to the user **`betty`** using **`chown betty hello`**. |

| **`4-empty`** | 

This script creates an **empty file named `hello` using the **`touch` command. |

| **`5-execute`** | 

This script **adds execute permission (`x`) to the **owner** (`u`) of the file `hello` using the symbolic mode **`chmod u+x`**. |

| **`6-multiple_permissions`** | 

 This script modifies permissions for `hello` by adding **execute** to the owner and group, and **read** to others, using the symbolic mode **`chmod u+x,g+x,o+r`**. |

| **`7-everybody`** | 

This script adds **execute permission** to all categories (owner, group, others) for the file `hello`, using the universal alias **`a`** (**`chmod a+x`**). |

| **`8-James_Bond`** | 

This script **sets** the permissions of `hello` to **`-------rwx`** (all permissions only for others) using the absolute octal notation **`chmod 007`**. |

| **`9-John_Doe`** | 

This script **sets** the exact permission mode of `hello` to **`rwxr-x-wx`** using the absolute octal notation **`chmod 753`**. |

| **`10-mirror_permissions`**| 

This script sets the mode of the file `hello` to be exactly the same as the mode of the file `olleh`, using the **`chmod --reference=olleh`** option. |

| **`11-directories_permissions`**|

 This script adds **execute permission** to all **subdirectories** of the current directory using **`chmod a+x */`**. |

| **`12-directory_permissions`**| 

This script **creates a directory** named `my_dir` and sets its permissions to **`751`** simultaneously using the **`mkdir -m 751`** command. |

| **`13-change_group`** | 

This script changes the **group owner** of the file `hello` to the group **`school`** using the **`chgrp`** command. |

| **`14-change_owner_and_group`**| 

This script changes the **owner to `vincent` and the group to `staff`** for all files and directories, using the **`chown vincent:staff *`** syntax. |

| **`15-symbolic_link_permissions`**| 

This script changes the owner and group of the **symbolic link `_hello` itself** to `vincent:staff`, using the **`-h`** (no dereference) flag (**`chown -h`**). |


| **`16-if_only`** | 

This script changes the owner of the file `hello` to **`vincent` only if** the current owner is **`guillaume`**, using the conditional flag  `chown --from=guillaume`
