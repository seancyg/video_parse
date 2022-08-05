## 抖音无水印视频解析 API - 2022-7-28 更新  

![](https://www.cooluc.com/usr/uploads/2020/07/1407259818.jpg)  

### 抖音无水印视频解析 API  

#### API 地址  
```html
http://parse.seanshow.cn/?url=
```

#### 使用示例  

**http://parse.seanshow.cn/?url=视频分享链接**  

例如：
```html
http://parse.seanshow.cn/?url=https://v.douyin.com/2bkXBX5/
```

解析成功返回内容  
```javascript
{
    "video":"解析视频链接",
    "audio":"背景音乐链接",
    "nickname":"作者",
    "desc":"视频描述",
    "duration":"视频时长"
}
```

