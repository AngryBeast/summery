#Github学习笔记
##基础篇
* 下载Git本地端
* 解决Github图片显示不出的问题
  > https://www.cnblogs.com/jooy/p/12090882.html
  > https://www.cnblogs.com/qiansm/p/12095047.html

* 使用MarkdownPad2进行编辑md文件,使用方法参考CSDN
   > 教程地址-> (https://blog.csdn.net/renlzrz/article/details/83545521)
   
   或[点击此处](https://blog.csdn.net/renlzrz/article/details/83545521)

* Github每个项目必须带有README.md文件以便对项目进行描述
### 具体使用
> [教程地址](https://blog.csdn.net/ouyang______/article/details/102736101?ops_request_misc=%7B%22request_id%22%3A%22158304591419724839225978%22%2C%22scm%22%3A%2220140713.130056874..%22%7D&request_id=158304591419724839225978&biz_id=0&utm_source=distribute.pc_search_result.none-task)

* 在Github上先创建一个仓库
* 在本地需要上传的文件夹中右键选择git base here
* 输入 ssh -T git@github.com  
  若出现下列提示则成功
  >You’ve successfully authenticated, but GitHub does not provide shell access
  
* git config –-global user.name “你github的名字”
* git config –-global user.email “你的github邮箱地址” 
* 在Github仓库中找到对应的地址  格式为
	>https://github.com/用户名/仓库名.git
	
	>例如: https://github.com/AngryBeast/summery.git

* git add README.md (文件)
* git commit -m "注释"
* git push origin master
