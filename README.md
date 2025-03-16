
# GitHub + Picx or Piclist or picgo 制作图床

## 网上有很多类似的教程，但本文出发点在于：解决 GitHub 图床的国内访问问题（通过vercel+二级域名）or (github pages)

# 前期准备(click)
1.  [GitHub 账号](https://github.com/)
2. [vercel账号](https://vercel.com/)
3. [二级域名](https://ym.bailanyun.cn/)(以摆烂云为例)
4. [picx](https://picx.xpoet.cn/)
5. [piclist](https://piclist.cn/)
```scoop
scoop bucket add lemon https://github.com/hoilc/scoop-lemon
scoop install lemon/piclist
```
## !!!关于github 账号!!!

[stean++下载](https://steampp.net/download) 可以解决github 外网登入问题 

[steam++ windows gitee下载直链](https://gitee.com/rmbgame/SteamTools/releases/download/3.0.0-rc.15/Steam%20%20_v3.0.0-rc.15_win_x64.exe)

[2025github注册 作者: 久绊A ](https://blog.csdn.net/m0_67906358/article/details/145818218?sharetype=blog&shareId=145818218&sharerefer=APP&sharesource=m0_67906358&sharefrom=link)

# 开始!! 

现在你已经有了github account 

## Using PicX 

[**picx**](https://picx.xpoet.cn/)

![](https://ffaffaha.tbit.top/PIclist/20250316181106415.png)

![](https://ffaffaha.tbit.top/PIclist/20250316181200566.png)

借助 PicX 他会为你创建 仓库 请放心使用授权

## Using vercel 

[vercel账号](https://vercel.com/)

### 创建账号

![](https://ffaffaha.tbit.top/PIclist/20250316182547450.png)

![](https://ffaffaha.tbit.top/PIclist/20250316182633865.png)

### Add New Project

![](https://ffaffaha.tbit.top/PIclist/20250316170425706.png)
![](https://ffaffaha.tbit.top/PIclist/20250316183009128.png)
![](https://ffaffaha.tbit.top/PIclist/20250316183045428.png)

完成后的

![](https://ffaffaha.tbit.top/PIclist/20250316183225616.png)

### 二级域名

[二级域名](https://ym.bailanyun.cn/)(以摆烂云为例)

![](https://ffaffaha.tbit.top/PIclist/20250316183454333.png)

### 重要的是

- 主机记录 xxx.xxx.cn
- 记录类型  `CNAME`
- 记录值 `cname.vercel-dns.com.`


![](https://ffaffaha.tbit.top/PIclist/20250316183733736.png)

## 返回 vercel 

![](https://ffaffaha.tbit.top/PIclist/20250316184122814.png)

![](https://ffaffaha.tbit.top/PIclist/20250316184225213.png)

![](https://ffaffaha.tbit.top/PIclist/20250316184254288.png)

![](https://ffaffaha.tbit.top/PIclist/20250316184453738.png)

![](https://ffaffaha.tbit.top/PIclist/20250316184744379.png)

## 返回 PicX

![](https://ffaffaha.tbit.top/PIclist/20250316185023624.png)

### 添加 二级域名

例如 `https://ffaffaha.tbit.top/{{path}}`

![](https://ffaffaha.tbit.top/PIclist/20250316185051530.png)
![](https://ffaffaha.tbit.top/PIclist/20250316185908218.png)

# picX end 

# 本地 Piclist

## [github classic token](https://github.com/)

只有一个重点! [github classic token](https://github.com/)

![](https://ffaffaha.tbit.top/PIclist/20250316171801342.png)
![](https://ffaffaha.tbit.top/PIclist/20250316171822520.png)
![](https://ffaffaha.tbit.top/PIclist/20250316171850572.png)
![](https://ffaffaha.tbit.top/PIclist/20250316171929145.png)
![](https://ffaffaha.tbit.top/PIclist/20250316172009881.png)
![](https://ffaffaha.tbit.top/PIclist/20250316172116169.png)
![](https://ffaffaha.tbit.top/PIclist/20250316172219838.png)
![](https://ffaffaha.tbit.top/PIclist/20250316172334024.png)
![](https://ffaffaha.tbit.top/PIclist/20250316172240540.png)

## [piclist下载](https://piclist.cn/)

这里给出scoop安装 或者去官网[piclist](https://piclist.cn/)

```cmd
scoop bucket add lemon https://github.com/hoilc/scoop-lemon
scoop install lemon/piclist
```

![](https://ffaffaha.tbit.top/PIclist/20250316171621584.png)

## piclist配制
![](https://ffaffaha.tbit.top/PIclist/20250316191059763.png)
![](https://ffaffaha.tbit.top/PIclist/20250316191554996.png)

## 结果
支持vscode markdow https 预览
![](https://ffaffaha.tbit.top/PIclist/20250316193014524.png)

# Question 
1. why use piclist ? 

通常picx日常使用已经很好了, 但是不支持 vscode 等 本地软件 (作者使用VScode写markdown,有机会将写 vscode插件Markdown Preview Enhanced的自定义 CSS
style.less部分)
![](https://ffaffaha.tbit.top/PIclist/20250316192438136.png)

