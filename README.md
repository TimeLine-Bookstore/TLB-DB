<html>
<style>
#url-type{color:#cccccc}
</style>
<body>
    <div style="text-align:center">
        <div id="url-type">
            <input type="radio" name="url-sel" value="author" onclick="document.getElementById('url-pre').innerHTML = ''; document.getElementById('url').size ='25';" checked>按文章名称搜索
        </div>
        <p><span id="url-pre" style="font-family:Consolas;font-size: 12.8px;color: #333;"> </span>
        <input type="text" id="url" name="url" placeholder="请输入…" size="24" ></p>
        <p>
            <button onclick="Go0()">搜索备份</button>
        </p>
    </div>
</body>
<script language="javascript">
    var keyWord;
function expand() {
    var urltype = document.getElementsByName('url-sel');
   if (urltype[0].checked) {
       keyWord = 'https://lest-day.github.io/TLB-DB/Timeline-Bookstore/' + keyWord + '.html' ;
   }

}
function Go0(){
keyWord=document.getElementById("url").value;
if (keyWord != "") {
    expand();
  var result=keyWord;
  window.open(result);
}
}
</script>
</html>
这是文章备份搜索工具，搜索内容输入格式：“文章分类/文章名称”,省略掉所有标点符号和“.html”,将空格位置替换为“-”。


> [TLB-DB备份区](https://github.com/lest-day/TLB-DB)
> ---
> 这是TLB维基的手动备份工具组区域，用于手动提取维基数据的数据库，由lest-day每周不定期做维护更新和清理操作。

除非另有说明，否则在此站点存储备份的文章和内容均来源于[TLB文学创作社区](https://timeline-bookstore.wikidot.com/)，且适用CC BY-SA 4.0授权协议

若原文不适用CC BY-SA 4.0授权协议，则默认适用于原文所使用的授权协议，原文链接均放置在页面首位。

除非特别说明，否则本站的已执行的功能性工具（包括但不限于搜索），均适用CC BY-SA 4.0授权协议。
