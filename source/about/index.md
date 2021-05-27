---
title: 这是关于
date: 2020-10-25 21:42:15
---


这里是 index_v2.js 版本,把协议改成了 https,这个是正常登录
<div id="SOHUCS"></div>



<script type="text/javascript">(function(){



  var appid = 'cytSyHmHo';



  var conf = 'prod_55b9562e2add3121059584fa71676433';



  var width = window.innerWidth || document.documentElement.clientWidth;



  if (width < 960) {



    var head = document.getElementsByTagName('head')[0]||document.head||document.documentElement;

    var script = document.createElement('script');

    script.type = 'text/javascript';

    script.charset = 'utf-8';

    script.id = 'changyan_mobile_js';

    script.src = 'https://changyan.sohu.com/upload/mobile/wap-js/changyan_mobile.js?client_id=' + appid + '&conf=' + conf;

    head.appendChild(script);



    } else { 

      var loadJs = function(d,a){

        var c=document.getElementsByTagName("head")[0]||document.head||document.documentElement;var b=document.createElement("script");b.setAttribute("type","text/javascript");b.setAttribute("charset","UTF-8");b.setAttribute("src",d);if(typeof a==="function"){if(window.attachEvent){b.onreadystatechange=function(){var e=b.readyState;if(e==="loaded"||e==="complete"){b.onreadystatechange=null;a()}}}else{b.onload=a}}c.appendChild(b)};loadJs("https://changyan.sohu.com/upload/changyan.js",function(){window.changyan.api.config({appid:appid,conf:conf})}); } })();</script>

</script><script type="text/javascript" src="http://static-1252921496.file.myqcloud.com/changyan-personalize/fluke/index_v2.js"></script>