fis-smarty
==========

百度前端集成框架 FIS 的前端模板语法插件


安装
------------

* __方法一__
	1. 下载
	2. 打开 Sublime Text 2 "Packages" 目录（"Preferences" -> "Browse Packages"）
	3. 将下载的整个文件夹放到上一步打开的文件夹

* __方法二（前提要安装了Sublime包管理工具）__
	1. Ctrl+Shift+P  =>  输入 `install package`， 按 `Enter`
	2. 稍等一会，弹出一个对话框， 输入 fis-smarty，按 `Enter`


使用 （Sinppets）
-------------

1.assign
>{% assign var="name" value=value scope=scope %}

2.block
>{% block name="blockname" %}
>	
>{% /block %}

3.comment
>{%* comment *%}

4.debug
>{% $variable|@debug_print_var %}

5.if
>{% if condition %}
>	
>{% /if %}

6.ifelse
>{% if condition %}
>	
>{% else %}
>	
>{% /if %}

7.newwidget
>{% widget var=$val %}
>	{%* html here *%}
>{% /widget %}

8.widget
>{% widget name="widget name" var=$val %}

9.smarty
>{% code %}