# DayDayPoc-chrome漏洞指纹匹配插件上线啦!
## 插件功能
&ensp;&ensp;DayDayPoc指纹匹配插件是烽火台实验室开发的一款漏洞指纹匹配插件，可帮助用户检测访问的网站是否命中DayDayPoc的漏洞指纹。

## 插件安装方式
- 下载并解压插件，插件地址：
  
&ensp;&ensp;https://github.com/webraybtl/ddpoc-chrome

&ensp;&ensp;备注：chrome应用商店正在上线中，目前仅支持离线安装模式。

- 浏览器访问：chrome://extensions/ 并打开开发者模式

  <img width="640" alt="image" src="https://github.com/webraybtl/ddpoc-chrome/assets/11575908/3a8b11bd-86e0-4732-beda-7c2d981da4f3">
- 将解压好的ddpocchrome文件夹拖拽到所有扩展程序区域

  ![image](https://github.com/webraybtl/ddpoc-chrome/assets/11575908/f20e48ea-bb9a-41a9-8cd0-108d921e9dce)
- 将插件固定到右上角工具栏

  ![image](https://github.com/webraybtl/ddpoc-chrome/assets/11575908/a945c696-bcb2-4345-ba69-d779f0da6036)
  ![image](https://github.com/webraybtl/ddpoc-chrome/assets/11575908/41bf53ee-b032-41d5-8f7f-7b8598ef3d24)

## 插件使用方式
- 打开需要检测的网站，点击右上角插件图标

  <img width="640" alt="image" src="https://github.com/webraybtl/ddpoc-chrome/assets/11575908/6fcd2d9a-bb36-484e-a9f1-220f14ce40a1">

- 获取token并录入，需要登录https://www.ddpoc.com/绑定微信后，在个人中心查看，复制你的token

  ![image](https://github.com/webraybtl/ddpoc-chrome/assets/11575908/39579d9d-6b2c-4a2e-a4e6-47a7d24eb396)
- 录入token后，点击更新token即可对当前网页进行检测
  
  <img width="640" alt="image" src="https://github.com/webraybtl/ddpoc-chrome/assets/11575908/3b6c6cd9-5e46-4ba4-99de-66d9701d44f3">

## 注意事项
&ensp;&ensp;该插件仅检测网页命中的ddpoc的漏洞指纹，不会额外发送请求包，更不会实际进行poc探测。
