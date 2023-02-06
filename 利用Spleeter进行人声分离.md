# 项目介绍
Spleeter 是一个使用预训练模型、Python 编写的运用 Tensorflow 项目的音源分离库。
特点：
- 预训练的模型使其拥有良好的分离速度
- 分离效果良好
# 安装
Spleeter 可以直接用 pip (python 的包管理器) 安装。
```
$ pip install spleeter
```
同时也可以直接安装 SpleeterGUI (带有图形界面)。
使用（命令行）
运行以下命令即可得到 spleeter 的内置帮助。
```
$ spleeter –help
```

# 重要选项：
- -b <比特率> 分离产物的比特率 [128k]
- -c <编码> 分离产物的编码 [wav]
- -o <路径> 分离产物的路径 [/tmp/separated_audio]
- -p spleeter:<分离类型> 指定如何分离 [2stems(人声、伴奏)]

*例子：分离 example.mp3，产物输出至 ./output（人声：output/example/vocals.mp3; 伴奏：output/example/accompaniment.mp3）。*

