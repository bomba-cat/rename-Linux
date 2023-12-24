# Install Instructions
- ```Install git```
- ```git clone https://github.com/xk-rl/rename-Linux```
- ```cd rename-Linux```
- ```sudo cp rename /bin```
- ```sudo cp renamedir /bin```

After that you can open your terminal and just enter rename.

# Usage
Inside the terminal you can enter: ```rename {arg1} {arg2}```
with arg1 being the file and arg2 being the new filename

this is just a little script running 2 basic commands:
- ```cp {arg1} {arg2}```
- ```rm {arg1}```

This will make a copy of the file with a new name (being arg2) and then just delete the original file.

It's also possible to rename the file and move it like this example:
```rename ~/Documents/example.txt /bin/newname.mp4```

You will be able to change the file extension too.

The same principle applies to ```renamedir {arg1} {arg2}```.

## Filenames can contain spaces!
