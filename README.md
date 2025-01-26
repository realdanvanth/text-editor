# Additional features that are added:
1. Add Bear and makefile for efficient compilation
2. Add 'wq' command for saving and exiting a file.
3. Add key commands :<br/>
    <b> zz </b> for deleting a line.<br/>
    <b>x</b> for deleting a character.
4. Structured files for better organization


# How to Install ?

1. clone project folder
```bash
git clone project_repo
```

2. Enter into Project folder
```bash
cd text-editor/
```

3. Build the dependency files

If Bear is not installed, then run: 
```bash
sudo apt install bear
```
Generate compile_command.json file
```bash
bear -- make
```
It builds compile_command.json file

After that run makefile
```bash
make
```
Run the text editor: 
```bash
./build/text "file_name"
```
