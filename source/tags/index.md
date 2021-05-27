---
title: 标签
date: 2020-10-25 21:42:15
---

index.js,没有替换协议之前，这里登录失败
<!-- 只需将下面代码放到希望展示的地方即可  -->
<!-- <a href="https://cy-cdn.kuaizhan.com/api/labs/hotnewswall/load?client_id=cyuwy52wp">畅言云评新闻墙</a> -->

去掉畅言云评头的版本
<!-- 代码1：放在页面需要展示的位置  -->
<!-- 如果您配置过sourceid，建议在div标签中配置sourceid、cid(分类id)，没有请忽略  -->
<div id="cyHotnewswall" role="cylabs" data-use="hotnewswall"></div>
<!-- 代码2：用来读取评论框配置，此代码需放置在代码1之后。 -->
<!-- 如果当前页面有评论框，代码2请勿放置在评论框代码之前。 -->
<!-- 如果页面同时使用多个实验室项目，以下代码只需要引入一次，只配置上面的div标签即可 -->
<!-- 如需修改默认配置，请到cy-cdn.kuaizhan.com后台进行配置 -->


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