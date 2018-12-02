# picbed-mweb-gitee

## 需要自定义

### 改为要存储的本地目录
```python
baseDir = '/Users/canvas/Documents/Tower/gitee-picbed/Images/'
```

### 自动提交到 Gitee 远程仓库便于调用
> 修改为自己的远程码云地址

```python
os.system('cd /Users/canvas/Documents/Tower/gitee-picbed && git add . && git commit -m "Added some imgs" && git push origin master')
```

### 修改端口号

```python
if __name__ == "__main__":
	app.run(host="127.0.0.1", port=7001)
```

### MWeb

![](https://gitee.com/athlonreg/picbed/raw/master/Images/12/94d456fa40eaccea1da1010db56a2a.jpg)

> 图片URL前缀为

`https://gitee.com/athlonreg/picbed/raw/master/Images`

将`athlonreg`修改为你的用户名，`picbed`改为存放图片的项目名。
