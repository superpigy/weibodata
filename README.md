# 社交数据抓取

抓取的微博数据，开放给所有做社交网络分析的研究者，将持续更新。<br>
数据以sql文件打包，已包含表结构，直接在mysql 或者 mariadb中导入即可<br>
抓取时已将微博某些格式进行转换：<br>
  1. @username:content 转换为[MEMTION:XXX]:content, 手残抓取时拼错了大家见谅<br>
  2. 表情符号转换为[EMOTiCON:表情代码]<br>
  3. #专题#转换为[TOPIC:专题]<br>
直接用正则抽取需要信息<br>
 
## 表结构说明<br>
  自己看吧懒得写了<br>
  
## 未来工作<br>
  1. 加入API接口，数据量太大，上传缓慢<br>
  2. 加入更多其它社交媒体的数据<br>
