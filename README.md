# tkmenulib | Tkinter GUI Menu Library
**Simple and bug-limited**
## Requirements
- Tkinter installed (**NOT** Custom TK ctk)
- Nothing else




## Usage



### BASIC USAGE
Just show actions and do their functions:
```python
def sayHi():
    print("Hello World")
basicLib(options={"Action Name goes Here": sayHi}  )
```
That will pull up a window that has a button saying "Action Name goes Here", when you press it, it activates the sayHi function.






### BASIC ARGS
backgroundColor
*Make sure it is a tk color. Basic usage:*
```py
basicLib(options={"Action Name goes Here": sayHi}, backgroundColor="red")
```
*If you do that it* ***WILL*** *change the background color, but you cant see it because we are using one button the fills up the whole screen. You can fix that by making the window size bigger with the size arg or add more buttons.*





size
*This simply makes the window bigger. Because it is so simple I will not provide an example. But a arg reference,*
```python
x_cord = "100"
y_cord = "55"
# arg below this text
size=f"{x_cord}x{y_cord}"
```





### ARG TREE
```python
options: dict, backgroundColor:str="dark gray", tkName:str="Menu",
                      useGrid:bool=False,
                      buttonActiveBackground:str="green",
                      size:str=None, font:str="Ebrima Regular",
                      fontsize:int=10
```
