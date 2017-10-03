# Unorganized notes

### Headfirst Python
`os.getcwd()`: get current path

`os.chdir('')` change directory

`data.seek(0)`回到文件起始位置

`split(':',1)`以：分开，maxsplit为1

`strip()`，`upper()`等BIF其实会创建一个新的字符串，被替换的数据被装入RAM，不会改变原来的数据。

在某个函数的help里面：按q回去

Java里的try catch在Python里是：

```
try:...	
except ValueError: 
	pass
finally:
	egfile.close()
```
Value Error出现于数据不符合期望格式时，如`each_line.split(':',1)`里面没有':'时

想要创建一个文件：
`man_file= open('man_data.txt','w')`
直接把格式改成‘w’