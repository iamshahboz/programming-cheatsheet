### Most used Linux commands

1. Print out currently logged in user
```bash
whoami
```

2. Clean the terminal screen
```bash
clear
```

3. See current location in a given terminal window

```bash
pwd
```

4. List content of folder
```bash
ls
```

```bash
ls -la
```

5. Change directory
```bash
cd
```

cd foldername

6. Make directory (Create a folder)
```bash
mkdir foldername
```

7. Create an empty file
```bash
touch filename  
```
--extention should be added, if no it will be txt file by default


8. Delete empty directory
```bash
rmdir foldername
```


9. Delete folders or files
```bash
rm filename
```


flags
-v verbose ~ it will show each of the step what it did

-r ~ remove directory with its content
-i ~ it will ask each of the step what to delete and what not

10. Open
```bash
open filename
```


11. Move file or Rename file
```bash
mv
```

mv file.txt newfile.txt - we renamed the file

mv file.txt students/ - we moved the file.txt to students folder

12. Copy the file
```bash
cp journal.txt todays_journal 
```
this copies the file to the same forlder with other name


13. Print the content of the file
```bash
cat students.txt 
```
prints the content of the students.txt file


14. 
```bash
less students.txt 
```
does the similar work with cat, but you will have a better view, you can scroll and search

 
15. Print out the argument to the terminal
```bash
echo
```

echo "PASSWORD=mypass123" > config.txt  - it takes an argument, it echo back instead it will redirect to file
which does not exist yet

16. Count the word
```bash
wc song.txt 
```
it return the number of lines, words, bytes


17. Find files
```bash
find
```
find . -name '*.js' - that will find all the files which has the name with extention js

18. Find text in a file
```bash
grep  great students.txt 
```
that will find all great words the file has


19. Find the size of files or directories
```bash
du student 
```
will return the size of student folder



20. Show top most CPU intensive processes
```bash
top
```

21. Kill programms
```bash
kill <PID>
```

22. Compress file / it uses the compression protocol LZ77
```bash
gzip
```

gzip my_file

23. Unzip the file to get the original 
```bash
gunzip 
```
gunzip my_file

24. Create an archieve, grouping multiple files in a single file
```bash
tar
```
tar -cf archive.tar file1 file2

to extract back

tar -xf archive.tar

25. Nano text editor. You can directly edit the file with this command
this will open a file in edit mode

```bash
nano file.txt
```

26. we can create an alias command for long commands, note that alias will be permanent for this, it will not last long

```bash
alias myls='ls -la'
```

a good place to keep aliases will be .bashrc
nano .bashrc
and we write the alias there




