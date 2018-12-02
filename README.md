# picbed-mweb-gitee

## 需要自定义

### 改为要存储的本地目录
```python
baseDir = '/Users/canvas/Documents/Tower/picbed/Images/'
```

### 自动提交到 Coding 远程仓库便于调用

> 修改为自己的远程`coding`地址

```python
os.system('cd /Users/canvas/Documents/Tower/picbed && git add . && git commit -m "Added some imgs" && git push origin master')
```

### 修改端口号

```python
if __name__ == "__main__":
	app.run(host="127.0.0.1", port=7002)
```

### MWeb

![](https://gitee.com/athlonreg/picbed/raw/master/Images/60/8bfa1f2c5f8e9a3a9479823ae4ad43.jpg)

图片`URL`前缀为

`https://coding.net/u/iamzhl/p/PicBed/git/raw/master/Images/`

将`iamzhl`修改为你的用户名，`PicBed`改为存放图片的项目名。
