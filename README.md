# 依赖
[redcarpet]()
# 重要文件说明
* _includes/header.html 引入的js和css文件管理
* _includes/sidebar.html 生成的文章餐单放在这里
* _includes/navbar.html 页面的顶部导航放在这里
* _includes/footer.html 页面的底部的展示栏
* _layouts/post.html 博客的模板
* _layouts/default.html 首页的模板

# 配置
_layouts/post.html 中需要配置自己的[disqus](https://disqus.com/)，申请自己的id，并替换掉如下代码:
```javascript
  (function() { // DON'T EDIT BELOW THIS LINE
		var d = document, s = d.createElement('script');

		s.src = '//cocorookie.disqus.com/embed.js';

		s.setAttribute('data-timestamp', +new Date());
		(d.head || d.body).appendChild(s);
		})();
		</script>
		<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>
```
