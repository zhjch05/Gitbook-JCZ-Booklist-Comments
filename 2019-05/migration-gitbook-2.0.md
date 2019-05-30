# Migration: GitBook 2.0

站点从Legacy Gitbook migrate到了2.0!

新的界面和功能！

域名不变！

非常喜欢了



来自程序员使用gitbook加onyx boox note pro annotations export的心得 \(which is very hacky\):

```bash
sed '/.*$/{G;}' annotations.txt > extraline.md
```

使用了这个之后，原来导出的annotations.txt每行都会多一行回车，用来直接copy进gitbook的markdown格式，不经过此步骤，格式会乱

