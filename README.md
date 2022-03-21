# Python Basic Tips and tricks

Writing down here things to remember and use later on 

## String Formatting
When we write a string, we can leave a place filler using `{}` and then use `<string>.format(thing_to_write)` which will insert it. Can modify this further by specifying the display type, ie, if we want a float with two decimal points, use `{variable}:.2f`

<b> Examples </b> 
```python3
"{} {}".format(self.__class__.__name__, self.content)
```
for a class instance of class `Generic` with content `5` would return `Generic 5`. 
