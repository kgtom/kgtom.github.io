
将代码嵌入到 ghost后台 Blog Footer中。
~~~
<!-- Gitalk 评论 start  -->

<!-- Link Gitalk 的支持文件  -->
<link rel="stylesheet" href="https://unpkg.com/gitalk/dist/gitalk.css">
<script src="https://unpkg.com/gitalk@latest/dist/gitalk.min.js"></script> 
<div id="gitalk-container"></div>     <script type="text/javascript">
    var gitalk = new Gitalk({

    // gitalk的主要参数
		clientID: `xxxxxxx`,
		clientSecret: `xxxxxxxx`,
		repo: `kgtom.github.io`,
		owner: 'kgtom',
		admin: ['kgtom'],
		
    
    });
    gitalk.render('gitalk-container');
</script> 
<!-- Gitalk end -->

~~~
其中：
clientID、clientSecret [点击](https://github.com/settings/applications/new)申请即可。


>reference:
https://github.com/gitalk/gitalk#install
