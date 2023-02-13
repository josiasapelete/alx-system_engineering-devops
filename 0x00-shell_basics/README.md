#Shell Basic

pwd : prints the absolute path name of the current working directory
ls: Display the contents list of your current directory.
cd ~:changes the working directory to the user’s home directory
ls -l: Display current directory contents in a long format
ls -al :Display current directory contents, including hidden files (starting with .). Use the long format
mkdir nameOfTheDirectory: make directorie
mv /tmp/betty /tmp/myDirectory: Move the file "betty" from tmp to /tmp/myDirectory
rm fileName: delete the file "fileName"
rm -r DirectoryName: delete the directory "DirectoryName"
cd -: changes the working directory to the previous one.
ls -la . .. /boot: list all files in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file fileName: prints the type of the file named filename
ln -s /bin/ls __ls__ :Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory
cp -u *.html .. : copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
