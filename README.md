# my-sublime-snippet (自定义sublime代码提示)
## 使用方法
- `Sublime Text → Preferences → Browse Packages`，放入`Packages/User`文件夹下即可
## 新增代码提示
- `Tools → Developer → New Snippet`
``` sublime-snippet
<snippet>
  <content><![CDATA[
Hello, ${1:this} is a ${2:snippet}.
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <!-- <tabTrigger>hello</tabTrigger> -->
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```
