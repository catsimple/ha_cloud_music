# 云音乐

在Home Assistant里使用的网易云音乐插件

> **指定ID播放**

- 播放网易云音乐歌单 `cloudmusic://163/playlist?id=25724904`
- 播放网易云音乐电台 `cloudmusic://163/radio/playlist?id=1008`
- 播放网易云音乐歌手 `cloudmusic://163/artist/playlist?id=2116`
- 播放喜马拉雅专辑 `cloudmusic://xmly/playlist?id=258244`

> **指定URL播放**
- [x] `cloudmusic://play/url?url=流媒体链接&song=歌曲名&singer=歌手&picurl=缩略图链接`

> **搜索播放**

- [x] 音乐搜索播放 `cloudmusic://play/song?kv=关键词`
      使用'歌名-歌手'的格式搜索会获得更匹配的搜索结果(使用了UNM的情况下)
- [x] 歌手搜索播放 `cloudmusic://play/singer?kv=关键词`
- [x] 歌单搜索播放 `cloudmusic://play/list?kv=关键词`
- [x] 电台搜索播放 `cloudmusic://play/radio?kv=关键词`
- [ ] 喜马拉雅搜索播放 `cloudmusic://play/xmly?kv=关键词`
- [ ] FM搜索播放 `cloudmusic://play/fm?kv=关键词`
- [x] （不推荐）第三方音乐搜索播放 `cloudmusic://search/play?kv=关键词`

> **登录后播放**
- [x] 每日推荐 `cloudmusic://163/my/daily`
- [x] 我喜欢的音乐 `cloudmusic://163/my/ilike`
- [x] 私人FM(旧版接口) `cloudmusic://163/my/play_old_personal_fm` 
- [x] 私人FM(新版接口) `cloudmusic://163/my/play_new_personal_fm`私人FM模式（新版接口）`mode`可选参数如下`DEFAULT, FAMILIAR, EXPLORE, SCENE_RCMD` 当`mode`为`SCENE_RCMD`时`submode`可选参数如下`EXERCISE, FOCUS, NIGHT_EMO`  如`cloudmusic://163/my/play_new_personal_fm?mode=SCENE_RCMD&submode=FOCUS` 
      
## 关联项目

- https://github.com/shaonianzhentan/cloud_music_mpd
- https://github.com/shaonianzhentan/ha_windows

## 如果这个项目对你有帮助，请我喝杯<del style="font-size: 14px;">咖啡</del>奶茶吧😘
|支付宝|微信|
|---|---|
<img src="https://ha.jiluxinqing.com/img/alipay.png" align="left" height="160" width="160" alt="支付宝" title="支付宝">  |  <img src="https://ha.jiluxinqing.com/img/wechat.png" align="left" height="160" width="160" alt="微信支付" title="微信">

#### 关注我的微信订阅号，了解更多HomeAssistant相关知识
<img src="https://ha.jiluxinqing.com/img/wechat-channel.png" height="160" alt="HomeAssistant家庭助理" title="HomeAssistant家庭助理">
