# Including and excluding files in zip

When zipping a directory or a bunch of files, there'll be a lot of stuff that you want to include and exclude.

To exclude a file:
```bash
zip -r files.zip . -x file_1 file_2
```

Alternatively, you can choose to include files:
```bash
zip -r files.zip . -i file_1 file_2
```