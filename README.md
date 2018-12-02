# picbed-mweb-gitee

## 需要自定义

### 改为要存储的本地目录
```python
baseDir = '/Users/canvas/Documents/Tower/gitlab-picbed/Images/'
```

### 自动提交到 Gitee 远程仓库便于调用
> 修改为自己的远程码云地址

```python
os.system('cd /Users/canvas/Documents/Tower/gitlab-picbed && git add . && git commit -m "Added some imgs" && git push origin master')
```

### 修改端口号

```python
if __name__ == "__main__":
	app.run(host="127.0.0.1", port=7003)
```

### MWeb

![](https://gitee.com/athlonreg/picbed/raw/master/Images/b4/20dbc755692fc09aff518901033fb4.jpg)
