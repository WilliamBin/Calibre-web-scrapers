# Calibre-web-scrapers
Calibre中文刮削整理
## 新增中国国家图书馆元数据源插件
[中国国家图书馆ISBN Calibre Metadata 源插件]( [https://github.com/fugary/calibre-douban](https://github.com/DoiiarX/NLCISBNPlugin) )
## Calibre桌面版刮削
先用[fugary]( https://github.com/fugary )制作的 [NewDouban]( https://github.com/fugary/calibre-douban )批量下载元数据与封面  
再检查刚下载的元数据  
![image](https://user-images.githubusercontent.com/13869608/158048275-5460fc24-d2bb-4ba9-92ff-be063fac296c.png)  
部分元数据不对的在填入豆瓣 id，或者书的 isbn后  
左键单击填入剪切板内的isbn，右键单击后左键单击douban填入剪切板内的豆瓣 id  
![image](https://user-images.githubusercontent.com/13869608/158048325-fbdc9b11-656e-48dc-a277-de210ae82e8c.png)  
再用 [StevenBaby]( https://github.com/StevenBaby )的 [doubanbook](https://github.com/StevenBaby/tools/tree/master/calibre)批量下载元数据  
- 获取豆瓣id  
将书名粘贴到搜索框后，通过封面选对版本，再右键复制链接，粘贴链接后取//之间的数字就是豆瓣id  
![image](https://user-images.githubusercontent.com/13869608/158048361-d310397c-d2cd-4058-ac5f-a0195202f712.png)  
![image](https://user-images.githubusercontent.com/13869608/158048362-55f00a32-9e03-4b16-8185-a022c46e23ed.png)  
![image](https://user-images.githubusercontent.com/13869608/158048363-0bf86e84-05d2-4d3d-a1d1-31031559062c.png)  
  
豆瓣没有的去 [亚马逊电子书]( https://www.amazon.cn/dp )找到amazon_cn也就是ASIN  
![image](https://user-images.githubusercontent.com/13869608/158048384-e42af444-6cd8-42a5-9a1c-9bfb995e953d.png)  
然后用对应的插件下载元数据，很多的套装只能去亚马逊  
前两个地方都没有的去[Google图书]( https://books.google.com/ )找到isbn后通过对应插件下载元数据  
## calibre-web刮削
[fugary]( https://github.com/fugary )制作的 [calibre-web-douban-api]( https://github.com/fugary/calibre-web-douban-api)  
  
## 其他观察中的项目
[第三方豆瓣读书 api 接口]( https://github.com/acdzh/douban-book-api )  
[竹简——最全中文ISBN信息查询接口](https://github.com/qiaohaoforever/BambooIsbn )  
## 有更好的刮削方式和流程欢迎大家补充
