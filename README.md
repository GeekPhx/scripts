# scripts
JavaScript Library

## jquery.backstretch.min.js使用说明:
* 引入jQuery文件
* 在body结束前添加如下代码:

` 
<script>
	$(function() {
		jQuery(document).ready(function() {
			$('body').backstretch([
				"assets/slides/tm-bg-slide-3.jpg", 
				"assets/slides/tm-bg-slide-2.jpg", 
				"assets/slides/tm-bg-slide-1.jpg"
				], {
				duration : 3200,
				fade : 1300
			});
		});
	})
</script>
` 
