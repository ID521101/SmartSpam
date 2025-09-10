# SmartSpam
智能评论过滤器，让机器人彻底远离你！（原作者：YoviSun）<br>
原作者发布地址：https://www.yovisun.com/archive/typecho-plugin-smartspam.html


增添违规屏蔽词文本,在prohibited_words.txt 中添加屏蔽词，一词一行！
**prohibited_words.txt** 中使用的屏蔽词来自 Sensitive-lexicon (中文敏感词库)——网易前端过滤敏感词库.txt
屏蔽词地址：https://github.com/konsheng/Sensitive-lexicon/tree/main/Vocabulary

## 历史版本

 * version 2.8.0 at 2025-09-10
 * 修复"邮箱关键词"设置后在删除造成无法评论的情况；新增了 prohibited_words.txt 文本，所有的屏蔽词放在文本中，"屏蔽昵称关键词操作"和"禁止词汇操作"共享一个文本。 by onemuggle.com 
 * 
 * version 2.7.0 at 2021-03-08
 * 添加对游客评论的处理；新增部分代码提升同接口插件间的兼容性。 by zezeshe.com
 * * version 2.6.0 at 2014-10-18
 * 添加对网址的检测
 * version 2.5.0 at 2014-08-30
 * 添加检测评论内容中是否包含文章标题
 * version 2.4.0 at 2014-08-27
 * 添加对于昵称关键词的检测，若昵称中含有某关键词，则评论失败
 * 添加对于邮箱地址的检测
 * version 2.3.0 at 2013-12-18
 * 添加对于昵称的长度检测，昵称的日文检测，网址判断操作
 * version 2.2.1 at 2013-12-04
 * 修改开启插件的默认选项为评论失败
 * version 2.2.0 at 2013-12-01
 * 添加禁止日文昵称的检测 by www.yovisun.com
 * version 2.1.0 at 2013-11-06
 * 添加禁止日文评论的检测 by www.yovisun.com
 * version 2.0.0 at 2013-06-02
 * 添加评论字符长度的检测 by www.yovisun.com
 * version 1.0.2 at 2010-05-16
 * 修正发表评论成功后，评论内容Cookie不清空的Bug
 * version 1.0.1 at 2009-11-29
 * 增加IP段过滤功能
 * version 1.0.0 at 2009-11-14
 * 实现评论内容按屏蔽词过滤功能
 * 实现过滤非主文评论功能
