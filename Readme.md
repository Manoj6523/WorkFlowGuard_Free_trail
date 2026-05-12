
# WorkflowGuard

A simple command-line tool that encrypts and protects your files using a custom character mapping system.

## What Is This?

**Author:** N Manoj Kumar  
**Type:** File encryption tool (runs from command line)  
**How it works:** Offline no internet needed  
**Main use:** Protect your source code files with encryption

⚠️ **Important:** This tool is only as secure as your dictionary file. Keep `Dictionary_File.py` safe!

## Key Rules

- This tool only works on the computer where it was set up
- It won't run on other computers
- If someone tries to use it elsewhere, backup files are automatically deleted

## What's Included

```
workflowguard/
│
├──DataVault
├──Converter.exe
├──HideFile.py
├──JumpleDic.py 
├──Dictionary_File.py
├──LICENSE.txt
├──PRODUCT_DESCRIPTION.md
└──README.md
```

## Main Features

1. **Encrypt single or multiple files** - Protect one file or process many at once
2. **Store file locations** - Keep track of which files you encrypted
3. **Automatic backups** - Creates backup copies before encrypting
4. **Easy file management** - View, organize, or delete your file list
5. **Extra security options** - Hide your dictionary file or shuffle encryption patterns

## How to Use

```
1) Single         - Encrypt/decrypt one file
2) Multiple       - Encrypt/decrypt many files
3) Delete         - Remove all stored file paths
4) ShowFiles      - See all encrypted files
5) ShowSingleFile - See one file's location
6) Backup         - Back up your encrypted files
7) SecFile        - Security features
        • hide        - Move dictionary to safe location
        • shuffle     - Change encryption pattern

## Safety Features

- Clear error messages (easy to understand)
- Checks files exist before encrypting
- Verifies dictionary file is present
- Tests backup files before operations
