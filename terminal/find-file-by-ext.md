# Find a file by extension

This comes in handy whenever I want to look for files that exists with a specific extension in a computer or server:

```bash
find . -name "*.ext"
```

In addition, sometimes, you might want to look for a bunch of files with a specific extension but with matching keywords:

```bash
find .name "*.ext" | grep "keyword"
```

## BONUS: Display list of files by extension with file sizes
Last month, I was trying to free up some space in our company server, so I realized that there were a lot of *.zip* files taking up a lot of space. So, I wrote a few commands to get me a list of zip files with their file sizes in sorting order into a .txt file:

```bash
find . -iname \*.zip -exec du -sh {} \; &gt; zipfiles.txt
sort -rh zipfiles.txt > newfile.txt
```

You can .zip with any extension to suit your needs! :)


