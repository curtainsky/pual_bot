# pual_bot 一个弱智的QQ机器人
pual_bot是一套建立在`Tornado`上的高效的支持并发的WebQQ机器人, 其主要功能有 执行Python代码, 贴代码, 英汉互译

# 安装配置
程序依赖tornado, 可使用 easy_install 安装
```bash
easy_install tornado
```

将`config.py.example`重命名为 `config.py`, 填入QQ号码和密码配置, 执行webqq.py脚本. 

# 更新
* 放弃原先的 pyxmpp2 mainloop 改为tornado
* 不在将验证图片放到网站上, 而是作为临时文件保存, 请使用图片查看器查看, 然后输入验证码
