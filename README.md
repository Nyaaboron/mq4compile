# mq4compile
A simple shell script that compiles mq4 files in the terminal

Note: Before using the script, make sure to edit the METAEDITOR variable to match the path of your metaeditor.exe.

Usage:
```
./mq4compile.sh /path/to/my/awesome_script.mq4
```

For convenience, you can move this script into a folder in your PATH:
```
# First check what folders are in your PATH
echo $PATH

# Then copy/move the script into the folder of your liking, in my case it will be ~/.local/bin
mv mq4compile.sh ~/.local/bin

# Now you can run mq4compile.sh anywhere
cd /path/to/my
mq4compile.sh awesome_script.mq4
```

Tip: Rename the script to `mqc` instead of `mq4compile.sh` to make it easier to type.
