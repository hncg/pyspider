# spider
网络情感监控与预测系统，爬虫部分——Python实现。

## 主要功能
1. 多线程抓取
2. 反爬虫破解,智能重抓，防止重抓。
3. 分词，情感分析和入库，其中分词基于jieba分词库，情感词本体基于大连理工大学《文本情感语义分析》

### 目录结构
```
{
	"README.MD" : "README",
	"log" : "日志文件",
	"spider" : "主代码",
	"split" : "分词代码"
}
```
####其中log目录主要存放抛出的异常时的url，包括

lod.log——针对 404 ，503等错误
code.log ——针对encode("utf8")转换时的错误
...