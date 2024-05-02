# Useful Bash scripts

A collection of useful Bash scripts to assist with terminal workflow.

---

__Potentially destructive scripts (can delete files interactively)__:

__`extract`__ -- Extracts every archive in the current directory and
subdirectories.

---

Scripts that can create files, but won't delete any:

__`new-md5`__ -- Recursively creates MD5 files and checks for missing entries in
existing MD5 files.

---

Scripts that won't create or delete files, eg. info aggregators:

__`files`__ -- Lists all filetypes in the current directory. Useful when
searching for unnecessary files. Example output:

```
$ files /dir/to/documents
      3 jpg
      7 txt
     31 md
41 total
```

__`file-depths`__ -- Calculates file counts for each directory depth and groups
them together. Useful when organizing a directory. Example output:

```
$ file-depths /dir/to/documents
      3 
     91 /
    102 //
     39 ///
```
