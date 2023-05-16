# qimgv_cat
If you work with a lot of images this helper could help you tremendously, by moving images and auto renaming them if needed. The script moves the image to a sub-directory in the same location as the image.

## Installation
Copy the `qimgv_cat` script under `/usr/local/bin` or whereever you like.

Define scripts in qimgv with the following command:

```
/usr/local/bin/qimgv_cat streetphoto %file%
/usr/local/bin/qimgv_cat portraits %file%
...etc...
```
And assign a hotkey to it, and voila with one press of a key you can move the image to a directory of your choice.

## How it works?
Calling  ```qimgv_cat street /home/user/myimage.jpg``` will:
- create a subdir `street` where `myimage.jpg` resides
- move the `myimage.jpg` into that subdir (/home/usr/street/)
- if file exists at destination, file gets auto renamed.

## Notes
Requires python3 and only uses builtin modules.
