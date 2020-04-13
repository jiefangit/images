可道云静态文件CDN加速地址：https://cdn.jsdelivr.net/gh/jiefangit/images/list/kod/static/

配置setting_user.php 
配置cdn地址: 在config/下新建 setting_user.php文件;粘贴如下内容；(已存在则不需要新建)

<?php

$GLOBALS['config']['settings']['staticPath'] = "https://cdn.jsdelivr.net/gh/jiefangit/images/list/kod/static/";
