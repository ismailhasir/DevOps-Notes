# Working Your Way Throught the CLI

## Basic Commands

- **echo** Hi   [Print to Screen]\
  ***Hi***

- **ls**  [List files & folders]\
  ***File.txt my_dir1 file2.conf***

- **cd** my_dir1  [Change Directory]

- **pwd** [Present Working Directory]\
  ***/home/my_dir1***

- **mkdir** new_directory [Make Directory]

- **cd** new_directory **;** **mkdir** www **;** pwd [Multiple Commands]\
***/home/my_dir1/new_directory***

## Commands-Directories

 /tmp/asia/india/bangalore

- **mkdir** /tpm/asia
- **mkdir** /tpm/asia/india
- **mkdir** /tpm/asia/india/bangalore
- **mkdir** ***-p*** /tpm/asia/india/bangalore [Make Directory Hierarchy]

- **rm** ***-r*** /tpm/asia/india/bangalore [Remove Directory]
- **cp** ***-r*** my_dir1 /tpm/my_dir1 [Copy Directory]

## Commands-Files

- **touch** new_file.txt [Create a new file(no contents)]

- **cat** ***>*** new_file.txt [Add contents to file]\
  This is some sample contents.\
  ***CTRL+D***

- **cat** new_file.txt [View contents of file]\
  This is some sample contents.

- **cp** new_file.txt copy_file.txt [Copy file]\

- **mv** new_file.txt [Move (Rename) File]\

- **rm** new_file.txt [Remove (Delete) File]
