

/* Changes that are made */
# Additional features that are added:
1. Add Bear and makefile for efficient compilation
2. Add 'wq' command for saving and exiting a file.
3. Add key commands :<br/>
    <b> zz </b> for deleting a line.<br/>
    <b>x</b> for deleting a character.
4. Structured files for better organization

/* Installation process */
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
/* */


# realvim
minimal text editor in c inspired by neovim

![image](https://github.com/user-attachments/assets/0ed04b35-bb1f-4230-9923-c75384e17fd8)


![image](https://github.com/user-attachments/assets/015dee65-f9ac-424a-b597-a8d10dcec538)


**Installation and Execution**

```install
git clone https://github.com/realdanvanth/realvim.git
```
```execute
cd ~/realvim/src && gcc -Wall "text.c" -o text -lncurses && ./text text.c
```
```
cd ~/realvim/src && gcc -Wall "text.c" -o text -lncurses && ./text sample.txt
```

# Text Editor Navigation Guide

| **Key**   | **Mode**      | **Action**                     |
|-----------|---------------|---------------------------------|
| `wasd`    | **Navigation**| Move cursor (up, left, down, right). |
| `q`       | **Command**   | Quit the editor.               |
| `i`       | **Insert**    | Switch to insert mode.         |
| `Escape`  | **Visual**    | Return to visual/command mode. |
| `:`       | **Command**   | Enter command mode             |

### Usage Notes:
- **Navigation Mode:** Use `wasd` to move the cursor around within the document.
- **Insert Mode:** Press `i` to start typing or editing the document content.
- **Quiting the Editor:** Press `q` to exit the editor. Ensure all changes are saved beforehand.
- **Returning to Visual Mode:** Press `Escape` to leave insert mode and switch back to visual mode.

