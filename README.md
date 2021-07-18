<!-- MDTOC maxdepth:6 firsth1:1 numbering:0 flatten:0 bullets:1 updateOnSave:1 -->

- [JetBrains全家桶 IDE 常用技巧](#jetbrains全家桶-ide-常用技巧)   
   - [激活](#激活)   
   - [启用Vim](#启用vim)   
   - [启用Vim相对行号](#启用vim相对行号)   
   - [鼠标滚动放大/缩小字体](#鼠标滚动放大缩小字体)   
   - [格式化代码](#格式化代码)   
   - [注释](#注释)   
   - [删除](#删除)   
   - [复制](#复制)   
   - [选中区域自动包裹括号引号](#选中区域自动包裹括号引号)   
   - [自动补全启用大小写支持](#自动补全启用大小写支持)   
   - [代码缩进及反缩进](#代码缩进及反缩进)   
   - [快速实现接口](#快速实现接口)   

<!-- /MDTOC -->
# JetBrains全家桶 IDE 常用技巧

## 激活

1. 套路：重置试用来达到无限试用目的(试用期将过时重新操作一番)

* 参考：<https://gitee.com/pengzhile/ide-eval-resetter>

```
1. Download and install plugin from [Download Link](https://plugins.zhile.io/files/ide-eval-resetter-2.1.14-d2fedb86.zip).
    * Alternative installation method:
        * Add "Custom Plugin Repository": `https://plugins.zhile.io` manually (`Settings/Preferences` -> `Plugins`)
        * Search and install plugin: `IDE Eval Reset`
2. Click `Help` or `Get Help` -> `Eval Reset` menu.
3. Click `Reset` -> `Yes` button.
4. Restart your IDE.
5. Now you have another 30 days eval time :)
6. For more information, visit [here](https://zhile.io/2020/11/18/jetbrains-eval-reset-da33a93d.html).
```


![20210718_121110_31](image/20210718_121110_31.png)

添加仓库


```
https://plugins.zhile.io
```

![20210718_121136_48](image/20210718_121136_48.png)

安装 IDE Eval Reset

![20210718_121222_14](image/20210718_121222_14.png)

![20210718_121231_41](image/20210718_121231_41.png)

Reset 重置试用，延长一个月试用期

![20210718_121323_19](image/20210718_121323_19.png)

![20210718_121346_12](image/20210718_121346_12.png)


![20210718_121426_16](image/20210718_121426_16.png)

## 启用Vim

File->Settings->Plugins 安装IdeaVim插件

![20210712_212220_63](image/20210712_212220_63.png)

File->Settings->Keymap 选择**适合**自己的开关，用于Vim模式和Idea模式快速切换


![20210712_212319_94](image/20210712_212319_94.png)

## 启用Vim相对行号

右小脚IdeaVim标志，没有配置则会创建，有配置就是open，添加vimrc内容即可

![20210718_111153_85](image/20210718_111153_85.png)

![20210718_111313_82](image/20210718_111313_82.png)


```
"" Source your .vimrc
"source ~/.vimrc

set nm
set relativenumber
```


## 鼠标滚动放大/缩小字体

方法一：

![20210713_192537_75](image/20210713_192537_75.png)

方法二：

File->Settings->Keymap 搜索中输入increase

![20210712_212433_95](image/20210712_212433_95.png)

![20210712_212455_76](image/20210712_212455_76.png)

![20210712_212505_42](image/20210712_212505_42.png)

File->Settings->Keymap 搜索中输入decrease

![20210712_212533_57](image/20210712_212533_57.png)

![20210712_212552_36](image/20210712_212552_36.png)

![20210712_212541_87](image/20210712_212541_87.png)

## 格式化代码

```
Ctrl + Alt + L (小写l)
```

## 注释

默认光标所在行注释，若选中多行则都会注释

```
Ctrl + /
```

## 删除

默认删除光标所在行，若选中多行则都会删除

```
Ctrl + x
```

## 复制

默认复制光标所在行，若选中多行则都会复制

```
Ctrl + d
```

## 选中区域自动包裹括号引号

```
Surround selection on typing quote or brace
```

Editor -> General -> Smart Keys

![20210713_200653_75](image/20210713_200653_75.png)


## 自动补全启用大小写支持

```
Match case
```

Edirotr -> Gneeral -> Code Completion

![20210713_200833_62](image/20210713_200833_62.png)


## 代码缩进及反缩进

```
缩进：Tab
反缩进：Shift + Tab
```

## 快速实现接口

在 type struct 上使用

![20210714_215053_26](image/20210714_215053_26.png)










---
