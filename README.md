# Database in C

A simple database based on SQLite written in C.

## Usage
Download the repl.c file and put it in a directory.
Open the terminal and follow the commands below.<br>
> <code>cd YOUR_DIRECTORY_NAME</code><br>
> <code>gcc repl.c -o db</code><br>
> <code>./db FILENAME.db</code>

## Features
- <code>select</code>  [prints all the rows]
- <code>insert ID USERNAME EMAIL</code>  [inserts a row]
- <code>.bTree</code>  [prints a Tree representation of the database]
- <code>.constants</code>  [prints some important headers]
- <code>.exit</code>  [saves the database on disk and quits]

## To Dos
- Deletion
- Updating a row
