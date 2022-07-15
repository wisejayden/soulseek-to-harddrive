# soulseek-to-harddrive
A script for Mac that will move all the files found in the subdirectories of the Downloads folder, and then move them to the Hard Drive.

## Instructions on how to create custom Alias to run Shell script

From your terminal open your `bash_profile`
```shell
    nano ~/.bash_profile
```
Add your new custom Alias - I'm using `soulseek` in this example.
```shell
    alias soulseek='sh {path_to_shell_script}'
```
Then either reopen your terminal or run the following script
```shell
    source ~/.bash_profile
```
Run your new Alias from the command line to begining moving those files!
```shell
    soulseek
```

