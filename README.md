# Linux-Commands

## pwd

The `pwd` command stands for "print working directory" in Unix-like operating systems, including Linux. It prints the absolute path of the current working directory to the standard output.

### Explanation:
- The current working directory is the directory in which a user is currently working. It's important to know the current working directory to navigate the file system effectively.
- Running pwd provides the full path to the current directory, starting from the root directory (`/`) of the file system.
- This command is particularly useful when you need to know the exact location in the file system where you are working. It helps in understanding the directory structure and facilitates navigation and file manipulation tasks.

```bash
pwd
```

## ls

The `ls` command is used in Linux and Unix-based operating systems to list files and directories in the current working directory. It's a fundamental command for navigating the file system and understanding what files and directories are present.

### Options
- `-l`: Displays the long format listing, which includes detailed information about each file or directory.
- `-h`: Makes file sizes human-readable, so you can easily understand the sizes of files.
- `-a`: Shows all files, including hidden files starting with '.'.

By combining these options (`-lha`), the ls command becomes a powerful tool for listing files and directories in a human-readable format, including hidden files, and providing detailed information about each entry in the directory.

```bash
ls
```

## mkdir

The `mkdir` command in Unix-like operating systems is used to create new directories (folders) within the file system.

### Explanation:
- Directories are used to organize files and other directories in a hierarchical structure.
- The `mkdir` command followed by the name of the directory you want to create allows you to instantly create a new directory in the current working directory.
- If you want to create a directory at a specific location in the file system, you can specify the full path to the directory you want to create.
- This command is especially useful for creating new project directories, organizing files, and maintaining a structured file system layout.

#### Examples:
- To create a new directory named "documents" in the current working directory:
```bash
mkdir documents
```
- To create a new directory named "pictures" within an existing directory named "photos":
```bash
mkdir photos/pictures
```
- To create a new directory named "work" in the root directory:
```bash
mkdir /work
```
