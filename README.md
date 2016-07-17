# 观看ppt
下载下来之后，直接用浏览器打开Open_edX.slides.html就行


# Creating Presentation Slides with Jupyter notebook
*  jupyter notebook --notebook-dir="." ：编辑ipynb原始文件
*  jupyter-nbconvert --to slides Open_edX.ipynb --reveal-prefix="http://cdn.bootcss.com/reveal.js/3.3.0"  --post serve  //编译
*  修改theme：在生成的html里，修改：css/theme,目前只有simple和sky比较正常，使有的可选项为

```
beige.css
black.css
blood.css
league.css
moon.css
night.css
README.md
serif.css
simple.css
sky.css
solarized.css
white.css
```

# 知识点

# 参考
* [blog post](http://echorand.me/presentation-slides-with-jupyter-notebook.html#.V19WnWJ96V4) 
