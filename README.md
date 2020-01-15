
<!DOCTYPE html>
<!--[if IE 9 ]>    <html dir="ltr" lang="en-US" class="ie9"> <![endif]-->
<!--[if (gte IE 10)|(gt IEMobile 7)|!(IEMobile)|!(IE)]><!--><html dir="ltr" lang="en-US"><!--<![endif]-->
  <head>
<!-- application -->
    <script type="text/javascript" src="//code.jquery.com/jquery-1.11.3.min.js"></script>
    <!-- Google Tag Manager -->
<script>
  (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
  new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
  j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
  'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
  })(window,document,'script','dataLayer','GTM-NL4KN8G');
</script>
<!-- End Google Tag Manager -->

<!-- Google Optimize Anti-flicker snippet -->
<style>.async-hide { opacity: 0 !important} </style>

<script>
  (function(a,s,y,n,c,h,i,d,e){s.className+=' '+y;h.start=1*new Date;
  h.end=i=function(){s.className=s.className.replace(RegExp(' ?'+y),'')};
  (a[n]=a[n]||[]).hide=h;setTimeout(function(){i();h.end=null},c);h.timeout=c;
  })(window,document.documentElement,'async-hide','dataLayer',4000,
  {'GTM-WDFZS8D':true});
</script>
<!-- End Google Optimize Anti-flicker snippet -->

<!-- Google Analytics w Optimize and Enhanced Ecommerce  -->
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-136373-5', 'auto');
  ga('require', 'GTM-WDFZS8D');  // Optimize
  ga('require', 'ec');           // Enhanced Ecommerce
  ga('send', 'pageview');

</script>
<!-- End Google Analytics -->
    <meta charset="UTF-8">
<script>window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","errorBeacon":"bam.nr-data.net","licenseKey":"1b930da09b","applicationID":"22494915","transactionName":"cFkNREpaWA9dF0pBVlRTEB9bXVUTTAAXbkRWRApVS2pXAlsNAFU=","queueTime":0,"applicationTime":751,"agent":""}</script>
<script>(window.NREUM||(NREUM={})).loader_config={licenseKey:"1b930da09b",applicationID:"22494915"};window.NREUM||(NREUM={}),__nr_require=function(n,e,t){function r(t){if(!e[t]){var i=e[t]={exports:{}};n[t][0].call(i.exports,function(e){var i=n[t][1][e];return r(i||e)},i,i.exports)}return e[t].exports}if("function"==typeof __nr_require)return __nr_require;for(var i=0;i<t.length;i++)r(t[i]);return r}({1:[function(n,e,t){function r(){}function i(n,e,t){return function(){return o(n,[u.now()].concat(f(arguments)),e?null:this,t),e?void 0:this}}var o=n("handle"),a=n(4),f=n(5),c=n("ee").get("tracer"),u=n("loader"),s=NREUM;"undefined"==typeof window.newrelic&&(newrelic=s);var p=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit","addRelease"],d="api-",l=d+"ixn-";a(p,function(n,e){s[e]=i(d+e,!0,"api")}),s.addPageAction=i(d+"addPageAction",!0),s.setCurrentRouteName=i(d+"routeName",!0),e.exports=newrelic,s.interaction=function(){return(new r).get()};var m=r.prototype={createTracer:function(n,e){var t={},r=this,i="function"==typeof e;return o(l+"tracer",[u.now(),n,t],r),function(){if(c.emit((i?"":"no-")+"fn-start",[u.now(),r,i],t),i)try{return e.apply(this,arguments)}catch(n){throw c.emit("fn-err",[arguments,this,n],t),n}finally{c.emit("fn-end",[u.now()],t)}}}};a("actionText,setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(n,e){m[e]=i(l+e)}),newrelic.noticeError=function(n,e){"string"==typeof n&&(n=new Error(n)),o("err",[n,u.now(),!1,e])}},{}],2:[function(n,e,t){function r(n,e){var t=n.getEntries();t.forEach(function(n){"first-paint"===n.name?a("timing",["fp",Math.floor(n.startTime)]):"first-contentful-paint"===n.name&&a("timing",["fcp",Math.floor(n.startTime)])})}function i(n){if(n instanceof c&&!s){var e,t=Math.round(n.timeStamp);e=t>1e12?Date.now()-t:f.now()-t,s=!0,a("timing",["fi",t,{type:n.type,fid:e}])}}if(!("init"in NREUM&&"page_view_timing"in NREUM.init&&"enabled"in NREUM.init.page_view_timing&&NREUM.init.page_view_timing.enabled===!1)){var o,a=n("handle"),f=n("loader"),c=NREUM.o.EV;if("PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver){o=new PerformanceObserver(r);try{o.observe({entryTypes:["paint"]})}catch(u){}}if("addEventListener"in document){var s=!1,p=["click","keydown","mousedown","pointerdown","touchstart"];p.forEach(function(n){document.addEventListener(n,i,!1)})}}},{}],3:[function(n,e,t){function r(n,e){if(!i)return!1;if(n!==i)return!1;if(!e)return!0;if(!o)return!1;for(var t=o.split("."),r=e.split("."),a=0;a<r.length;a++)if(r[a]!==t[a])return!1;return!0}var i=null,o=null,a=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var f=navigator.userAgent,c=f.match(a);c&&f.indexOf("Chrome")===-1&&f.indexOf("Chromium")===-1&&(i="Safari",o=c[1])}e.exports={agent:i,version:o,match:r}},{}],4:[function(n,e,t){function r(n,e){var t=[],r="",o=0;for(r in n)i.call(n,r)&&(t[o]=e(r,n[r]),o+=1);return t}var i=Object.prototype.hasOwnProperty;e.exports=r},{}],5:[function(n,e,t){function r(n,e,t){e||(e=0),"undefined"==typeof t&&(t=n?n.length:0);for(var r=-1,i=t-e||0,o=Array(i<0?0:i);++r<i;)o[r]=n[e+r];return o}e.exports=r},{}],6:[function(n,e,t){e.exports={exists:"undefined"!=typeof window.performance&&window.performance.timing&&"undefined"!=typeof window.performance.timing.navigationStart}},{}],ee:[function(n,e,t){function r(){}function i(n){function e(n){return n&&n instanceof r?n:n?c(n,f,o):o()}function t(t,r,i,o){if(!d.aborted||o){n&&n(t,r,i);for(var a=e(i),f=v(t),c=f.length,u=0;u<c;u++)f[u].apply(a,r);var p=s[y[t]];return p&&p.push([b,t,r,a]),a}}function l(n,e){h[n]=v(n).concat(e)}function m(n,e){var t=h[n];if(t)for(var r=0;r<t.length;r++)t[r]===e&&t.splice(r,1)}function v(n){return h[n]||[]}function g(n){return p[n]=p[n]||i(t)}function w(n,e){u(n,function(n,t){e=e||"feature",y[t]=e,e in s||(s[e]=[])})}var h={},y={},b={on:l,addEventListener:l,removeEventListener:m,emit:t,get:g,listeners:v,context:e,buffer:w,abort:a,aborted:!1};return b}function o(){return new r}function a(){(s.api||s.feature)&&(d.aborted=!0,s=d.backlog={})}var f="nr@context",c=n("gos"),u=n(4),s={},p={},d=e.exports=i();d.backlog=s},{}],gos:[function(n,e,t){function r(n,e,t){if(i.call(n,e))return n[e];var r=t();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(n,e,{value:r,writable:!0,enumerable:!1}),r}catch(o){}return n[e]=r,r}var i=Object.prototype.hasOwnProperty;e.exports=r},{}],handle:[function(n,e,t){function r(n,e,t,r){i.buffer([n],r),i.emit(n,e,t)}var i=n("ee").get("handle");e.exports=r,r.ee=i},{}],id:[function(n,e,t){function r(n){var e=typeof n;return!n||"object"!==e&&"function"!==e?-1:n===window?0:a(n,o,function(){return i++})}var i=1,o="nr@id",a=n("gos");e.exports=r},{}],loader:[function(n,e,t){function r(){if(!x++){var n=E.info=NREUM.info,e=l.getElementsByTagName("script")[0];if(setTimeout(s.abort,3e4),!(n&&n.licenseKey&&n.applicationID&&e))return s.abort();u(y,function(e,t){n[e]||(n[e]=t)}),c("mark",["onload",a()+E.offset],null,"api");var t=l.createElement("script");t.src="https://"+n.agent,e.parentNode.insertBefore(t,e)}}function i(){"complete"===l.readyState&&o()}function o(){c("mark",["domContent",a()+E.offset],null,"api")}function a(){return O.exists&&performance.now?Math.round(performance.now()):(f=Math.max((new Date).getTime(),f))-E.offset}var f=(new Date).getTime(),c=n("handle"),u=n(4),s=n("ee"),p=n(3),d=window,l=d.document,m="addEventListener",v="attachEvent",g=d.XMLHttpRequest,w=g&&g.prototype;NREUM.o={ST:setTimeout,SI:d.setImmediate,CT:clearTimeout,XHR:g,REQ:d.Request,EV:d.Event,PR:d.Promise,MO:d.MutationObserver};var h=""+location,y={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-1158.min.js"},b=g&&w&&w[m]&&!/CriOS/.test(navigator.userAgent),E=e.exports={offset:f,now:a,origin:h,features:{},xhrWrappable:b,userAgent:p};n(1),n(2),l[m]?(l[m]("DOMContentLoaded",o,!1),d[m]("load",r,!1)):(l[v]("onreadystatechange",i),d[v]("onload",r)),c("mark",["firstbyte",f],null,"api");var x=0,O=n(6)},{}],"wrap-function":[function(n,e,t){function r(n){return!(n&&n instanceof Function&&n.apply&&!n[a])}var i=n("ee"),o=n(5),a="nr@original",f=Object.prototype.hasOwnProperty,c=!1;e.exports=function(n,e){function t(n,e,t,i){function nrWrapper(){var r,a,f,c;try{a=this,r=o(arguments),f="function"==typeof t?t(r,a):t||{}}catch(u){d([u,"",[r,a,i],f])}s(e+"start",[r,a,i],f);try{return c=n.apply(a,r)}catch(p){throw s(e+"err",[r,a,p],f),p}finally{s(e+"end",[r,a,c],f)}}return r(n)?n:(e||(e=""),nrWrapper[a]=n,p(n,nrWrapper),nrWrapper)}function u(n,e,i,o){i||(i="");var a,f,c,u="-"===i.charAt(0);for(c=0;c<e.length;c++)f=e[c],a=n[f],r(a)||(n[f]=t(a,u?f+i:i,o,f))}function s(t,r,i){if(!c||e){var o=c;c=!0;try{n.emit(t,r,i,e)}catch(a){d([a,t,r,i])}c=o}}function p(n,e){if(Object.defineProperty&&Object.keys)try{var t=Object.keys(n);return t.forEach(function(t){Object.defineProperty(e,t,{get:function(){return n[t]},set:function(e){return n[t]=e,e}})}),e}catch(r){d([r])}for(var i in n)f.call(n,i)&&(e[i]=n[i]);return e}function d(e){try{n.emit("internal-error",e)}catch(t){}}return n||(n=i),t.inPlace=u,t.flag=a,t}},{}]},{},["loader"]);</script>
    <meta name="viewport"         content="width=device-width, initial-scale=1">
    <meta name="format-detection" content="telephone=no">

    <meta name="description" content="Read Boku no Hero Academia | The world&#39;s most popular manga! Read free or become a member. Start your free trial today! | My Hero Academia -  Midoriya inherits the superpower of the world’s greatest hero, but greatness won’t come easy.">

    <title>VIZ | Read My Hero Academia Manga Free - Official Shonen Jump From Japan</title>

<script type="text/javascript">
function cl(arg) {  }
</script>


      <link rel="canonical" href="https://www.viz.com/shonenjump/chapters/my-hero-academia">


    <link rel="apple-touch-icon" sizes="180x180" href="/favicon/apple-touch-icon.png?v=47MPqANpyj">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon/favicon-32x32.png?v=47MPqANpyj">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon/favicon-16x16.png?v=47MPqANpyj">
<link rel="manifest" href="/favicon/manifest.json?v=47MPqANpyj" crossorigin="use-credentials">
<link rel="mask-icon" href="/favicon/safari-pinned-tab.svg?v=47MPqANpyj" color="#ff0000">
<link rel="shortcut icon" href="/favicon/favicon.ico?v=47MPqANpyj">
<meta name="msapplication-config" content="/favicon/browserconfig.xml?v=47MPqANpyj">
<meta name="theme-color" content="#ff0000">



    <link rel="stylesheet" media="all" href="https://assets.viz.com/assets/manifest-viz-ui-46301224aa52a20ce60d3181ad84aa1920d5434d2a01cff01eab01ce4cccdb97.css" />

    <script type="text/javascript">
      // Picture element HTML5 shiv
      document.createElement("picture");
        var accountSource = "wsj_web";
    </script>


    <script src="https://assets.viz.com/assets/manifest-picturefill-251915c1c5c28dce5fe695c7b06042b06148adf01b169726c36bf677baebd29a.js" async="async"></script>
    <script src="https://assets.viz.com/assets/manifest-viz-common-8df70a13ed2ec1f34d3e261f538462e0fcb967efef9c27c92c1e5acd4a0b8004.js"></script>
    <script src="https://assets.viz.com/assets/manifest-viz-ui-78f129a749f864fd4a1fe86f2ac99e10d521534e26f88b937cbaeff219aad2d2.js"></script>

    <script src="https://www.gstatic.com/firebasejs/7.2.1/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/7.2.1/firebase-auth.js"></script>
<script src="https://www.gstatic.com/firebasejs/7.2.1/firebase-firestore.js"></script>

<script type="text/javascript">
// Initialize Firebase
firebase.initializeApp({
  apiKey:            "AIzaSyBSJhex6FCiVd84KIazrliP0HKELIKSnv4",
  authDomain:        "vizmule.firebaseapp.com",
  databaseURL:       "https://vizmule.firebaseio.com",
  projectId:         "vizmule",
  storageBucket:     "vizmule.appspot.com",
  messagingSenderId: "381084636812"
});
// To be used in FireStoreWrap to dis-allow initalization for any unrecognized collections (don't create garbage entries by typos)
var fs_collections = ['manga'];
</script>

<script src="https://assets.viz.com/assets/manifest-viz-firebase-1b97b139cd6b0d1409b09cdadc950f93ecfad142502b5fc6b8142a8433ddc5ae.js"></script>


    <!-- Facebook Pixel Code -->
<script>
!function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;
n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,
document,'script','https://connect.facebook.net/en_US/fbevents.js');

fbq('init', '1691826154417019');
fbq('track', "PageView");</script>
<noscript>
<img height="1" width="1" style="display:none" src="https://www.facebook.com/tr?id=1691826154417019&ev=PageView&noscript=1"/>
</noscript>
<!-- End Facebook Pixel Code -->

    <!-- Pinterest Pixel Base Code -->
<script type="text/javascript">
  !function(e){if(!window.pintrk){window.pintrk=function(){
  window.pintrk.queue.push(Array.prototype.slice.call(arguments))};var
    n=window.pintrk;n.queue=[],n.version="3.0";var
    t=document.createElement("script");t.async=!0,t.src=e;var
    r=document.getElementsByTagName("script")[0];
    r.parentNode.insertBefore(t,r)}}("https://s.pinimg.com/ct/core.js");
  pintrk('load', '2613740785131' );
  pintrk('page');
</script>
<noscript>
  <img height="1" width="1" style="display:none;" alt="" 
    src="https://ct.pinterest.com/v3/?tid=&noscript=1" />
</noscript>
<!-- End Pinterest Pixel Base Code -->

    <script type="text/javascript">
setTimeout(function(){var a=document.createElement("script");
var b=document.getElementsByTagName("script")[0];
a.src=document.location.protocol+"//script.crazyegg.com/pages/scripts/0062/6851.js?"+Math.floor(new Date().getTime()/3600000);
a.async=true;a.type="text/javascript";b.parentNode.insertBefore(a,b)}, 1);
</script>
  </head>

  <body  style="background-color: #444; background-image: url('https://de7i3bh7bgh0d.cloudfront.net/wsj-bg-smoketile.jpg');">
      <header id="site-header" role="banner" class="o_site-header bg-trans-white">

  <div id="fan-favorites" class="o_fan-favorites bg-off-black type-sm disp-n--nl">
    <div class="o_fan-favorites-row row nowrap">
      <h2 class="disp-ib mar-r-md color-mid-gray">Manga &amp; Anime Favorites</h2>
      <ul class="disp-ib">
          <li class="disp-ib mar-r-md"><a href="/sailor-moon">Sailor Moon</a></li>
          <li class="disp-ib mar-r-md"><a href="/boruto">Boruto</a></li>
          <li class="disp-ib mar-r-md"><a href="/demon-slayer-kimetsu-no-yaiba">Demon Slayer</a></li>
          <li class="disp-ib mar-r-md"><a href="/my-hero-academia">My Hero Academia</a></li>
          <li class="disp-ib mar-r-md"><a href="/naruto">Naruto</a></li>
          <li class="disp-ib mar-r-md"><a href="/pokemon">Pokémon</a></li>
          <li class="disp-ib mar-r-md"><a href="/one-punch-man">One-Punch Man</a></li>
          <li class="disp-ib mar-r-md"><a href="/shonenjump">Free Manga for All!</a></li>
          <li class="disp-ib mar-r-md"><a href="/products/gomi-no-sensei" rel="nofollow" style="display: none" aria-hidden="true">Gomi</a></li>
      </ul>
    </div>
  </div>


  <div id="header-container" class="row flex flex-justify">

    <h1 class="o_logo-top bg-red flex g-3--lg g-omega--lg">
      <span class="color-white type-sm--md type-bs weight-bold pos-r">
        <a href="/" class="o_logo-img"><img alt="VIZ Media: The world’s most popular anime, manga and more!" src="https://assets.viz.com/assets/logo@2x-b76f649f933ea15f45147ff5445a2501c85c7f863ba0aba5ea7bec93c3272cc6.png" />

</a>
      </span>
    </h1>

    <a href="javascript:void(0)" data-nav-open class="nav-btn nav-btn--center color-off-black"><i class="icon-menu"></i><span>Menu</span></a>

    <nav id="nav-container" data-nav-state="closed" role="navigation" class="o_nav-container">
      <a href="javascript:void(0)" data-nav-close class="nav-btn color-white pad-y-sm mar-y-rg"><i class="icon-close"></i><span>Dismiss</span></a>

      <ul id="primary-nav" class="o_primary-nav type-md style-caps weight-bold mar-y-md mar-y-0--lg">
          <li class="o_primary-nav-item disp-ib--lg mar-r-md">
            <a class="o_primary-nav-link" href="/read">Read</a>
          </li>
          <li class="o_primary-nav-item disp-ib--lg mar-r-md">
            <a class="o_primary-nav-link" href="/watch">Watch</a>
          </li>
          <li class="o_primary-nav-item active disp-ib--lg mar-r-md">
            <a class="o_primary-nav-link" href="/shonenjump">Shonen Jump</a>
          </li>
          <li class="o_primary-nav-item disp-ib--lg mar-r-md">
            <a class="o_primary-nav-link" href="/community">Community</a>
          </li>
          <li class="o_primary-nav-item disp-ib--lg">
            <a class="o_primary-nav-link" href="/calendar">Calendar</a>
          </li>
      </ul>

      <div id="site-search" class="o_site-search float-r--lg">
        <!-- header search bar -->
        <form action="/search" method="GET">
          <input name="search" type="search" class="o_search-ac o_site-search-field" placeholder="Find a title or a character…" autocomplete="off">
          <button type="submit" class="o_site-search-btn"><i class="icon-search"></i></button>
        </form>
      </div>

      <div id="fan-favorites-small" class="o_fan-favorites-small disp-n--lg type-sm mar-y-md mar-y-0--lg">
          <div class="mar-b-rg"><a href="/shonenjump">Free Manga for All!</a></div>
        <ul class="list-unmarked line-tight">
            <li class="mar-b-rg"><a href="/sailor-moon">Sailor Moon</a></li>
            <li class="mar-b-rg"><a href="/boruto">Boruto</a></li>
            <li class="mar-b-rg"><a href="/demon-slayer-kimetsu-no-yaiba">Demon Slayer</a></li>
            <li class="mar-b-rg"><a href="/my-hero-academia">My Hero Academia</a></li>
            <li class="mar-b-rg"><a href="/naruto">Naruto</a></li>
            <li class="mar-b-rg"><a href="/pokemon">Pokémon</a></li>
            <li class="mar-b-rg"><a href="/one-punch-man">One-Punch Man</a></li>
        </ul>
      </div>

      <ul id="utility-nav" class="o_utility-nav type-rg mar-t-rg mar-b-xl mar-t-md mar-t-sm--lg">
        <li class="o_account-links disp-bl disp-ib--lg mar-b-md mar-b-0--lg">
        </li>
      </ul>

    </nav>
  </div>

</header>


    <script src="https://assets.viz.com/assets/manifest-viz-property-847982a46bced20f734f51d6b060dade9fc864fad2865d731cd2c4a86fcbe886.js"></script>
<script type="text/javascript">
  var series_title   = "My Hero Academia", 
      followableType = "chapter_series",
      followableID   = 399,
      followLabel    = series_title + " Chapter List",
      followPage     = "chapter series",
      followMsg      = series_title + " chapters";
</script>

  <div id="hero" class="o_hero">
    <img class="o_hero-media" src="https://dw9to29mmj727.cloudfront.net/promo/2016/5344-SeriesHeaders_MHA_v2_2000x800.jpg">
  </div>

  <div id="announcement_215" class="announcement o_internal-promo-trackable" style="display:none;position:relative;">
      <div class="announcement_txt">                  <section class="bg-off-black color-off-white pad-y-md type-sm type-rg--md type-center">
<div class="row"><a class="o_a-url color-off-white hover-red" href="/sj-offer"><strong class="o_a-hdr">Join Shonen Jump and unlock the digital vault of 10,000+ chapters!</strong></a>&nbsp;<span class="o_a-body" style="display: none;"></span></div>
<script type="text/javascript">
  $(document).on("post_account_links", function() { if (is_wsj_subscriber) { $("#announcement_215").hide(); }});
</script>
</section>
                </div>
  </div>
  <script type="text/javascript">
    $(document).ready(function(){
      var announcementToShow = $("#announcement_215");

      if (typeof(deactivate_announcements) !== 'undefined' && deactivate_announcements) {
        announcementToShow.hide();

      } else {
        $(".hide_announcement", announcementToShow).click(function() {
            VizAnnouncement.markHidden(215);
          announcementToShow.slideUp("fast");
        });
        VizAnnouncement.runIfVisible(215, function(isVisible) {
          if (isVisible) { announcementToShow.slideDown("fast"); }
        });
      }
    }); // document.ready

      var announcementPosition = "Read My Hero Academia Manga Free - Official Shonen Jump From Japan";

      dataLayer.push({
        'ecommerce': {
          'promoView': {
            'promotions': [
             {
              'id': 'announcement_215',
              'name': 'SJ Page Launch 2018',
              'creative': 'pencil',
              'position': announcementPosition
             }]
          }
        }
      });

      $(document).ready(function(){

        $(document).on("click", "#announcement_215 a:not(.hide_announcement)", function(e) {
          e.preventDefault();
          var href = $(this).attr("href");

          ga('ec:addPromo', {
            'id': 'announcement_215',
            'name': 'SJ Page Launch 2018',
            'creative': 'pencil',
            'position': announcementPosition
          });
          ga('ec:setAction', 'promo_click');
          ga('send', 'event', 'Internal Promotions', 'click', 'SJ Page Launch 2018', {
            hitCallback: function() {
              document.location = href;
            }
          });
          Tracking.sendEvent({"category":"Announcement","action":"SJ Page Launch 2018","label":"title"});

        }); // on.click
      }); // document.ready
  </script>


<div class="bg-off-white row-nopad overflow-hide">

  <section id="series-intro" class="row mar-t-rg">
    <div class="clearfix mar-t-md mar-b-lg">
      

<script type="text/javascript">
  $(document).ready(function() {
    $(".sub-nav-select select").change(function() {
      var target = $(this).val();
      if (target && target != 'na' && target != window.location.href) {
        window.location.href = $(this).val();
      }
    });
  });
</script>

<div class="sub-nav-container flex color-mid-gray">
  <ul class="sub-nav-list list-unmarked list-divided flex-width-1 h-scroll">
    <li><a href="/shonenjump" class="active">Shonen Jump</a></li>
      <li><a href="/shonen-jump-chapter-schedule" class="active">Chapter Schedule</a></li>
    <li><a href="/sj-featured" class="active">Comment</a></li>
    <li><a href="/blog/shonen-jump" class="active">Blog</a></li>
    <li><a href="/calendar" class="active">New Volumes</a></li>
  </ul>
  <span class="sub-nav-select select-wrapper flex-width-1 mar-b-sm">
    <select>
        <option selected value="na">Series</option>
      <option value="/shonenjump">Shonen Jump</option>
        <option value="/shonen-jump-chapter-schedule">Chapter Schedule</option>
      <option value="/sj-featured">Comment</option>
      <option value="/blog/shonen-jump">Blog</option>
      <option value="/calendar">New Volumes</option>
    </select>
  </span>
</div>

      <h2 class="type-lg type-xl--md type-xxl--lg line-solid weight-bold style-caps mar-b-rg">My Hero Academia</h2>
        <h4 class="line-solid type-md type-lg--md mar-t-rg"> Midoriya inherits the superpower of the world’s greatest hero, but greatness won’t come easy.</h4>
    </div>

      <div class="type-rg">
          <span class="disp-bl--bm mar-b-md">Created by Kohei Horikoshi</span>
      </div>


      <div class="mar-b-md mar-t-lg pos-r">
        <a href="javascript:void('Follow series')" class="o_requires-login o_follow-link btn-primary-dark mar-b-md type-rg mar-r-sm disp-n"
   clickfn="Following.change(followableType, followableID, 1, followPage, followMsg, followLabel);"
   data-login-msg="Log in to follow My Hero Academia chapters!"
   data-signup-msg="To follow My Hero Academia chapters, sign up for a VIZ account"
   data-confirmation-msg="You are now following My Hero Academia chapters"
   data-signup-context="follow-chapter-series-399"
   data-show-signup="1"
   data-follow-state="off" >
   <i class="icon-like"></i>&nbsp;
Follow series</a>

      </div>
  </section>

        <section class="section_chapters mar-b-xl bg-off-white" id="section0">

    <!-- Load chapter series tile rows -->

      <div class="row">
          <script type="text/javascript">
            $(document).ready(function(){ initProductSort(); });
          </script>
          <div class="clear-b mar-b-sm pos-r">
              <div class="o_sort-controls disp-n float-r--lg type-rg mar-t-0 mar-b-rg mar-t-md--lg mar-b-0--lg mar-x-0 mar-x-xl--md mar-x-xxl--lg">
                <ul data-sort-group="sort" class="list-unmarked list-inline list-divided h-scroll line-caption float-r--lg color-mid-gray type-sm type-rg--lg">
                  <li><a data-sort="za" data-sort-state="on"  class="color-red"                     href="javascript:void('sort 9-0')"><!--&darr;-->&#8675;9-1</a></li>
                  <li><a data-sort="az" data-sort-state="off" class="color-mid-gray hover-dark-red" href="javascript:void('sort 0-9')"><!--&uarr;-->1-9&#8675;</a></li>
                </ul>
              </div>
              <div class="clear-b"></div>
          </div>
        <div class="o_sort_container mar-x-0 mar-x-xl--md mar-x-xxl--lg clearfix">
            <div class="section_future_chapter o_sortable brdr-dotted-lid"
                 data-sort-recent="66"
                 data-sort-alpha-label="myheroacademia"
                 data-sort-alpha-num="10000000">
              <div class="type-center type-sm line-caption pad-y-rg pad-y-md--lg type-rg--lg">
                New chapter coming in 4 days!
              </div>
            </div>
          
<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="1"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2560">

    <a href="/shonenjump/my-hero-academia-chapter-256/chapter/19820?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-256/chapter/19820?action=read"
       class="o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">January  6, 2020</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19820">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 256</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-white bg-green  hover-bg-green"><span style="white-space:nowrap;"><i class="icon-eye"     style="margin-right:5px;"></i>FREE</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="2"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2550">

    <a href="/shonenjump/my-hero-academia-chapter-255/chapter/19779?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-255/chapter/19779?action=read"
       class="o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">December 22, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19779">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 255</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-white bg-green  hover-bg-green"><span style="white-space:nowrap;"><i class="icon-eye"     style="margin-right:5px;"></i>FREE</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="3"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2540">

    <a href="/shonenjump/my-hero-academia-chapter-254/chapter/19758?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-254/chapter/19758?action=read"
       class="o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">December 15, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19758">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 254</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-white bg-green  hover-bg-green"><span style="white-space:nowrap;"><i class="icon-eye"     style="margin-right:5px;"></i>FREE</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="4"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2530">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-253/chapter/19693?action=read',targetTitle:'My Hero Academia, Chapter 253'};wsjModalPromoId='wsj_subscribe_modal_19693';wsjModalSource='My Hero Academia, Chapter 253';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19693,'/shonenjump/my-hero-academia-chapter-253/chapter/19693?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">December  8, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19693">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 253</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="5"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2520">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-252/chapter/19663?action=read',targetTitle:'My Hero Academia, Chapter 252'};wsjModalPromoId='wsj_subscribe_modal_19663';wsjModalSource='My Hero Academia, Chapter 252';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19663,'/shonenjump/my-hero-academia-chapter-252/chapter/19663?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">December  1, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19663">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 252</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="6"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2510">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-251/chapter/19634?action=read',targetTitle:'My Hero Academia, Chapter 251'};wsjModalPromoId='wsj_subscribe_modal_19634';wsjModalSource='My Hero Academia, Chapter 251';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19634,'/shonenjump/my-hero-academia-chapter-251/chapter/19634?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">November 24, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19634">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 251</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="7"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2500">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-250/chapter/19566?action=read',targetTitle:'My Hero Academia, Chapter 250'};wsjModalPromoId='wsj_subscribe_modal_19566';wsjModalSource='My Hero Academia, Chapter 250';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19566,'/shonenjump/my-hero-academia-chapter-250/chapter/19566?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">November 17, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19566">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 250</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="8"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2490">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-249/chapter/19447?action=read',targetTitle:'My Hero Academia, Chapter 249'};wsjModalPromoId='wsj_subscribe_modal_19447';wsjModalSource='My Hero Academia, Chapter 249';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19447,'/shonenjump/my-hero-academia-chapter-249/chapter/19447?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">November 10, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19447">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 249</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="9"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2480">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-248/chapter/19425?action=read',targetTitle:'My Hero Academia, Chapter 248'};wsjModalPromoId='wsj_subscribe_modal_19425';wsjModalSource='My Hero Academia, Chapter 248';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19425,'/shonenjump/my-hero-academia-chapter-248/chapter/19425?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">October 27, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19425">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 248</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="10"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2470">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-247/chapter/19402?action=read',targetTitle:'My Hero Academia, Chapter 247'};wsjModalPromoId='wsj_subscribe_modal_19402';wsjModalSource='My Hero Academia, Chapter 247';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19402,'/shonenjump/my-hero-academia-chapter-247/chapter/19402?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">October 20, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19402">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 247</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="11"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2460">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-246/chapter/19340?action=read',targetTitle:'My Hero Academia, Chapter 246'};wsjModalPromoId='wsj_subscribe_modal_19340';wsjModalSource='My Hero Academia, Chapter 246';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19340,'/shonenjump/my-hero-academia-chapter-246/chapter/19340?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">October 11, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19340">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 246</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="12"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2450">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-245/chapter/19244?action=read',targetTitle:'My Hero Academia, Chapter 245'};wsjModalPromoId='wsj_subscribe_modal_19244';wsjModalSource='My Hero Academia, Chapter 245';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19244,'/shonenjump/my-hero-academia-chapter-245/chapter/19244?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">October  6, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19244">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 245</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="13"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2440">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-244/chapter/19232?action=read',targetTitle:'My Hero Academia, Chapter 244'};wsjModalPromoId='wsj_subscribe_modal_19232';wsjModalSource='My Hero Academia, Chapter 244';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19232,'/shonenjump/my-hero-academia-chapter-244/chapter/19232?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">September 29, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19232">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 244</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="14"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2430">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-243/chapter/19201?action=read',targetTitle:'My Hero Academia, Chapter 243'};wsjModalPromoId='wsj_subscribe_modal_19201';wsjModalSource='My Hero Academia, Chapter 243';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19201,'/shonenjump/my-hero-academia-chapter-243/chapter/19201?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">September 13, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19201">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 243</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="15"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2420">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-242/chapter/19150?action=read',targetTitle:'My Hero Academia, Chapter 242'};wsjModalPromoId='wsj_subscribe_modal_19150';wsjModalSource='My Hero Academia, Chapter 242';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19150,'/shonenjump/my-hero-academia-chapter-242/chapter/19150?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">September  8, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19150">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 242</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="16"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2410">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-241/chapter/19079?action=read',targetTitle:'My Hero Academia, Chapter 241'};wsjModalPromoId='wsj_subscribe_modal_19079';wsjModalSource='My Hero Academia, Chapter 241';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19079,'/shonenjump/my-hero-academia-chapter-241/chapter/19079?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">September  1, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19079">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 241</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="17"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2400">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-240/chapter/19065?action=read',targetTitle:'My Hero Academia, Chapter 240'};wsjModalPromoId='wsj_subscribe_modal_19065';wsjModalSource='My Hero Academia, Chapter 240';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(19065,'/shonenjump/my-hero-academia-chapter-240/chapter/19065?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">August 25, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="19065">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 240</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="18"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2390">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-239/chapter/18740?action=read',targetTitle:'My Hero Academia, Chapter 239'};wsjModalPromoId='wsj_subscribe_modal_18740';wsjModalSource='My Hero Academia, Chapter 239';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18740,'/shonenjump/my-hero-academia-chapter-239/chapter/18740?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">August 18, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18740">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 239</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="19"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2380">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-238/chapter/18714?action=read',targetTitle:'My Hero Academia, Chapter 238'};wsjModalPromoId='wsj_subscribe_modal_18714';wsjModalSource='My Hero Academia, Chapter 238';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18714,'/shonenjump/my-hero-academia-chapter-238/chapter/18714?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">August  4, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18714">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 238</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="20"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2370">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-237/chapter/18693?action=read',targetTitle:'My Hero Academia, Chapter 237'};wsjModalPromoId='wsj_subscribe_modal_18693';wsjModalSource='My Hero Academia, Chapter 237';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18693,'/shonenjump/my-hero-academia-chapter-237/chapter/18693?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">July 28, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18693">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 237</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="21"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2360">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-236/chapter/18625?action=read',targetTitle:'My Hero Academia, Chapter 236'};wsjModalPromoId='wsj_subscribe_modal_18625';wsjModalSource='My Hero Academia, Chapter 236';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18625,'/shonenjump/my-hero-academia-chapter-236/chapter/18625?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">July 21, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18625">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 236</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="22"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2350">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-235/chapter/18605?action=read',targetTitle:'My Hero Academia, Chapter 235'};wsjModalPromoId='wsj_subscribe_modal_18605';wsjModalSource='My Hero Academia, Chapter 235';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18605,'/shonenjump/my-hero-academia-chapter-235/chapter/18605?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">July 12, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18605">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 235</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="23"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2340">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-234/chapter/18446?action=read',targetTitle:'My Hero Academia, Chapter 234'};wsjModalPromoId='wsj_subscribe_modal_18446';wsjModalSource='My Hero Academia, Chapter 234';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18446,'/shonenjump/my-hero-academia-chapter-234/chapter/18446?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">July  7, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18446">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 234</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="24"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2330">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-233/chapter/18408?action=read',targetTitle:'My Hero Academia, Chapter 233'};wsjModalPromoId='wsj_subscribe_modal_18408';wsjModalSource='My Hero Academia, Chapter 233';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18408,'/shonenjump/my-hero-academia-chapter-233/chapter/18408?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">June 23, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18408">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 233</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="25"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2320">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-232/chapter/18331?action=read',targetTitle:'My Hero Academia, Chapter 232'};wsjModalPromoId='wsj_subscribe_modal_18331';wsjModalSource='My Hero Academia, Chapter 232';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18331,'/shonenjump/my-hero-academia-chapter-232/chapter/18331?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">June 16, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18331">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 232</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="26"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2310">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-231/chapter/18308?action=read',targetTitle:'My Hero Academia, Chapter 231'};wsjModalPromoId='wsj_subscribe_modal_18308';wsjModalSource='My Hero Academia, Chapter 231';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18308,'/shonenjump/my-hero-academia-chapter-231/chapter/18308?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">June  9, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18308">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 231</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="27"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2300">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-230/chapter/18249?action=read',targetTitle:'My Hero Academia, Chapter 230'};wsjModalPromoId='wsj_subscribe_modal_18249';wsjModalSource='My Hero Academia, Chapter 230';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18249,'/shonenjump/my-hero-academia-chapter-230/chapter/18249?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">June  2, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18249">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 230</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="28"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2290">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-229/chapter/18229?action=read',targetTitle:'My Hero Academia, Chapter 229'};wsjModalPromoId='wsj_subscribe_modal_18229';wsjModalSource='My Hero Academia, Chapter 229';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18229,'/shonenjump/my-hero-academia-chapter-229/chapter/18229?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">May 26, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18229">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 229</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="29"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2280">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-228/chapter/18211?action=read',targetTitle:'My Hero Academia, Chapter 228'};wsjModalPromoId='wsj_subscribe_modal_18211';wsjModalSource='My Hero Academia, Chapter 228';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18211,'/shonenjump/my-hero-academia-chapter-228/chapter/18211?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">May 19, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18211">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 228</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="30"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2270">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-227/chapter/18187?action=read',targetTitle:'My Hero Academia, Chapter 227'};wsjModalPromoId='wsj_subscribe_modal_18187';wsjModalSource='My Hero Academia, Chapter 227';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18187,'/shonenjump/my-hero-academia-chapter-227/chapter/18187?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">May 12, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18187">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 227</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="31"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2260">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-226/chapter/18112?action=read',targetTitle:'My Hero Academia, Chapter 226'};wsjModalPromoId='wsj_subscribe_modal_18112';wsjModalSource='My Hero Academia, Chapter 226';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18112,'/shonenjump/my-hero-academia-chapter-226/chapter/18112?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">April 26, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18112">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 226</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="32"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2250">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-225/chapter/18094?action=read',targetTitle:'My Hero Academia, Chapter 225'};wsjModalPromoId='wsj_subscribe_modal_18094';wsjModalSource='My Hero Academia, Chapter 225';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18094,'/shonenjump/my-hero-academia-chapter-225/chapter/18094?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">April 21, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18094">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 225</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="33"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2240">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-224/chapter/18070?action=read',targetTitle:'My Hero Academia, Chapter 224'};wsjModalPromoId='wsj_subscribe_modal_18070';wsjModalSource='My Hero Academia, Chapter 224';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18070,'/shonenjump/my-hero-academia-chapter-224/chapter/18070?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">April 14, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18070">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 224</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="34"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2230">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-223/chapter/18025?action=read',targetTitle:'My Hero Academia, Chapter 223'};wsjModalPromoId='wsj_subscribe_modal_18025';wsjModalSource='My Hero Academia, Chapter 223';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(18025,'/shonenjump/my-hero-academia-chapter-223/chapter/18025?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">April  7, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="18025">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 223</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="35"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2220">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-222/chapter/17983?action=read',targetTitle:'My Hero Academia, Chapter 222'};wsjModalPromoId='wsj_subscribe_modal_17983';wsjModalSource='My Hero Academia, Chapter 222';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17983,'/shonenjump/my-hero-academia-chapter-222/chapter/17983?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">March 31, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17983">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 222</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="36"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2210">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-221/chapter/17936?action=read',targetTitle:'My Hero Academia, Chapter 221'};wsjModalPromoId='wsj_subscribe_modal_17936';wsjModalSource='My Hero Academia, Chapter 221';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17936,'/shonenjump/my-hero-academia-chapter-221/chapter/17936?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">March 24, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17936">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 221</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="37"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2200">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-220/chapter/17912?action=read',targetTitle:'My Hero Academia, Chapter 220'};wsjModalPromoId='wsj_subscribe_modal_17912';wsjModalSource='My Hero Academia, Chapter 220';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17912,'/shonenjump/my-hero-academia-chapter-220/chapter/17912?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">March 17, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17912">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 220</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="38"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2190">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-219/chapter/17892?action=read',targetTitle:'My Hero Academia, Chapter 219'};wsjModalPromoId='wsj_subscribe_modal_17892';wsjModalSource='My Hero Academia, Chapter 219';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17892,'/shonenjump/my-hero-academia-chapter-219/chapter/17892?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">March 10, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17892">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 219</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="39"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2180">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-218/chapter/17826?action=read',targetTitle:'My Hero Academia, Chapter 218'};wsjModalPromoId='wsj_subscribe_modal_17826';wsjModalSource='My Hero Academia, Chapter 218';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17826,'/shonenjump/my-hero-academia-chapter-218/chapter/17826?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">March  3, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17826">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 218</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="40"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2170">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-217/chapter/17739?action=read',targetTitle:'My Hero Academia, Chapter 217'};wsjModalPromoId='wsj_subscribe_modal_17739';wsjModalSource='My Hero Academia, Chapter 217';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17739,'/shonenjump/my-hero-academia-chapter-217/chapter/17739?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">February 17, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17739">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 217</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="41"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2160">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-216/chapter/17721?action=read',targetTitle:'My Hero Academia, Chapter 216'};wsjModalPromoId='wsj_subscribe_modal_17721';wsjModalSource='My Hero Academia, Chapter 216';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17721,'/shonenjump/my-hero-academia-chapter-216/chapter/17721?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">February  8, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17721">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 216</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="42"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2150">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-215/chapter/17706?action=read',targetTitle:'My Hero Academia, Chapter 215'};wsjModalPromoId='wsj_subscribe_modal_17706';wsjModalSource='My Hero Academia, Chapter 215';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17706,'/shonenjump/my-hero-academia-chapter-215/chapter/17706?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">February  3, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17706">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 215</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="43"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2140">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-214/chapter/17666?action=read',targetTitle:'My Hero Academia, Chapter 214'};wsjModalPromoId='wsj_subscribe_modal_17666';wsjModalSource='My Hero Academia, Chapter 214';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17666,'/shonenjump/my-hero-academia-chapter-214/chapter/17666?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">January 27, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17666">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 214</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="44"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2130">

    <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-213/chapter/17646?action=read',targetTitle:'My Hero Academia, Chapter 213'};wsjModalPromoId='wsj_subscribe_modal_17646';wsjModalSource='My Hero Academia, Chapter 213';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17646,'/shonenjump/my-hero-academia-chapter-213/chapter/17646?action=read');"
       class="o_chapter-archive o_chapter-container disp-bl color-off-black hover-off-black hover-bg-lighter-gray flex">


        <div class="flex-width-2 type-bs type-sm--sm style-italic">
          <table height="100%" width="100%">
            <tr><td align="right" valign="middle" class="pad-y-0 pad-r-0 pad-r-rg--sm">January 20, 2019</td></tr>
          </table>
        </div>
        <div class="pad-l-md pad-l-lg--lg pad-y-rg pad-y-md--lg type-rg--lg type-sm line-caption flex-width-2">
          <table height="100%">
            <tr class="o_chapter" data-mc_id="17646">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing" style="white-space:nowrap;">
                <div class="disp-id mar-r-sm">Ch. 213</div>
              </td>
              <td valign="middle" class="pad-y-0">
                <div class="pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
              </td>
            </tr>
          </table>
        </div>


    </a>
</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="45"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2120">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-22/product/6124/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1974709655.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-22/product/6124/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="17598"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2120">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-212/chapter/17598?action=read',targetTitle:'My Hero Academia, Chapter 212'};wsjModalPromoId='wsj_subscribe_modal_17598';wsjModalSource='My Hero Academia, Chapter 212';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17598,'/shonenjump/my-hero-academia-chapter-212/chapter/17598?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 212
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-212/chapter/17598?action=read',targetTitle:'My Hero Academia, Chapter 212'};wsjModalPromoId='wsj_subscribe_modal_17598';wsjModalSource='My Hero Academia, Chapter 212';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17598,'/shonenjump/my-hero-academia-chapter-212/chapter/17598?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-212/chapter/17598?action=read',targetTitle:'My Hero Academia, Chapter 212'};wsjModalPromoId='wsj_subscribe_modal_17598';wsjModalSource='My Hero Academia, Chapter 212';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17598,'/shonenjump/my-hero-academia-chapter-212/chapter/17598?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="17569"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2110">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-211/chapter/17569?action=read',targetTitle:'My Hero Academia, Chapter 211'};wsjModalPromoId='wsj_subscribe_modal_17569';wsjModalSource='My Hero Academia, Chapter 211';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17569,'/shonenjump/my-hero-academia-chapter-211/chapter/17569?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 211
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-211/chapter/17569?action=read',targetTitle:'My Hero Academia, Chapter 211'};wsjModalPromoId='wsj_subscribe_modal_17569';wsjModalSource='My Hero Academia, Chapter 211';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17569,'/shonenjump/my-hero-academia-chapter-211/chapter/17569?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-211/chapter/17569?action=read',targetTitle:'My Hero Academia, Chapter 211'};wsjModalPromoId='wsj_subscribe_modal_17569';wsjModalSource='My Hero Academia, Chapter 211';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17569,'/shonenjump/my-hero-academia-chapter-211/chapter/17569?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="17531"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2100">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-210/chapter/17531?action=read',targetTitle:'My Hero Academia, Chapter 210'};wsjModalPromoId='wsj_subscribe_modal_17531';wsjModalSource='My Hero Academia, Chapter 210';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17531,'/shonenjump/my-hero-academia-chapter-210/chapter/17531?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 210
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-210/chapter/17531?action=read',targetTitle:'My Hero Academia, Chapter 210'};wsjModalPromoId='wsj_subscribe_modal_17531';wsjModalSource='My Hero Academia, Chapter 210';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17531,'/shonenjump/my-hero-academia-chapter-210/chapter/17531?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-210/chapter/17531?action=read',targetTitle:'My Hero Academia, Chapter 210'};wsjModalPromoId='wsj_subscribe_modal_17531';wsjModalSource='My Hero Academia, Chapter 210';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17531,'/shonenjump/my-hero-academia-chapter-210/chapter/17531?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="17516"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2090">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-209/chapter/17516?action=read',targetTitle:'My Hero Academia, Chapter 209'};wsjModalPromoId='wsj_subscribe_modal_17516';wsjModalSource='My Hero Academia, Chapter 209';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17516,'/shonenjump/my-hero-academia-chapter-209/chapter/17516?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 209
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-209/chapter/17516?action=read',targetTitle:'My Hero Academia, Chapter 209'};wsjModalPromoId='wsj_subscribe_modal_17516';wsjModalSource='My Hero Academia, Chapter 209';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17516,'/shonenjump/my-hero-academia-chapter-209/chapter/17516?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-209/chapter/17516?action=read',targetTitle:'My Hero Academia, Chapter 209'};wsjModalPromoId='wsj_subscribe_modal_17516';wsjModalSource='My Hero Academia, Chapter 209';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(17516,'/shonenjump/my-hero-academia-chapter-209/chapter/17516?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16655"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2080">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-208/chapter/16655?action=read',targetTitle:'My Hero Academia, Chapter 208'};wsjModalPromoId='wsj_subscribe_modal_16655';wsjModalSource='My Hero Academia, Chapter 208';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16655,'/shonenjump/my-hero-academia-chapter-208/chapter/16655?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 208
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-208/chapter/16655?action=read',targetTitle:'My Hero Academia, Chapter 208'};wsjModalPromoId='wsj_subscribe_modal_16655';wsjModalSource='My Hero Academia, Chapter 208';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16655,'/shonenjump/my-hero-academia-chapter-208/chapter/16655?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-208/chapter/16655?action=read',targetTitle:'My Hero Academia, Chapter 208'};wsjModalPromoId='wsj_subscribe_modal_16655';wsjModalSource='My Hero Academia, Chapter 208';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16655,'/shonenjump/my-hero-academia-chapter-208/chapter/16655?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16712"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2070">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-207/chapter/16712?action=read',targetTitle:'My Hero Academia, Chapter 207'};wsjModalPromoId='wsj_subscribe_modal_16712';wsjModalSource='My Hero Academia, Chapter 207';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16712,'/shonenjump/my-hero-academia-chapter-207/chapter/16712?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 207
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-207/chapter/16712?action=read',targetTitle:'My Hero Academia, Chapter 207'};wsjModalPromoId='wsj_subscribe_modal_16712';wsjModalSource='My Hero Academia, Chapter 207';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16712,'/shonenjump/my-hero-academia-chapter-207/chapter/16712?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-207/chapter/16712?action=read',targetTitle:'My Hero Academia, Chapter 207'};wsjModalPromoId='wsj_subscribe_modal_16712';wsjModalSource='My Hero Academia, Chapter 207';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16712,'/shonenjump/my-hero-academia-chapter-207/chapter/16712?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16679"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2060">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-206/chapter/16679?action=read',targetTitle:'My Hero Academia, Chapter 206'};wsjModalPromoId='wsj_subscribe_modal_16679';wsjModalSource='My Hero Academia, Chapter 206';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16679,'/shonenjump/my-hero-academia-chapter-206/chapter/16679?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 206
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-206/chapter/16679?action=read',targetTitle:'My Hero Academia, Chapter 206'};wsjModalPromoId='wsj_subscribe_modal_16679';wsjModalSource='My Hero Academia, Chapter 206';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16679,'/shonenjump/my-hero-academia-chapter-206/chapter/16679?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-206/chapter/16679?action=read',targetTitle:'My Hero Academia, Chapter 206'};wsjModalPromoId='wsj_subscribe_modal_16679';wsjModalSource='My Hero Academia, Chapter 206';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16679,'/shonenjump/my-hero-academia-chapter-206/chapter/16679?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16660"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2050">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-205/chapter/16660?action=read',targetTitle:'My Hero Academia, Chapter 205'};wsjModalPromoId='wsj_subscribe_modal_16660';wsjModalSource='My Hero Academia, Chapter 205';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16660,'/shonenjump/my-hero-academia-chapter-205/chapter/16660?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 205
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-205/chapter/16660?action=read',targetTitle:'My Hero Academia, Chapter 205'};wsjModalPromoId='wsj_subscribe_modal_16660';wsjModalSource='My Hero Academia, Chapter 205';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16660,'/shonenjump/my-hero-academia-chapter-205/chapter/16660?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-205/chapter/16660?action=read',targetTitle:'My Hero Academia, Chapter 205'};wsjModalPromoId='wsj_subscribe_modal_16660';wsjModalSource='My Hero Academia, Chapter 205';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16660,'/shonenjump/my-hero-academia-chapter-205/chapter/16660?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16692"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2040">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-204/chapter/16692?action=read',targetTitle:'My Hero Academia, Chapter 204'};wsjModalPromoId='wsj_subscribe_modal_16692';wsjModalSource='My Hero Academia, Chapter 204';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16692,'/shonenjump/my-hero-academia-chapter-204/chapter/16692?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 204
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-204/chapter/16692?action=read',targetTitle:'My Hero Academia, Chapter 204'};wsjModalPromoId='wsj_subscribe_modal_16692';wsjModalSource='My Hero Academia, Chapter 204';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16692,'/shonenjump/my-hero-academia-chapter-204/chapter/16692?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-204/chapter/16692?action=read',targetTitle:'My Hero Academia, Chapter 204'};wsjModalPromoId='wsj_subscribe_modal_16692';wsjModalSource='My Hero Academia, Chapter 204';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16692,'/shonenjump/my-hero-academia-chapter-204/chapter/16692?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16698"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2030">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-203/chapter/16698?action=read',targetTitle:'My Hero Academia, Chapter 203'};wsjModalPromoId='wsj_subscribe_modal_16698';wsjModalSource='My Hero Academia, Chapter 203';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16698,'/shonenjump/my-hero-academia-chapter-203/chapter/16698?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 203
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-203/chapter/16698?action=read',targetTitle:'My Hero Academia, Chapter 203'};wsjModalPromoId='wsj_subscribe_modal_16698';wsjModalSource='My Hero Academia, Chapter 203';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16698,'/shonenjump/my-hero-academia-chapter-203/chapter/16698?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-203/chapter/16698?action=read',targetTitle:'My Hero Academia, Chapter 203'};wsjModalPromoId='wsj_subscribe_modal_16698';wsjModalSource='My Hero Academia, Chapter 203';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16698,'/shonenjump/my-hero-academia-chapter-203/chapter/16698?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16656"
                data-sort-recent="11"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2020">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-202/chapter/16656?action=read',targetTitle:'My Hero Academia, Chapter 202'};wsjModalPromoId='wsj_subscribe_modal_16656';wsjModalSource='My Hero Academia, Chapter 202';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16656,'/shonenjump/my-hero-academia-chapter-202/chapter/16656?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 202
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-202/chapter/16656?action=read',targetTitle:'My Hero Academia, Chapter 202'};wsjModalPromoId='wsj_subscribe_modal_16656';wsjModalSource='My Hero Academia, Chapter 202';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16656,'/shonenjump/my-hero-academia-chapter-202/chapter/16656?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-202/chapter/16656?action=read',targetTitle:'My Hero Academia, Chapter 202'};wsjModalPromoId='wsj_subscribe_modal_16656';wsjModalSource='My Hero Academia, Chapter 202';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16656,'/shonenjump/my-hero-academia-chapter-202/chapter/16656?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16672"
                data-sort-recent="12"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2010">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-201/chapter/16672?action=read',targetTitle:'My Hero Academia, Chapter 201'};wsjModalPromoId='wsj_subscribe_modal_16672';wsjModalSource='My Hero Academia, Chapter 201';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16672,'/shonenjump/my-hero-academia-chapter-201/chapter/16672?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 201
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-201/chapter/16672?action=read',targetTitle:'My Hero Academia, Chapter 201'};wsjModalPromoId='wsj_subscribe_modal_16672';wsjModalSource='My Hero Academia, Chapter 201';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16672,'/shonenjump/my-hero-academia-chapter-201/chapter/16672?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-201/chapter/16672?action=read',targetTitle:'My Hero Academia, Chapter 201'};wsjModalPromoId='wsj_subscribe_modal_16672';wsjModalSource='My Hero Academia, Chapter 201';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16672,'/shonenjump/my-hero-academia-chapter-201/chapter/16672?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="46"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="2000">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-21/product/6057/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1974709507.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-21/product/6057/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16713"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="2000">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-200/chapter/16713?action=read',targetTitle:'My Hero Academia, Chapter 200'};wsjModalPromoId='wsj_subscribe_modal_16713';wsjModalSource='My Hero Academia, Chapter 200';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16713,'/shonenjump/my-hero-academia-chapter-200/chapter/16713?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 200
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-200/chapter/16713?action=read',targetTitle:'My Hero Academia, Chapter 200'};wsjModalPromoId='wsj_subscribe_modal_16713';wsjModalSource='My Hero Academia, Chapter 200';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16713,'/shonenjump/my-hero-academia-chapter-200/chapter/16713?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-200/chapter/16713?action=read',targetTitle:'My Hero Academia, Chapter 200'};wsjModalPromoId='wsj_subscribe_modal_16713';wsjModalSource='My Hero Academia, Chapter 200';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16713,'/shonenjump/my-hero-academia-chapter-200/chapter/16713?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16696"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1990">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-199/chapter/16696?action=read',targetTitle:'My Hero Academia, Chapter 199'};wsjModalPromoId='wsj_subscribe_modal_16696';wsjModalSource='My Hero Academia, Chapter 199';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16696,'/shonenjump/my-hero-academia-chapter-199/chapter/16696?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 199
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-199/chapter/16696?action=read',targetTitle:'My Hero Academia, Chapter 199'};wsjModalPromoId='wsj_subscribe_modal_16696';wsjModalSource='My Hero Academia, Chapter 199';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16696,'/shonenjump/my-hero-academia-chapter-199/chapter/16696?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-199/chapter/16696?action=read',targetTitle:'My Hero Academia, Chapter 199'};wsjModalPromoId='wsj_subscribe_modal_16696';wsjModalSource='My Hero Academia, Chapter 199';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16696,'/shonenjump/my-hero-academia-chapter-199/chapter/16696?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16652"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1980">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-198/chapter/16652?action=read',targetTitle:'My Hero Academia, Chapter 198'};wsjModalPromoId='wsj_subscribe_modal_16652';wsjModalSource='My Hero Academia, Chapter 198';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16652,'/shonenjump/my-hero-academia-chapter-198/chapter/16652?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 198
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-198/chapter/16652?action=read',targetTitle:'My Hero Academia, Chapter 198'};wsjModalPromoId='wsj_subscribe_modal_16652';wsjModalSource='My Hero Academia, Chapter 198';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16652,'/shonenjump/my-hero-academia-chapter-198/chapter/16652?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-198/chapter/16652?action=read',targetTitle:'My Hero Academia, Chapter 198'};wsjModalPromoId='wsj_subscribe_modal_16652';wsjModalSource='My Hero Academia, Chapter 198';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16652,'/shonenjump/my-hero-academia-chapter-198/chapter/16652?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16711"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1970">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-197/chapter/16711?action=read',targetTitle:'My Hero Academia, Chapter 197'};wsjModalPromoId='wsj_subscribe_modal_16711';wsjModalSource='My Hero Academia, Chapter 197';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16711,'/shonenjump/my-hero-academia-chapter-197/chapter/16711?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 197
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-197/chapter/16711?action=read',targetTitle:'My Hero Academia, Chapter 197'};wsjModalPromoId='wsj_subscribe_modal_16711';wsjModalSource='My Hero Academia, Chapter 197';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16711,'/shonenjump/my-hero-academia-chapter-197/chapter/16711?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-197/chapter/16711?action=read',targetTitle:'My Hero Academia, Chapter 197'};wsjModalPromoId='wsj_subscribe_modal_16711';wsjModalSource='My Hero Academia, Chapter 197';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16711,'/shonenjump/my-hero-academia-chapter-197/chapter/16711?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16676"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1960">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-196/chapter/16676?action=read',targetTitle:'My Hero Academia, Chapter 196'};wsjModalPromoId='wsj_subscribe_modal_16676';wsjModalSource='My Hero Academia, Chapter 196';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16676,'/shonenjump/my-hero-academia-chapter-196/chapter/16676?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 196
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-196/chapter/16676?action=read',targetTitle:'My Hero Academia, Chapter 196'};wsjModalPromoId='wsj_subscribe_modal_16676';wsjModalSource='My Hero Academia, Chapter 196';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16676,'/shonenjump/my-hero-academia-chapter-196/chapter/16676?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-196/chapter/16676?action=read',targetTitle:'My Hero Academia, Chapter 196'};wsjModalPromoId='wsj_subscribe_modal_16676';wsjModalSource='My Hero Academia, Chapter 196';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16676,'/shonenjump/my-hero-academia-chapter-196/chapter/16676?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16662"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1950">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-195/chapter/16662?action=read',targetTitle:'My Hero Academia, Chapter 195'};wsjModalPromoId='wsj_subscribe_modal_16662';wsjModalSource='My Hero Academia, Chapter 195';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16662,'/shonenjump/my-hero-academia-chapter-195/chapter/16662?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 195
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-195/chapter/16662?action=read',targetTitle:'My Hero Academia, Chapter 195'};wsjModalPromoId='wsj_subscribe_modal_16662';wsjModalSource='My Hero Academia, Chapter 195';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16662,'/shonenjump/my-hero-academia-chapter-195/chapter/16662?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-195/chapter/16662?action=read',targetTitle:'My Hero Academia, Chapter 195'};wsjModalPromoId='wsj_subscribe_modal_16662';wsjModalSource='My Hero Academia, Chapter 195';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16662,'/shonenjump/my-hero-academia-chapter-195/chapter/16662?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16693"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1940">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-194/chapter/16693?action=read',targetTitle:'My Hero Academia, Chapter 194'};wsjModalPromoId='wsj_subscribe_modal_16693';wsjModalSource='My Hero Academia, Chapter 194';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16693,'/shonenjump/my-hero-academia-chapter-194/chapter/16693?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 194
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-194/chapter/16693?action=read',targetTitle:'My Hero Academia, Chapter 194'};wsjModalPromoId='wsj_subscribe_modal_16693';wsjModalSource='My Hero Academia, Chapter 194';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16693,'/shonenjump/my-hero-academia-chapter-194/chapter/16693?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-194/chapter/16693?action=read',targetTitle:'My Hero Academia, Chapter 194'};wsjModalPromoId='wsj_subscribe_modal_16693';wsjModalSource='My Hero Academia, Chapter 194';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16693,'/shonenjump/my-hero-academia-chapter-194/chapter/16693?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16695"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1930">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-193/chapter/16695?action=read',targetTitle:'My Hero Academia, Chapter 193'};wsjModalPromoId='wsj_subscribe_modal_16695';wsjModalSource='My Hero Academia, Chapter 193';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16695,'/shonenjump/my-hero-academia-chapter-193/chapter/16695?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 193
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-193/chapter/16695?action=read',targetTitle:'My Hero Academia, Chapter 193'};wsjModalPromoId='wsj_subscribe_modal_16695';wsjModalSource='My Hero Academia, Chapter 193';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16695,'/shonenjump/my-hero-academia-chapter-193/chapter/16695?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-193/chapter/16695?action=read',targetTitle:'My Hero Academia, Chapter 193'};wsjModalPromoId='wsj_subscribe_modal_16695';wsjModalSource='My Hero Academia, Chapter 193';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16695,'/shonenjump/my-hero-academia-chapter-193/chapter/16695?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16654"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1920">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-192/chapter/16654?action=read',targetTitle:'My Hero Academia, Chapter 192'};wsjModalPromoId='wsj_subscribe_modal_16654';wsjModalSource='My Hero Academia, Chapter 192';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16654,'/shonenjump/my-hero-academia-chapter-192/chapter/16654?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 192
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-192/chapter/16654?action=read',targetTitle:'My Hero Academia, Chapter 192'};wsjModalPromoId='wsj_subscribe_modal_16654';wsjModalSource='My Hero Academia, Chapter 192';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16654,'/shonenjump/my-hero-academia-chapter-192/chapter/16654?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-192/chapter/16654?action=read',targetTitle:'My Hero Academia, Chapter 192'};wsjModalPromoId='wsj_subscribe_modal_16654';wsjModalSource='My Hero Academia, Chapter 192';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16654,'/shonenjump/my-hero-academia-chapter-192/chapter/16654?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16673"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1910">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-191/chapter/16673?action=read',targetTitle:'My Hero Academia, Chapter 191'};wsjModalPromoId='wsj_subscribe_modal_16673';wsjModalSource='My Hero Academia, Chapter 191';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16673,'/shonenjump/my-hero-academia-chapter-191/chapter/16673?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 191
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-191/chapter/16673?action=read',targetTitle:'My Hero Academia, Chapter 191'};wsjModalPromoId='wsj_subscribe_modal_16673';wsjModalSource='My Hero Academia, Chapter 191';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16673,'/shonenjump/my-hero-academia-chapter-191/chapter/16673?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-191/chapter/16673?action=read',targetTitle:'My Hero Academia, Chapter 191'};wsjModalPromoId='wsj_subscribe_modal_16673';wsjModalSource='My Hero Academia, Chapter 191';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16673,'/shonenjump/my-hero-academia-chapter-191/chapter/16673?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16715"
                data-sort-recent="11"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1900">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-190/chapter/16715?action=read',targetTitle:'My Hero Academia, Chapter 190'};wsjModalPromoId='wsj_subscribe_modal_16715';wsjModalSource='My Hero Academia, Chapter 190';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16715,'/shonenjump/my-hero-academia-chapter-190/chapter/16715?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 190
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-190/chapter/16715?action=read',targetTitle:'My Hero Academia, Chapter 190'};wsjModalPromoId='wsj_subscribe_modal_16715';wsjModalSource='My Hero Academia, Chapter 190';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16715,'/shonenjump/my-hero-academia-chapter-190/chapter/16715?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-190/chapter/16715?action=read',targetTitle:'My Hero Academia, Chapter 190'};wsjModalPromoId='wsj_subscribe_modal_16715';wsjModalSource='My Hero Academia, Chapter 190';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16715,'/shonenjump/my-hero-academia-chapter-190/chapter/16715?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16718"
                data-sort-recent="12"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1890">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-189/chapter/16718?action=read',targetTitle:'My Hero Academia, Chapter 189'};wsjModalPromoId='wsj_subscribe_modal_16718';wsjModalSource='My Hero Academia, Chapter 189';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16718,'/shonenjump/my-hero-academia-chapter-189/chapter/16718?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 189
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-189/chapter/16718?action=read',targetTitle:'My Hero Academia, Chapter 189'};wsjModalPromoId='wsj_subscribe_modal_16718';wsjModalSource='My Hero Academia, Chapter 189';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16718,'/shonenjump/my-hero-academia-chapter-189/chapter/16718?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-189/chapter/16718?action=read',targetTitle:'My Hero Academia, Chapter 189'};wsjModalPromoId='wsj_subscribe_modal_16718';wsjModalSource='My Hero Academia, Chapter 189';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16718,'/shonenjump/my-hero-academia-chapter-189/chapter/16718?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="47"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="1880">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-20/product/6002/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1974707733.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-20/product/6002/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16669"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1880">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-188/chapter/16669?action=read',targetTitle:'My Hero Academia, Chapter 188'};wsjModalPromoId='wsj_subscribe_modal_16669';wsjModalSource='My Hero Academia, Chapter 188';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16669,'/shonenjump/my-hero-academia-chapter-188/chapter/16669?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 188
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-188/chapter/16669?action=read',targetTitle:'My Hero Academia, Chapter 188'};wsjModalPromoId='wsj_subscribe_modal_16669';wsjModalSource='My Hero Academia, Chapter 188';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16669,'/shonenjump/my-hero-academia-chapter-188/chapter/16669?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-188/chapter/16669?action=read',targetTitle:'My Hero Academia, Chapter 188'};wsjModalPromoId='wsj_subscribe_modal_16669';wsjModalSource='My Hero Academia, Chapter 188';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16669,'/shonenjump/my-hero-academia-chapter-188/chapter/16669?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16689"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1870">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-187/chapter/16689?action=read',targetTitle:'My Hero Academia, Chapter 187'};wsjModalPromoId='wsj_subscribe_modal_16689';wsjModalSource='My Hero Academia, Chapter 187';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16689,'/shonenjump/my-hero-academia-chapter-187/chapter/16689?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 187
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-187/chapter/16689?action=read',targetTitle:'My Hero Academia, Chapter 187'};wsjModalPromoId='wsj_subscribe_modal_16689';wsjModalSource='My Hero Academia, Chapter 187';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16689,'/shonenjump/my-hero-academia-chapter-187/chapter/16689?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-187/chapter/16689?action=read',targetTitle:'My Hero Academia, Chapter 187'};wsjModalPromoId='wsj_subscribe_modal_16689';wsjModalSource='My Hero Academia, Chapter 187';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16689,'/shonenjump/my-hero-academia-chapter-187/chapter/16689?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16664"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1860">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-186/chapter/16664?action=read',targetTitle:'My Hero Academia, Chapter 186'};wsjModalPromoId='wsj_subscribe_modal_16664';wsjModalSource='My Hero Academia, Chapter 186';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16664,'/shonenjump/my-hero-academia-chapter-186/chapter/16664?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 186
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-186/chapter/16664?action=read',targetTitle:'My Hero Academia, Chapter 186'};wsjModalPromoId='wsj_subscribe_modal_16664';wsjModalSource='My Hero Academia, Chapter 186';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16664,'/shonenjump/my-hero-academia-chapter-186/chapter/16664?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-186/chapter/16664?action=read',targetTitle:'My Hero Academia, Chapter 186'};wsjModalPromoId='wsj_subscribe_modal_16664';wsjModalSource='My Hero Academia, Chapter 186';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16664,'/shonenjump/my-hero-academia-chapter-186/chapter/16664?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16684"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1850">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-185/chapter/16684?action=read',targetTitle:'My Hero Academia, Chapter 185'};wsjModalPromoId='wsj_subscribe_modal_16684';wsjModalSource='My Hero Academia, Chapter 185';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16684,'/shonenjump/my-hero-academia-chapter-185/chapter/16684?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 185
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-185/chapter/16684?action=read',targetTitle:'My Hero Academia, Chapter 185'};wsjModalPromoId='wsj_subscribe_modal_16684';wsjModalSource='My Hero Academia, Chapter 185';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16684,'/shonenjump/my-hero-academia-chapter-185/chapter/16684?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-185/chapter/16684?action=read',targetTitle:'My Hero Academia, Chapter 185'};wsjModalPromoId='wsj_subscribe_modal_16684';wsjModalSource='My Hero Academia, Chapter 185';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16684,'/shonenjump/my-hero-academia-chapter-185/chapter/16684?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16706"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1840">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-184/chapter/16706?action=read',targetTitle:'My Hero Academia, Chapter 184'};wsjModalPromoId='wsj_subscribe_modal_16706';wsjModalSource='My Hero Academia, Chapter 184';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16706,'/shonenjump/my-hero-academia-chapter-184/chapter/16706?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 184
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-184/chapter/16706?action=read',targetTitle:'My Hero Academia, Chapter 184'};wsjModalPromoId='wsj_subscribe_modal_16706';wsjModalSource='My Hero Academia, Chapter 184';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16706,'/shonenjump/my-hero-academia-chapter-184/chapter/16706?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-184/chapter/16706?action=read',targetTitle:'My Hero Academia, Chapter 184'};wsjModalPromoId='wsj_subscribe_modal_16706';wsjModalSource='My Hero Academia, Chapter 184';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16706,'/shonenjump/my-hero-academia-chapter-184/chapter/16706?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16716"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1830">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-183/chapter/16716?action=read',targetTitle:'My Hero Academia, Chapter 183'};wsjModalPromoId='wsj_subscribe_modal_16716';wsjModalSource='My Hero Academia, Chapter 183';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16716,'/shonenjump/my-hero-academia-chapter-183/chapter/16716?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 183
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-183/chapter/16716?action=read',targetTitle:'My Hero Academia, Chapter 183'};wsjModalPromoId='wsj_subscribe_modal_16716';wsjModalSource='My Hero Academia, Chapter 183';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16716,'/shonenjump/my-hero-academia-chapter-183/chapter/16716?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-183/chapter/16716?action=read',targetTitle:'My Hero Academia, Chapter 183'};wsjModalPromoId='wsj_subscribe_modal_16716';wsjModalSource='My Hero Academia, Chapter 183';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16716,'/shonenjump/my-hero-academia-chapter-183/chapter/16716?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16670"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1820">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-182/chapter/16670?action=read',targetTitle:'My Hero Academia, Chapter 182'};wsjModalPromoId='wsj_subscribe_modal_16670';wsjModalSource='My Hero Academia, Chapter 182';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16670,'/shonenjump/my-hero-academia-chapter-182/chapter/16670?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 182
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-182/chapter/16670?action=read',targetTitle:'My Hero Academia, Chapter 182'};wsjModalPromoId='wsj_subscribe_modal_16670';wsjModalSource='My Hero Academia, Chapter 182';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16670,'/shonenjump/my-hero-academia-chapter-182/chapter/16670?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-182/chapter/16670?action=read',targetTitle:'My Hero Academia, Chapter 182'};wsjModalPromoId='wsj_subscribe_modal_16670';wsjModalSource='My Hero Academia, Chapter 182';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16670,'/shonenjump/my-hero-academia-chapter-182/chapter/16670?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16647"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1810">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-181/chapter/16647?action=read',targetTitle:'My Hero Academia, Chapter 181'};wsjModalPromoId='wsj_subscribe_modal_16647';wsjModalSource='My Hero Academia, Chapter 181';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16647,'/shonenjump/my-hero-academia-chapter-181/chapter/16647?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 181
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-181/chapter/16647?action=read',targetTitle:'My Hero Academia, Chapter 181'};wsjModalPromoId='wsj_subscribe_modal_16647';wsjModalSource='My Hero Academia, Chapter 181';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16647,'/shonenjump/my-hero-academia-chapter-181/chapter/16647?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-181/chapter/16647?action=read',targetTitle:'My Hero Academia, Chapter 181'};wsjModalPromoId='wsj_subscribe_modal_16647';wsjModalSource='My Hero Academia, Chapter 181';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16647,'/shonenjump/my-hero-academia-chapter-181/chapter/16647?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16701"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1800">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-180/chapter/16701?action=read',targetTitle:'My Hero Academia, Chapter 180'};wsjModalPromoId='wsj_subscribe_modal_16701';wsjModalSource='My Hero Academia, Chapter 180';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16701,'/shonenjump/my-hero-academia-chapter-180/chapter/16701?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 180
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-180/chapter/16701?action=read',targetTitle:'My Hero Academia, Chapter 180'};wsjModalPromoId='wsj_subscribe_modal_16701';wsjModalSource='My Hero Academia, Chapter 180';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16701,'/shonenjump/my-hero-academia-chapter-180/chapter/16701?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-180/chapter/16701?action=read',targetTitle:'My Hero Academia, Chapter 180'};wsjModalPromoId='wsj_subscribe_modal_16701';wsjModalSource='My Hero Academia, Chapter 180';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16701,'/shonenjump/my-hero-academia-chapter-180/chapter/16701?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16710"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1790">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-179/chapter/16710?action=read',targetTitle:'My Hero Academia, Chapter 179'};wsjModalPromoId='wsj_subscribe_modal_16710';wsjModalSource='My Hero Academia, Chapter 179';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16710,'/shonenjump/my-hero-academia-chapter-179/chapter/16710?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 179
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-179/chapter/16710?action=read',targetTitle:'My Hero Academia, Chapter 179'};wsjModalPromoId='wsj_subscribe_modal_16710';wsjModalSource='My Hero Academia, Chapter 179';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16710,'/shonenjump/my-hero-academia-chapter-179/chapter/16710?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-179/chapter/16710?action=read',targetTitle:'My Hero Academia, Chapter 179'};wsjModalPromoId='wsj_subscribe_modal_16710';wsjModalSource='My Hero Academia, Chapter 179';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16710,'/shonenjump/my-hero-academia-chapter-179/chapter/16710?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16675"
                data-sort-recent="11"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1780">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-178/chapter/16675?action=read',targetTitle:'My Hero Academia, Chapter 178'};wsjModalPromoId='wsj_subscribe_modal_16675';wsjModalSource='My Hero Academia, Chapter 178';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16675,'/shonenjump/my-hero-academia-chapter-178/chapter/16675?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 178
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-178/chapter/16675?action=read',targetTitle:'My Hero Academia, Chapter 178'};wsjModalPromoId='wsj_subscribe_modal_16675';wsjModalSource='My Hero Academia, Chapter 178';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16675,'/shonenjump/my-hero-academia-chapter-178/chapter/16675?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-178/chapter/16675?action=read',targetTitle:'My Hero Academia, Chapter 178'};wsjModalPromoId='wsj_subscribe_modal_16675';wsjModalSource='My Hero Academia, Chapter 178';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16675,'/shonenjump/my-hero-academia-chapter-178/chapter/16675?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="48"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="1770">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-19/product/5924/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1974704602.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-19/product/5924/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16697"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1770">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-177/chapter/16697?action=read',targetTitle:'My Hero Academia, Chapter 177'};wsjModalPromoId='wsj_subscribe_modal_16697';wsjModalSource='My Hero Academia, Chapter 177';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16697,'/shonenjump/my-hero-academia-chapter-177/chapter/16697?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 177
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-177/chapter/16697?action=read',targetTitle:'My Hero Academia, Chapter 177'};wsjModalPromoId='wsj_subscribe_modal_16697';wsjModalSource='My Hero Academia, Chapter 177';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16697,'/shonenjump/my-hero-academia-chapter-177/chapter/16697?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-177/chapter/16697?action=read',targetTitle:'My Hero Academia, Chapter 177'};wsjModalPromoId='wsj_subscribe_modal_16697';wsjModalSource='My Hero Academia, Chapter 177';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16697,'/shonenjump/my-hero-academia-chapter-177/chapter/16697?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16653"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1760">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-176/chapter/16653?action=read',targetTitle:'My Hero Academia, Chapter 176'};wsjModalPromoId='wsj_subscribe_modal_16653';wsjModalSource='My Hero Academia, Chapter 176';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16653,'/shonenjump/my-hero-academia-chapter-176/chapter/16653?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 176
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-176/chapter/16653?action=read',targetTitle:'My Hero Academia, Chapter 176'};wsjModalPromoId='wsj_subscribe_modal_16653';wsjModalSource='My Hero Academia, Chapter 176';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16653,'/shonenjump/my-hero-academia-chapter-176/chapter/16653?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-176/chapter/16653?action=read',targetTitle:'My Hero Academia, Chapter 176'};wsjModalPromoId='wsj_subscribe_modal_16653';wsjModalSource='My Hero Academia, Chapter 176';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16653,'/shonenjump/my-hero-academia-chapter-176/chapter/16653?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16674"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1750">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-175/chapter/16674?action=read',targetTitle:'My Hero Academia, Chapter 175'};wsjModalPromoId='wsj_subscribe_modal_16674';wsjModalSource='My Hero Academia, Chapter 175';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16674,'/shonenjump/my-hero-academia-chapter-175/chapter/16674?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 175
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-175/chapter/16674?action=read',targetTitle:'My Hero Academia, Chapter 175'};wsjModalPromoId='wsj_subscribe_modal_16674';wsjModalSource='My Hero Academia, Chapter 175';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16674,'/shonenjump/my-hero-academia-chapter-175/chapter/16674?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-175/chapter/16674?action=read',targetTitle:'My Hero Academia, Chapter 175'};wsjModalPromoId='wsj_subscribe_modal_16674';wsjModalSource='My Hero Academia, Chapter 175';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16674,'/shonenjump/my-hero-academia-chapter-175/chapter/16674?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16714"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1740">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-174/chapter/16714?action=read',targetTitle:'My Hero Academia, Chapter 174'};wsjModalPromoId='wsj_subscribe_modal_16714';wsjModalSource='My Hero Academia, Chapter 174';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16714,'/shonenjump/my-hero-academia-chapter-174/chapter/16714?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 174
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-174/chapter/16714?action=read',targetTitle:'My Hero Academia, Chapter 174'};wsjModalPromoId='wsj_subscribe_modal_16714';wsjModalSource='My Hero Academia, Chapter 174';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16714,'/shonenjump/my-hero-academia-chapter-174/chapter/16714?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-174/chapter/16714?action=read',targetTitle:'My Hero Academia, Chapter 174'};wsjModalPromoId='wsj_subscribe_modal_16714';wsjModalSource='My Hero Academia, Chapter 174';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16714,'/shonenjump/my-hero-academia-chapter-174/chapter/16714?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16709"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1730">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-173/chapter/16709?action=read',targetTitle:'My Hero Academia, Chapter 173'};wsjModalPromoId='wsj_subscribe_modal_16709';wsjModalSource='My Hero Academia, Chapter 173';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16709,'/shonenjump/my-hero-academia-chapter-173/chapter/16709?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 173
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-173/chapter/16709?action=read',targetTitle:'My Hero Academia, Chapter 173'};wsjModalPromoId='wsj_subscribe_modal_16709';wsjModalSource='My Hero Academia, Chapter 173';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16709,'/shonenjump/my-hero-academia-chapter-173/chapter/16709?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-173/chapter/16709?action=read',targetTitle:'My Hero Academia, Chapter 173'};wsjModalPromoId='wsj_subscribe_modal_16709';wsjModalSource='My Hero Academia, Chapter 173';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16709,'/shonenjump/my-hero-academia-chapter-173/chapter/16709?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16677"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1720">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-172/chapter/16677?action=read',targetTitle:'My Hero Academia, Chapter 172'};wsjModalPromoId='wsj_subscribe_modal_16677';wsjModalSource='My Hero Academia, Chapter 172';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16677,'/shonenjump/my-hero-academia-chapter-172/chapter/16677?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 172
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-172/chapter/16677?action=read',targetTitle:'My Hero Academia, Chapter 172'};wsjModalPromoId='wsj_subscribe_modal_16677';wsjModalSource='My Hero Academia, Chapter 172';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16677,'/shonenjump/my-hero-academia-chapter-172/chapter/16677?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-172/chapter/16677?action=read',targetTitle:'My Hero Academia, Chapter 172'};wsjModalPromoId='wsj_subscribe_modal_16677';wsjModalSource='My Hero Academia, Chapter 172';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16677,'/shonenjump/my-hero-academia-chapter-172/chapter/16677?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16661"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1710">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-171/chapter/16661?action=read',targetTitle:'My Hero Academia, Chapter 171'};wsjModalPromoId='wsj_subscribe_modal_16661';wsjModalSource='My Hero Academia, Chapter 171';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16661,'/shonenjump/my-hero-academia-chapter-171/chapter/16661?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 171
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-171/chapter/16661?action=read',targetTitle:'My Hero Academia, Chapter 171'};wsjModalPromoId='wsj_subscribe_modal_16661';wsjModalSource='My Hero Academia, Chapter 171';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16661,'/shonenjump/my-hero-academia-chapter-171/chapter/16661?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-171/chapter/16661?action=read',targetTitle:'My Hero Academia, Chapter 171'};wsjModalPromoId='wsj_subscribe_modal_16661';wsjModalSource='My Hero Academia, Chapter 171';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16661,'/shonenjump/my-hero-academia-chapter-171/chapter/16661?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16694"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1700">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-170/chapter/16694?action=read',targetTitle:'My Hero Academia, Chapter 170'};wsjModalPromoId='wsj_subscribe_modal_16694';wsjModalSource='My Hero Academia, Chapter 170';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16694,'/shonenjump/my-hero-academia-chapter-170/chapter/16694?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 170
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-170/chapter/16694?action=read',targetTitle:'My Hero Academia, Chapter 170'};wsjModalPromoId='wsj_subscribe_modal_16694';wsjModalSource='My Hero Academia, Chapter 170';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16694,'/shonenjump/my-hero-academia-chapter-170/chapter/16694?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-170/chapter/16694?action=read',targetTitle:'My Hero Academia, Chapter 170'};wsjModalPromoId='wsj_subscribe_modal_16694';wsjModalSource='My Hero Academia, Chapter 170';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16694,'/shonenjump/my-hero-academia-chapter-170/chapter/16694?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16690"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1690">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-169/chapter/16690?action=read',targetTitle:'My Hero Academia, Chapter 169'};wsjModalPromoId='wsj_subscribe_modal_16690';wsjModalSource='My Hero Academia, Chapter 169';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16690,'/shonenjump/my-hero-academia-chapter-169/chapter/16690?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 169
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-169/chapter/16690?action=read',targetTitle:'My Hero Academia, Chapter 169'};wsjModalPromoId='wsj_subscribe_modal_16690';wsjModalSource='My Hero Academia, Chapter 169';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16690,'/shonenjump/my-hero-academia-chapter-169/chapter/16690?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-169/chapter/16690?action=read',targetTitle:'My Hero Academia, Chapter 169'};wsjModalPromoId='wsj_subscribe_modal_16690';wsjModalSource='My Hero Academia, Chapter 169';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16690,'/shonenjump/my-hero-academia-chapter-169/chapter/16690?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16665"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1680">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-168/chapter/16665?action=read',targetTitle:'My Hero Academia, Chapter 168'};wsjModalPromoId='wsj_subscribe_modal_16665';wsjModalSource='My Hero Academia, Chapter 168';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16665,'/shonenjump/my-hero-academia-chapter-168/chapter/16665?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 168
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-168/chapter/16665?action=read',targetTitle:'My Hero Academia, Chapter 168'};wsjModalPromoId='wsj_subscribe_modal_16665';wsjModalSource='My Hero Academia, Chapter 168';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16665,'/shonenjump/my-hero-academia-chapter-168/chapter/16665?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-168/chapter/16665?action=read',targetTitle:'My Hero Academia, Chapter 168'};wsjModalPromoId='wsj_subscribe_modal_16665';wsjModalSource='My Hero Academia, Chapter 168';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16665,'/shonenjump/my-hero-academia-chapter-168/chapter/16665?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="49"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="1670">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-18/product/5879/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1974704378.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-18/product/5879/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16717"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1670">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-167/chapter/16717?action=read',targetTitle:'My Hero Academia, Chapter 167'};wsjModalPromoId='wsj_subscribe_modal_16717';wsjModalSource='My Hero Academia, Chapter 167';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16717,'/shonenjump/my-hero-academia-chapter-167/chapter/16717?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 167
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-167/chapter/16717?action=read',targetTitle:'My Hero Academia, Chapter 167'};wsjModalPromoId='wsj_subscribe_modal_16717';wsjModalSource='My Hero Academia, Chapter 167';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16717,'/shonenjump/my-hero-academia-chapter-167/chapter/16717?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-167/chapter/16717?action=read',targetTitle:'My Hero Academia, Chapter 167'};wsjModalPromoId='wsj_subscribe_modal_16717';wsjModalSource='My Hero Academia, Chapter 167';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16717,'/shonenjump/my-hero-academia-chapter-167/chapter/16717?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16668"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1660">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-166/chapter/16668?action=read',targetTitle:'My Hero Academia, Chapter 166'};wsjModalPromoId='wsj_subscribe_modal_16668';wsjModalSource='My Hero Academia, Chapter 166';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16668,'/shonenjump/my-hero-academia-chapter-166/chapter/16668?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 166
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-166/chapter/16668?action=read',targetTitle:'My Hero Academia, Chapter 166'};wsjModalPromoId='wsj_subscribe_modal_16668';wsjModalSource='My Hero Academia, Chapter 166';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16668,'/shonenjump/my-hero-academia-chapter-166/chapter/16668?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-166/chapter/16668?action=read',targetTitle:'My Hero Academia, Chapter 166'};wsjModalPromoId='wsj_subscribe_modal_16668';wsjModalSource='My Hero Academia, Chapter 166';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16668,'/shonenjump/my-hero-academia-chapter-166/chapter/16668?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16648"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1650">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-165/chapter/16648?action=read',targetTitle:'My Hero Academia, Chapter 165'};wsjModalPromoId='wsj_subscribe_modal_16648';wsjModalSource='My Hero Academia, Chapter 165';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16648,'/shonenjump/my-hero-academia-chapter-165/chapter/16648?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 165
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-165/chapter/16648?action=read',targetTitle:'My Hero Academia, Chapter 165'};wsjModalPromoId='wsj_subscribe_modal_16648';wsjModalSource='My Hero Academia, Chapter 165';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16648,'/shonenjump/my-hero-academia-chapter-165/chapter/16648?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-165/chapter/16648?action=read',targetTitle:'My Hero Academia, Chapter 165'};wsjModalPromoId='wsj_subscribe_modal_16648';wsjModalSource='My Hero Academia, Chapter 165';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16648,'/shonenjump/my-hero-academia-chapter-165/chapter/16648?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16700"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1640">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-164/chapter/16700?action=read',targetTitle:'My Hero Academia, Chapter 164'};wsjModalPromoId='wsj_subscribe_modal_16700';wsjModalSource='My Hero Academia, Chapter 164';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16700,'/shonenjump/my-hero-academia-chapter-164/chapter/16700?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 164
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-164/chapter/16700?action=read',targetTitle:'My Hero Academia, Chapter 164'};wsjModalPromoId='wsj_subscribe_modal_16700';wsjModalSource='My Hero Academia, Chapter 164';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16700,'/shonenjump/my-hero-academia-chapter-164/chapter/16700?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-164/chapter/16700?action=read',targetTitle:'My Hero Academia, Chapter 164'};wsjModalPromoId='wsj_subscribe_modal_16700';wsjModalSource='My Hero Academia, Chapter 164';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16700,'/shonenjump/my-hero-academia-chapter-164/chapter/16700?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16688"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1630">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-163/chapter/16688?action=read',targetTitle:'My Hero Academia, Chapter 163'};wsjModalPromoId='wsj_subscribe_modal_16688';wsjModalSource='My Hero Academia, Chapter 163';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16688,'/shonenjump/my-hero-academia-chapter-163/chapter/16688?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 163
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-163/chapter/16688?action=read',targetTitle:'My Hero Academia, Chapter 163'};wsjModalPromoId='wsj_subscribe_modal_16688';wsjModalSource='My Hero Academia, Chapter 163';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16688,'/shonenjump/my-hero-academia-chapter-163/chapter/16688?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-163/chapter/16688?action=read',targetTitle:'My Hero Academia, Chapter 163'};wsjModalPromoId='wsj_subscribe_modal_16688';wsjModalSource='My Hero Academia, Chapter 163';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16688,'/shonenjump/my-hero-academia-chapter-163/chapter/16688?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16666"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1620">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-162/chapter/16666?action=read',targetTitle:'My Hero Academia, Chapter 162'};wsjModalPromoId='wsj_subscribe_modal_16666';wsjModalSource='My Hero Academia, Chapter 162';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16666,'/shonenjump/my-hero-academia-chapter-162/chapter/16666?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 162
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-162/chapter/16666?action=read',targetTitle:'My Hero Academia, Chapter 162'};wsjModalPromoId='wsj_subscribe_modal_16666';wsjModalSource='My Hero Academia, Chapter 162';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16666,'/shonenjump/my-hero-academia-chapter-162/chapter/16666?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-162/chapter/16666?action=read',targetTitle:'My Hero Academia, Chapter 162'};wsjModalPromoId='wsj_subscribe_modal_16666';wsjModalSource='My Hero Academia, Chapter 162';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16666,'/shonenjump/my-hero-academia-chapter-162/chapter/16666?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16683"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1610">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-161/chapter/16683?action=read',targetTitle:'My Hero Academia, Chapter 161'};wsjModalPromoId='wsj_subscribe_modal_16683';wsjModalSource='My Hero Academia, Chapter 161';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16683,'/shonenjump/my-hero-academia-chapter-161/chapter/16683?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 161
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-161/chapter/16683?action=read',targetTitle:'My Hero Academia, Chapter 161'};wsjModalPromoId='wsj_subscribe_modal_16683';wsjModalSource='My Hero Academia, Chapter 161';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16683,'/shonenjump/my-hero-academia-chapter-161/chapter/16683?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-161/chapter/16683?action=read',targetTitle:'My Hero Academia, Chapter 161'};wsjModalPromoId='wsj_subscribe_modal_16683';wsjModalSource='My Hero Academia, Chapter 161';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16683,'/shonenjump/my-hero-academia-chapter-161/chapter/16683?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16707"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1600">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-160/chapter/16707?action=read',targetTitle:'My Hero Academia, Chapter 160'};wsjModalPromoId='wsj_subscribe_modal_16707';wsjModalSource='My Hero Academia, Chapter 160';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16707,'/shonenjump/my-hero-academia-chapter-160/chapter/16707?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 160
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-160/chapter/16707?action=read',targetTitle:'My Hero Academia, Chapter 160'};wsjModalPromoId='wsj_subscribe_modal_16707';wsjModalSource='My Hero Academia, Chapter 160';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16707,'/shonenjump/my-hero-academia-chapter-160/chapter/16707?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-160/chapter/16707?action=read',targetTitle:'My Hero Academia, Chapter 160'};wsjModalPromoId='wsj_subscribe_modal_16707';wsjModalSource='My Hero Academia, Chapter 160';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16707,'/shonenjump/my-hero-academia-chapter-160/chapter/16707?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16681"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1590">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-159/chapter/16681?action=read',targetTitle:'My Hero Academia, Chapter 159'};wsjModalPromoId='wsj_subscribe_modal_16681';wsjModalSource='My Hero Academia, Chapter 159';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16681,'/shonenjump/my-hero-academia-chapter-159/chapter/16681?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 159
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-159/chapter/16681?action=read',targetTitle:'My Hero Academia, Chapter 159'};wsjModalPromoId='wsj_subscribe_modal_16681';wsjModalSource='My Hero Academia, Chapter 159';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16681,'/shonenjump/my-hero-academia-chapter-159/chapter/16681?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-159/chapter/16681?action=read',targetTitle:'My Hero Academia, Chapter 159'};wsjModalPromoId='wsj_subscribe_modal_16681';wsjModalSource='My Hero Academia, Chapter 159';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16681,'/shonenjump/my-hero-academia-chapter-159/chapter/16681?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16703"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1580">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-158/chapter/16703?action=read',targetTitle:'My Hero Academia, Chapter 158'};wsjModalPromoId='wsj_subscribe_modal_16703';wsjModalSource='My Hero Academia, Chapter 158';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16703,'/shonenjump/my-hero-academia-chapter-158/chapter/16703?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 158
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-158/chapter/16703?action=read',targetTitle:'My Hero Academia, Chapter 158'};wsjModalPromoId='wsj_subscribe_modal_16703';wsjModalSource='My Hero Academia, Chapter 158';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16703,'/shonenjump/my-hero-academia-chapter-158/chapter/16703?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-158/chapter/16703?action=read',targetTitle:'My Hero Academia, Chapter 158'};wsjModalPromoId='wsj_subscribe_modal_16703';wsjModalSource='My Hero Academia, Chapter 158';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16703,'/shonenjump/my-hero-academia-chapter-158/chapter/16703?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="50"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="1570">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-17/product/5820/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1974702561.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-17/product/5820/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16651"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1570">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-157/chapter/16651?action=read',targetTitle:'My Hero Academia, Chapter 157'};wsjModalPromoId='wsj_subscribe_modal_16651';wsjModalSource='My Hero Academia, Chapter 157';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16651,'/shonenjump/my-hero-academia-chapter-157/chapter/16651?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 157
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-157/chapter/16651?action=read',targetTitle:'My Hero Academia, Chapter 157'};wsjModalPromoId='wsj_subscribe_modal_16651';wsjModalSource='My Hero Academia, Chapter 157';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16651,'/shonenjump/my-hero-academia-chapter-157/chapter/16651?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-157/chapter/16651?action=read',targetTitle:'My Hero Academia, Chapter 157'};wsjModalPromoId='wsj_subscribe_modal_16651';wsjModalSource='My Hero Academia, Chapter 157';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16651,'/shonenjump/my-hero-academia-chapter-157/chapter/16651?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16702"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1560">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-156/chapter/16702?action=read',targetTitle:'My Hero Academia, Chapter 156'};wsjModalPromoId='wsj_subscribe_modal_16702';wsjModalSource='My Hero Academia, Chapter 156';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16702,'/shonenjump/my-hero-academia-chapter-156/chapter/16702?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 156
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-156/chapter/16702?action=read',targetTitle:'My Hero Academia, Chapter 156'};wsjModalPromoId='wsj_subscribe_modal_16702';wsjModalSource='My Hero Academia, Chapter 156';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16702,'/shonenjump/my-hero-academia-chapter-156/chapter/16702?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-156/chapter/16702?action=read',targetTitle:'My Hero Academia, Chapter 156'};wsjModalPromoId='wsj_subscribe_modal_16702';wsjModalSource='My Hero Academia, Chapter 156';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16702,'/shonenjump/my-hero-academia-chapter-156/chapter/16702?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16720"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1550">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-155/chapter/16720?action=read',targetTitle:'My Hero Academia, Chapter 155'};wsjModalPromoId='wsj_subscribe_modal_16720';wsjModalSource='My Hero Academia, Chapter 155';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16720,'/shonenjump/my-hero-academia-chapter-155/chapter/16720?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 155
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-155/chapter/16720?action=read',targetTitle:'My Hero Academia, Chapter 155'};wsjModalPromoId='wsj_subscribe_modal_16720';wsjModalSource='My Hero Academia, Chapter 155';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16720,'/shonenjump/my-hero-academia-chapter-155/chapter/16720?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-155/chapter/16720?action=read',targetTitle:'My Hero Academia, Chapter 155'};wsjModalPromoId='wsj_subscribe_modal_16720';wsjModalSource='My Hero Academia, Chapter 155';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16720,'/shonenjump/my-hero-academia-chapter-155/chapter/16720?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16671"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1540">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-154/chapter/16671?action=read',targetTitle:'My Hero Academia, Chapter 154'};wsjModalPromoId='wsj_subscribe_modal_16671';wsjModalSource='My Hero Academia, Chapter 154';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16671,'/shonenjump/my-hero-academia-chapter-154/chapter/16671?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 154
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-154/chapter/16671?action=read',targetTitle:'My Hero Academia, Chapter 154'};wsjModalPromoId='wsj_subscribe_modal_16671';wsjModalSource='My Hero Academia, Chapter 154';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16671,'/shonenjump/my-hero-academia-chapter-154/chapter/16671?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-154/chapter/16671?action=read',targetTitle:'My Hero Academia, Chapter 154'};wsjModalPromoId='wsj_subscribe_modal_16671';wsjModalSource='My Hero Academia, Chapter 154';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16671,'/shonenjump/my-hero-academia-chapter-154/chapter/16671?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16680"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1530">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-153/chapter/16680?action=read',targetTitle:'My Hero Academia, Chapter 153'};wsjModalPromoId='wsj_subscribe_modal_16680';wsjModalSource='My Hero Academia, Chapter 153';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16680,'/shonenjump/my-hero-academia-chapter-153/chapter/16680?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 153
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-153/chapter/16680?action=read',targetTitle:'My Hero Academia, Chapter 153'};wsjModalPromoId='wsj_subscribe_modal_16680';wsjModalSource='My Hero Academia, Chapter 153';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16680,'/shonenjump/my-hero-academia-chapter-153/chapter/16680?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-153/chapter/16680?action=read',targetTitle:'My Hero Academia, Chapter 153'};wsjModalPromoId='wsj_subscribe_modal_16680';wsjModalSource='My Hero Academia, Chapter 153';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16680,'/shonenjump/my-hero-academia-chapter-153/chapter/16680?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16704"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1520">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-152/chapter/16704?action=read',targetTitle:'My Hero Academia, Chapter 152'};wsjModalPromoId='wsj_subscribe_modal_16704';wsjModalSource='My Hero Academia, Chapter 152';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16704,'/shonenjump/my-hero-academia-chapter-152/chapter/16704?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 152
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-152/chapter/16704?action=read',targetTitle:'My Hero Academia, Chapter 152'};wsjModalPromoId='wsj_subscribe_modal_16704';wsjModalSource='My Hero Academia, Chapter 152';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16704,'/shonenjump/my-hero-academia-chapter-152/chapter/16704?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-152/chapter/16704?action=read',targetTitle:'My Hero Academia, Chapter 152'};wsjModalPromoId='wsj_subscribe_modal_16704';wsjModalSource='My Hero Academia, Chapter 152';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16704,'/shonenjump/my-hero-academia-chapter-152/chapter/16704?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16686"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1510">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-151/chapter/16686?action=read',targetTitle:'My Hero Academia, Chapter 151'};wsjModalPromoId='wsj_subscribe_modal_16686';wsjModalSource='My Hero Academia, Chapter 151';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16686,'/shonenjump/my-hero-academia-chapter-151/chapter/16686?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 151
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-151/chapter/16686?action=read',targetTitle:'My Hero Academia, Chapter 151'};wsjModalPromoId='wsj_subscribe_modal_16686';wsjModalSource='My Hero Academia, Chapter 151';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16686,'/shonenjump/my-hero-academia-chapter-151/chapter/16686?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-151/chapter/16686?action=read',targetTitle:'My Hero Academia, Chapter 151'};wsjModalPromoId='wsj_subscribe_modal_16686';wsjModalSource='My Hero Academia, Chapter 151';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16686,'/shonenjump/my-hero-academia-chapter-151/chapter/16686?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16663"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1500">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-150/chapter/16663?action=read',targetTitle:'My Hero Academia, Chapter 150'};wsjModalPromoId='wsj_subscribe_modal_16663';wsjModalSource='My Hero Academia, Chapter 150';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16663,'/shonenjump/my-hero-academia-chapter-150/chapter/16663?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 150
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-150/chapter/16663?action=read',targetTitle:'My Hero Academia, Chapter 150'};wsjModalPromoId='wsj_subscribe_modal_16663';wsjModalSource='My Hero Academia, Chapter 150';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16663,'/shonenjump/my-hero-academia-chapter-150/chapter/16663?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-150/chapter/16663?action=read',targetTitle:'My Hero Academia, Chapter 150'};wsjModalPromoId='wsj_subscribe_modal_16663';wsjModalSource='My Hero Academia, Chapter 150';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16663,'/shonenjump/my-hero-academia-chapter-150/chapter/16663?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16659"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1490">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-149/chapter/16659?action=read',targetTitle:'My Hero Academia, Chapter 149'};wsjModalPromoId='wsj_subscribe_modal_16659';wsjModalSource='My Hero Academia, Chapter 149';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16659,'/shonenjump/my-hero-academia-chapter-149/chapter/16659?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 149
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-149/chapter/16659?action=read',targetTitle:'My Hero Academia, Chapter 149'};wsjModalPromoId='wsj_subscribe_modal_16659';wsjModalSource='My Hero Academia, Chapter 149';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16659,'/shonenjump/my-hero-academia-chapter-149/chapter/16659?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-149/chapter/16659?action=read',targetTitle:'My Hero Academia, Chapter 149'};wsjModalPromoId='wsj_subscribe_modal_16659';wsjModalSource='My Hero Academia, Chapter 149';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16659,'/shonenjump/my-hero-academia-chapter-149/chapter/16659?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16691"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1480">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-148/chapter/16691?action=read',targetTitle:'My Hero Academia, Chapter 148'};wsjModalPromoId='wsj_subscribe_modal_16691';wsjModalSource='My Hero Academia, Chapter 148';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16691,'/shonenjump/my-hero-academia-chapter-148/chapter/16691?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 148
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-148/chapter/16691?action=read',targetTitle:'My Hero Academia, Chapter 148'};wsjModalPromoId='wsj_subscribe_modal_16691';wsjModalSource='My Hero Academia, Chapter 148';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16691,'/shonenjump/my-hero-academia-chapter-148/chapter/16691?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-148/chapter/16691?action=read',targetTitle:'My Hero Academia, Chapter 148'};wsjModalPromoId='wsj_subscribe_modal_16691';wsjModalSource='My Hero Academia, Chapter 148';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16691,'/shonenjump/my-hero-academia-chapter-148/chapter/16691?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="51"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="1470">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-16/product/5756/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1974702553.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-16/product/5756/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16965"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1470">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-147/chapter/16965?action=read',targetTitle:'My Hero Academia, Chapter 147'};wsjModalPromoId='wsj_subscribe_modal_16965';wsjModalSource='My Hero Academia, Chapter 147';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16965,'/shonenjump/my-hero-academia-chapter-147/chapter/16965?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 147
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-147/chapter/16965?action=read',targetTitle:'My Hero Academia, Chapter 147'};wsjModalPromoId='wsj_subscribe_modal_16965';wsjModalSource='My Hero Academia, Chapter 147';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16965,'/shonenjump/my-hero-academia-chapter-147/chapter/16965?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-147/chapter/16965?action=read',targetTitle:'My Hero Academia, Chapter 147'};wsjModalPromoId='wsj_subscribe_modal_16965';wsjModalSource='My Hero Academia, Chapter 147';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16965,'/shonenjump/my-hero-academia-chapter-147/chapter/16965?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16964"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1460">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-146/chapter/16964?action=read',targetTitle:'My Hero Academia, Chapter 146'};wsjModalPromoId='wsj_subscribe_modal_16964';wsjModalSource='My Hero Academia, Chapter 146';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16964,'/shonenjump/my-hero-academia-chapter-146/chapter/16964?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 146
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-146/chapter/16964?action=read',targetTitle:'My Hero Academia, Chapter 146'};wsjModalPromoId='wsj_subscribe_modal_16964';wsjModalSource='My Hero Academia, Chapter 146';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16964,'/shonenjump/my-hero-academia-chapter-146/chapter/16964?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-146/chapter/16964?action=read',targetTitle:'My Hero Academia, Chapter 146'};wsjModalPromoId='wsj_subscribe_modal_16964';wsjModalSource='My Hero Academia, Chapter 146';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16964,'/shonenjump/my-hero-academia-chapter-146/chapter/16964?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16963"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1450">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-145/chapter/16963?action=read',targetTitle:'My Hero Academia, Chapter 145'};wsjModalPromoId='wsj_subscribe_modal_16963';wsjModalSource='My Hero Academia, Chapter 145';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16963,'/shonenjump/my-hero-academia-chapter-145/chapter/16963?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 145
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-145/chapter/16963?action=read',targetTitle:'My Hero Academia, Chapter 145'};wsjModalPromoId='wsj_subscribe_modal_16963';wsjModalSource='My Hero Academia, Chapter 145';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16963,'/shonenjump/my-hero-academia-chapter-145/chapter/16963?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-145/chapter/16963?action=read',targetTitle:'My Hero Academia, Chapter 145'};wsjModalPromoId='wsj_subscribe_modal_16963';wsjModalSource='My Hero Academia, Chapter 145';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16963,'/shonenjump/my-hero-academia-chapter-145/chapter/16963?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16962"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1440">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-144/chapter/16962?action=read',targetTitle:'My Hero Academia, Chapter 144'};wsjModalPromoId='wsj_subscribe_modal_16962';wsjModalSource='My Hero Academia, Chapter 144';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16962,'/shonenjump/my-hero-academia-chapter-144/chapter/16962?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 144
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-144/chapter/16962?action=read',targetTitle:'My Hero Academia, Chapter 144'};wsjModalPromoId='wsj_subscribe_modal_16962';wsjModalSource='My Hero Academia, Chapter 144';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16962,'/shonenjump/my-hero-academia-chapter-144/chapter/16962?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-144/chapter/16962?action=read',targetTitle:'My Hero Academia, Chapter 144'};wsjModalPromoId='wsj_subscribe_modal_16962';wsjModalSource='My Hero Academia, Chapter 144';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16962,'/shonenjump/my-hero-academia-chapter-144/chapter/16962?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16961"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1430">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-143/chapter/16961?action=read',targetTitle:'My Hero Academia, Chapter 143'};wsjModalPromoId='wsj_subscribe_modal_16961';wsjModalSource='My Hero Academia, Chapter 143';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16961,'/shonenjump/my-hero-academia-chapter-143/chapter/16961?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 143
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-143/chapter/16961?action=read',targetTitle:'My Hero Academia, Chapter 143'};wsjModalPromoId='wsj_subscribe_modal_16961';wsjModalSource='My Hero Academia, Chapter 143';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16961,'/shonenjump/my-hero-academia-chapter-143/chapter/16961?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-143/chapter/16961?action=read',targetTitle:'My Hero Academia, Chapter 143'};wsjModalPromoId='wsj_subscribe_modal_16961';wsjModalSource='My Hero Academia, Chapter 143';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16961,'/shonenjump/my-hero-academia-chapter-143/chapter/16961?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16960"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1420">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-142/chapter/16960?action=read',targetTitle:'My Hero Academia, Chapter 142'};wsjModalPromoId='wsj_subscribe_modal_16960';wsjModalSource='My Hero Academia, Chapter 142';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16960,'/shonenjump/my-hero-academia-chapter-142/chapter/16960?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 142
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-142/chapter/16960?action=read',targetTitle:'My Hero Academia, Chapter 142'};wsjModalPromoId='wsj_subscribe_modal_16960';wsjModalSource='My Hero Academia, Chapter 142';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16960,'/shonenjump/my-hero-academia-chapter-142/chapter/16960?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-142/chapter/16960?action=read',targetTitle:'My Hero Academia, Chapter 142'};wsjModalPromoId='wsj_subscribe_modal_16960';wsjModalSource='My Hero Academia, Chapter 142';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16960,'/shonenjump/my-hero-academia-chapter-142/chapter/16960?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16959"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1410">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-141/chapter/16959?action=read',targetTitle:'My Hero Academia, Chapter 141'};wsjModalPromoId='wsj_subscribe_modal_16959';wsjModalSource='My Hero Academia, Chapter 141';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16959,'/shonenjump/my-hero-academia-chapter-141/chapter/16959?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 141
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-141/chapter/16959?action=read',targetTitle:'My Hero Academia, Chapter 141'};wsjModalPromoId='wsj_subscribe_modal_16959';wsjModalSource='My Hero Academia, Chapter 141';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16959,'/shonenjump/my-hero-academia-chapter-141/chapter/16959?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-141/chapter/16959?action=read',targetTitle:'My Hero Academia, Chapter 141'};wsjModalPromoId='wsj_subscribe_modal_16959';wsjModalSource='My Hero Academia, Chapter 141';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16959,'/shonenjump/my-hero-academia-chapter-141/chapter/16959?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16958"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1400">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-140/chapter/16958?action=read',targetTitle:'My Hero Academia, Chapter 140'};wsjModalPromoId='wsj_subscribe_modal_16958';wsjModalSource='My Hero Academia, Chapter 140';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16958,'/shonenjump/my-hero-academia-chapter-140/chapter/16958?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 140
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-140/chapter/16958?action=read',targetTitle:'My Hero Academia, Chapter 140'};wsjModalPromoId='wsj_subscribe_modal_16958';wsjModalSource='My Hero Academia, Chapter 140';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16958,'/shonenjump/my-hero-academia-chapter-140/chapter/16958?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-140/chapter/16958?action=read',targetTitle:'My Hero Academia, Chapter 140'};wsjModalPromoId='wsj_subscribe_modal_16958';wsjModalSource='My Hero Academia, Chapter 140';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16958,'/shonenjump/my-hero-academia-chapter-140/chapter/16958?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16957"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1390">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-139/chapter/16957?action=read',targetTitle:'My Hero Academia, Chapter 139'};wsjModalPromoId='wsj_subscribe_modal_16957';wsjModalSource='My Hero Academia, Chapter 139';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16957,'/shonenjump/my-hero-academia-chapter-139/chapter/16957?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 139
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-139/chapter/16957?action=read',targetTitle:'My Hero Academia, Chapter 139'};wsjModalPromoId='wsj_subscribe_modal_16957';wsjModalSource='My Hero Academia, Chapter 139';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16957,'/shonenjump/my-hero-academia-chapter-139/chapter/16957?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-139/chapter/16957?action=read',targetTitle:'My Hero Academia, Chapter 139'};wsjModalPromoId='wsj_subscribe_modal_16957';wsjModalSource='My Hero Academia, Chapter 139';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16957,'/shonenjump/my-hero-academia-chapter-139/chapter/16957?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16956"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1380">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-138/chapter/16956?action=read',targetTitle:'My Hero Academia, Chapter 138'};wsjModalPromoId='wsj_subscribe_modal_16956';wsjModalSource='My Hero Academia, Chapter 138';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16956,'/shonenjump/my-hero-academia-chapter-138/chapter/16956?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 138
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-138/chapter/16956?action=read',targetTitle:'My Hero Academia, Chapter 138'};wsjModalPromoId='wsj_subscribe_modal_16956';wsjModalSource='My Hero Academia, Chapter 138';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16956,'/shonenjump/my-hero-academia-chapter-138/chapter/16956?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-138/chapter/16956?action=read',targetTitle:'My Hero Academia, Chapter 138'};wsjModalPromoId='wsj_subscribe_modal_16956';wsjModalSource='My Hero Academia, Chapter 138';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16956,'/shonenjump/my-hero-academia-chapter-138/chapter/16956?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="52"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="1370">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-15/product/5669/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/197470100X.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-15/product/5669/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16181"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1370">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-137/chapter/16181?action=read',targetTitle:'My Hero Academia, Chapter 137'};wsjModalPromoId='wsj_subscribe_modal_16181';wsjModalSource='My Hero Academia, Chapter 137';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16181,'/shonenjump/my-hero-academia-chapter-137/chapter/16181?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 137
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-137/chapter/16181?action=read',targetTitle:'My Hero Academia, Chapter 137'};wsjModalPromoId='wsj_subscribe_modal_16181';wsjModalSource='My Hero Academia, Chapter 137';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16181,'/shonenjump/my-hero-academia-chapter-137/chapter/16181?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-137/chapter/16181?action=read',targetTitle:'My Hero Academia, Chapter 137'};wsjModalPromoId='wsj_subscribe_modal_16181';wsjModalSource='My Hero Academia, Chapter 137';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16181,'/shonenjump/my-hero-academia-chapter-137/chapter/16181?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16180"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1360">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-136/chapter/16180?action=read',targetTitle:'My Hero Academia, Chapter 136'};wsjModalPromoId='wsj_subscribe_modal_16180';wsjModalSource='My Hero Academia, Chapter 136';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16180,'/shonenjump/my-hero-academia-chapter-136/chapter/16180?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 136
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-136/chapter/16180?action=read',targetTitle:'My Hero Academia, Chapter 136'};wsjModalPromoId='wsj_subscribe_modal_16180';wsjModalSource='My Hero Academia, Chapter 136';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16180,'/shonenjump/my-hero-academia-chapter-136/chapter/16180?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-136/chapter/16180?action=read',targetTitle:'My Hero Academia, Chapter 136'};wsjModalPromoId='wsj_subscribe_modal_16180';wsjModalSource='My Hero Academia, Chapter 136';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16180,'/shonenjump/my-hero-academia-chapter-136/chapter/16180?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16179"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1350">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-135/chapter/16179?action=read',targetTitle:'My Hero Academia, Chapter 135'};wsjModalPromoId='wsj_subscribe_modal_16179';wsjModalSource='My Hero Academia, Chapter 135';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16179,'/shonenjump/my-hero-academia-chapter-135/chapter/16179?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 135
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-135/chapter/16179?action=read',targetTitle:'My Hero Academia, Chapter 135'};wsjModalPromoId='wsj_subscribe_modal_16179';wsjModalSource='My Hero Academia, Chapter 135';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16179,'/shonenjump/my-hero-academia-chapter-135/chapter/16179?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-135/chapter/16179?action=read',targetTitle:'My Hero Academia, Chapter 135'};wsjModalPromoId='wsj_subscribe_modal_16179';wsjModalSource='My Hero Academia, Chapter 135';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16179,'/shonenjump/my-hero-academia-chapter-135/chapter/16179?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16178"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1340">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-134/chapter/16178?action=read',targetTitle:'My Hero Academia, Chapter 134'};wsjModalPromoId='wsj_subscribe_modal_16178';wsjModalSource='My Hero Academia, Chapter 134';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16178,'/shonenjump/my-hero-academia-chapter-134/chapter/16178?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 134
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-134/chapter/16178?action=read',targetTitle:'My Hero Academia, Chapter 134'};wsjModalPromoId='wsj_subscribe_modal_16178';wsjModalSource='My Hero Academia, Chapter 134';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16178,'/shonenjump/my-hero-academia-chapter-134/chapter/16178?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-134/chapter/16178?action=read',targetTitle:'My Hero Academia, Chapter 134'};wsjModalPromoId='wsj_subscribe_modal_16178';wsjModalSource='My Hero Academia, Chapter 134';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16178,'/shonenjump/my-hero-academia-chapter-134/chapter/16178?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16177"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1330">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-133/chapter/16177?action=read',targetTitle:'My Hero Academia, Chapter 133'};wsjModalPromoId='wsj_subscribe_modal_16177';wsjModalSource='My Hero Academia, Chapter 133';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16177,'/shonenjump/my-hero-academia-chapter-133/chapter/16177?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 133
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-133/chapter/16177?action=read',targetTitle:'My Hero Academia, Chapter 133'};wsjModalPromoId='wsj_subscribe_modal_16177';wsjModalSource='My Hero Academia, Chapter 133';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16177,'/shonenjump/my-hero-academia-chapter-133/chapter/16177?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-133/chapter/16177?action=read',targetTitle:'My Hero Academia, Chapter 133'};wsjModalPromoId='wsj_subscribe_modal_16177';wsjModalSource='My Hero Academia, Chapter 133';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16177,'/shonenjump/my-hero-academia-chapter-133/chapter/16177?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16176"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1320">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-132/chapter/16176?action=read',targetTitle:'My Hero Academia, Chapter 132'};wsjModalPromoId='wsj_subscribe_modal_16176';wsjModalSource='My Hero Academia, Chapter 132';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16176,'/shonenjump/my-hero-academia-chapter-132/chapter/16176?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 132
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-132/chapter/16176?action=read',targetTitle:'My Hero Academia, Chapter 132'};wsjModalPromoId='wsj_subscribe_modal_16176';wsjModalSource='My Hero Academia, Chapter 132';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16176,'/shonenjump/my-hero-academia-chapter-132/chapter/16176?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-132/chapter/16176?action=read',targetTitle:'My Hero Academia, Chapter 132'};wsjModalPromoId='wsj_subscribe_modal_16176';wsjModalSource='My Hero Academia, Chapter 132';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16176,'/shonenjump/my-hero-academia-chapter-132/chapter/16176?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16175"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1310">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-131/chapter/16175?action=read',targetTitle:'My Hero Academia, Chapter 131'};wsjModalPromoId='wsj_subscribe_modal_16175';wsjModalSource='My Hero Academia, Chapter 131';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16175,'/shonenjump/my-hero-academia-chapter-131/chapter/16175?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 131
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-131/chapter/16175?action=read',targetTitle:'My Hero Academia, Chapter 131'};wsjModalPromoId='wsj_subscribe_modal_16175';wsjModalSource='My Hero Academia, Chapter 131';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16175,'/shonenjump/my-hero-academia-chapter-131/chapter/16175?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-131/chapter/16175?action=read',targetTitle:'My Hero Academia, Chapter 131'};wsjModalPromoId='wsj_subscribe_modal_16175';wsjModalSource='My Hero Academia, Chapter 131';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16175,'/shonenjump/my-hero-academia-chapter-131/chapter/16175?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16174"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1300">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-130/chapter/16174?action=read',targetTitle:'My Hero Academia, Chapter 130'};wsjModalPromoId='wsj_subscribe_modal_16174';wsjModalSource='My Hero Academia, Chapter 130';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16174,'/shonenjump/my-hero-academia-chapter-130/chapter/16174?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 130
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-130/chapter/16174?action=read',targetTitle:'My Hero Academia, Chapter 130'};wsjModalPromoId='wsj_subscribe_modal_16174';wsjModalSource='My Hero Academia, Chapter 130';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16174,'/shonenjump/my-hero-academia-chapter-130/chapter/16174?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-130/chapter/16174?action=read',targetTitle:'My Hero Academia, Chapter 130'};wsjModalPromoId='wsj_subscribe_modal_16174';wsjModalSource='My Hero Academia, Chapter 130';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16174,'/shonenjump/my-hero-academia-chapter-130/chapter/16174?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="16173"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1290">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-129/chapter/16173?action=read',targetTitle:'My Hero Academia, Chapter 129'};wsjModalPromoId='wsj_subscribe_modal_16173';wsjModalSource='My Hero Academia, Chapter 129';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16173,'/shonenjump/my-hero-academia-chapter-129/chapter/16173?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 129
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-129/chapter/16173?action=read',targetTitle:'My Hero Academia, Chapter 129'};wsjModalPromoId='wsj_subscribe_modal_16173';wsjModalSource='My Hero Academia, Chapter 129';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16173,'/shonenjump/my-hero-academia-chapter-129/chapter/16173?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-129/chapter/16173?action=read',targetTitle:'My Hero Academia, Chapter 129'};wsjModalPromoId='wsj_subscribe_modal_16173';wsjModalSource='My Hero Academia, Chapter 129';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(16173,'/shonenjump/my-hero-academia-chapter-129/chapter/16173?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="53"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="1280">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-14/product/5583/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421599473.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-14/product/5583/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8697"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1280">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-128/chapter/8697?action=read',targetTitle:'My Hero Academia, Chapter 128'};wsjModalPromoId='wsj_subscribe_modal_8697';wsjModalSource='My Hero Academia, Chapter 128';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8697,'/shonenjump/my-hero-academia-chapter-128/chapter/8697?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 128
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-128/chapter/8697?action=read',targetTitle:'My Hero Academia, Chapter 128'};wsjModalPromoId='wsj_subscribe_modal_8697';wsjModalSource='My Hero Academia, Chapter 128';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8697,'/shonenjump/my-hero-academia-chapter-128/chapter/8697?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-128/chapter/8697?action=read',targetTitle:'My Hero Academia, Chapter 128'};wsjModalPromoId='wsj_subscribe_modal_8697';wsjModalSource='My Hero Academia, Chapter 128';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8697,'/shonenjump/my-hero-academia-chapter-128/chapter/8697?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8696"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1270">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-127/chapter/8696?action=read',targetTitle:'My Hero Academia, Chapter 127'};wsjModalPromoId='wsj_subscribe_modal_8696';wsjModalSource='My Hero Academia, Chapter 127';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8696,'/shonenjump/my-hero-academia-chapter-127/chapter/8696?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 127
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-127/chapter/8696?action=read',targetTitle:'My Hero Academia, Chapter 127'};wsjModalPromoId='wsj_subscribe_modal_8696';wsjModalSource='My Hero Academia, Chapter 127';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8696,'/shonenjump/my-hero-academia-chapter-127/chapter/8696?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-127/chapter/8696?action=read',targetTitle:'My Hero Academia, Chapter 127'};wsjModalPromoId='wsj_subscribe_modal_8696';wsjModalSource='My Hero Academia, Chapter 127';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8696,'/shonenjump/my-hero-academia-chapter-127/chapter/8696?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8695"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1260">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-126/chapter/8695?action=read',targetTitle:'My Hero Academia, Chapter 126'};wsjModalPromoId='wsj_subscribe_modal_8695';wsjModalSource='My Hero Academia, Chapter 126';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8695,'/shonenjump/my-hero-academia-chapter-126/chapter/8695?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 126
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-126/chapter/8695?action=read',targetTitle:'My Hero Academia, Chapter 126'};wsjModalPromoId='wsj_subscribe_modal_8695';wsjModalSource='My Hero Academia, Chapter 126';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8695,'/shonenjump/my-hero-academia-chapter-126/chapter/8695?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-126/chapter/8695?action=read',targetTitle:'My Hero Academia, Chapter 126'};wsjModalPromoId='wsj_subscribe_modal_8695';wsjModalSource='My Hero Academia, Chapter 126';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8695,'/shonenjump/my-hero-academia-chapter-126/chapter/8695?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8694"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1250">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-125/chapter/8694?action=read',targetTitle:'My Hero Academia, Chapter 125'};wsjModalPromoId='wsj_subscribe_modal_8694';wsjModalSource='My Hero Academia, Chapter 125';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8694,'/shonenjump/my-hero-academia-chapter-125/chapter/8694?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 125
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-125/chapter/8694?action=read',targetTitle:'My Hero Academia, Chapter 125'};wsjModalPromoId='wsj_subscribe_modal_8694';wsjModalSource='My Hero Academia, Chapter 125';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8694,'/shonenjump/my-hero-academia-chapter-125/chapter/8694?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-125/chapter/8694?action=read',targetTitle:'My Hero Academia, Chapter 125'};wsjModalPromoId='wsj_subscribe_modal_8694';wsjModalSource='My Hero Academia, Chapter 125';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8694,'/shonenjump/my-hero-academia-chapter-125/chapter/8694?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8693"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1240">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-124/chapter/8693?action=read',targetTitle:'My Hero Academia, Chapter 124'};wsjModalPromoId='wsj_subscribe_modal_8693';wsjModalSource='My Hero Academia, Chapter 124';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8693,'/shonenjump/my-hero-academia-chapter-124/chapter/8693?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 124
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-124/chapter/8693?action=read',targetTitle:'My Hero Academia, Chapter 124'};wsjModalPromoId='wsj_subscribe_modal_8693';wsjModalSource='My Hero Academia, Chapter 124';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8693,'/shonenjump/my-hero-academia-chapter-124/chapter/8693?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-124/chapter/8693?action=read',targetTitle:'My Hero Academia, Chapter 124'};wsjModalPromoId='wsj_subscribe_modal_8693';wsjModalSource='My Hero Academia, Chapter 124';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8693,'/shonenjump/my-hero-academia-chapter-124/chapter/8693?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8692"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1230">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-123/chapter/8692?action=read',targetTitle:'My Hero Academia, Chapter 123'};wsjModalPromoId='wsj_subscribe_modal_8692';wsjModalSource='My Hero Academia, Chapter 123';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8692,'/shonenjump/my-hero-academia-chapter-123/chapter/8692?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 123
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-123/chapter/8692?action=read',targetTitle:'My Hero Academia, Chapter 123'};wsjModalPromoId='wsj_subscribe_modal_8692';wsjModalSource='My Hero Academia, Chapter 123';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8692,'/shonenjump/my-hero-academia-chapter-123/chapter/8692?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-123/chapter/8692?action=read',targetTitle:'My Hero Academia, Chapter 123'};wsjModalPromoId='wsj_subscribe_modal_8692';wsjModalSource='My Hero Academia, Chapter 123';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8692,'/shonenjump/my-hero-academia-chapter-123/chapter/8692?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8691"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1220">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-122/chapter/8691?action=read',targetTitle:'My Hero Academia, Chapter 122'};wsjModalPromoId='wsj_subscribe_modal_8691';wsjModalSource='My Hero Academia, Chapter 122';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8691,'/shonenjump/my-hero-academia-chapter-122/chapter/8691?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 122
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-122/chapter/8691?action=read',targetTitle:'My Hero Academia, Chapter 122'};wsjModalPromoId='wsj_subscribe_modal_8691';wsjModalSource='My Hero Academia, Chapter 122';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8691,'/shonenjump/my-hero-academia-chapter-122/chapter/8691?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-122/chapter/8691?action=read',targetTitle:'My Hero Academia, Chapter 122'};wsjModalPromoId='wsj_subscribe_modal_8691';wsjModalSource='My Hero Academia, Chapter 122';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8691,'/shonenjump/my-hero-academia-chapter-122/chapter/8691?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8690"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1210">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-121/chapter/8690?action=read',targetTitle:'My Hero Academia, Chapter 121'};wsjModalPromoId='wsj_subscribe_modal_8690';wsjModalSource='My Hero Academia, Chapter 121';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8690,'/shonenjump/my-hero-academia-chapter-121/chapter/8690?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 121
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-121/chapter/8690?action=read',targetTitle:'My Hero Academia, Chapter 121'};wsjModalPromoId='wsj_subscribe_modal_8690';wsjModalSource='My Hero Academia, Chapter 121';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8690,'/shonenjump/my-hero-academia-chapter-121/chapter/8690?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-121/chapter/8690?action=read',targetTitle:'My Hero Academia, Chapter 121'};wsjModalPromoId='wsj_subscribe_modal_8690';wsjModalSource='My Hero Academia, Chapter 121';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8690,'/shonenjump/my-hero-academia-chapter-121/chapter/8690?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8689"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1200">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-120/chapter/8689?action=read',targetTitle:'My Hero Academia, Chapter 120'};wsjModalPromoId='wsj_subscribe_modal_8689';wsjModalSource='My Hero Academia, Chapter 120';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8689,'/shonenjump/my-hero-academia-chapter-120/chapter/8689?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 120
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-120/chapter/8689?action=read',targetTitle:'My Hero Academia, Chapter 120'};wsjModalPromoId='wsj_subscribe_modal_8689';wsjModalSource='My Hero Academia, Chapter 120';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8689,'/shonenjump/my-hero-academia-chapter-120/chapter/8689?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-120/chapter/8689?action=read',targetTitle:'My Hero Academia, Chapter 120'};wsjModalPromoId='wsj_subscribe_modal_8689';wsjModalSource='My Hero Academia, Chapter 120';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8689,'/shonenjump/my-hero-academia-chapter-120/chapter/8689?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8688"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1190">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-119/chapter/8688?action=read',targetTitle:'My Hero Academia, Chapter 119'};wsjModalPromoId='wsj_subscribe_modal_8688';wsjModalSource='My Hero Academia, Chapter 119';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8688,'/shonenjump/my-hero-academia-chapter-119/chapter/8688?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 119
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-119/chapter/8688?action=read',targetTitle:'My Hero Academia, Chapter 119'};wsjModalPromoId='wsj_subscribe_modal_8688';wsjModalSource='My Hero Academia, Chapter 119';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8688,'/shonenjump/my-hero-academia-chapter-119/chapter/8688?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-119/chapter/8688?action=read',targetTitle:'My Hero Academia, Chapter 119'};wsjModalPromoId='wsj_subscribe_modal_8688';wsjModalSource='My Hero Academia, Chapter 119';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8688,'/shonenjump/my-hero-academia-chapter-119/chapter/8688?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="54"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="1180">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-13/product/5522/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421598035.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-13/product/5522/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8677"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1180">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-118/chapter/8677?action=read',targetTitle:'My Hero Academia, Chapter 118'};wsjModalPromoId='wsj_subscribe_modal_8677';wsjModalSource='My Hero Academia, Chapter 118';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8677,'/shonenjump/my-hero-academia-chapter-118/chapter/8677?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 118
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-118/chapter/8677?action=read',targetTitle:'My Hero Academia, Chapter 118'};wsjModalPromoId='wsj_subscribe_modal_8677';wsjModalSource='My Hero Academia, Chapter 118';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8677,'/shonenjump/my-hero-academia-chapter-118/chapter/8677?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-118/chapter/8677?action=read',targetTitle:'My Hero Academia, Chapter 118'};wsjModalPromoId='wsj_subscribe_modal_8677';wsjModalSource='My Hero Academia, Chapter 118';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8677,'/shonenjump/my-hero-academia-chapter-118/chapter/8677?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8676"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1170">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-117/chapter/8676?action=read',targetTitle:'My Hero Academia, Chapter 117'};wsjModalPromoId='wsj_subscribe_modal_8676';wsjModalSource='My Hero Academia, Chapter 117';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8676,'/shonenjump/my-hero-academia-chapter-117/chapter/8676?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 117
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-117/chapter/8676?action=read',targetTitle:'My Hero Academia, Chapter 117'};wsjModalPromoId='wsj_subscribe_modal_8676';wsjModalSource='My Hero Academia, Chapter 117';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8676,'/shonenjump/my-hero-academia-chapter-117/chapter/8676?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-117/chapter/8676?action=read',targetTitle:'My Hero Academia, Chapter 117'};wsjModalPromoId='wsj_subscribe_modal_8676';wsjModalSource='My Hero Academia, Chapter 117';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8676,'/shonenjump/my-hero-academia-chapter-117/chapter/8676?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8675"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1160">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-116/chapter/8675?action=read',targetTitle:'My Hero Academia, Chapter 116'};wsjModalPromoId='wsj_subscribe_modal_8675';wsjModalSource='My Hero Academia, Chapter 116';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8675,'/shonenjump/my-hero-academia-chapter-116/chapter/8675?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 116
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-116/chapter/8675?action=read',targetTitle:'My Hero Academia, Chapter 116'};wsjModalPromoId='wsj_subscribe_modal_8675';wsjModalSource='My Hero Academia, Chapter 116';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8675,'/shonenjump/my-hero-academia-chapter-116/chapter/8675?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-116/chapter/8675?action=read',targetTitle:'My Hero Academia, Chapter 116'};wsjModalPromoId='wsj_subscribe_modal_8675';wsjModalSource='My Hero Academia, Chapter 116';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8675,'/shonenjump/my-hero-academia-chapter-116/chapter/8675?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8674"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1150">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-115/chapter/8674?action=read',targetTitle:'My Hero Academia, Chapter 115'};wsjModalPromoId='wsj_subscribe_modal_8674';wsjModalSource='My Hero Academia, Chapter 115';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8674,'/shonenjump/my-hero-academia-chapter-115/chapter/8674?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 115
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-115/chapter/8674?action=read',targetTitle:'My Hero Academia, Chapter 115'};wsjModalPromoId='wsj_subscribe_modal_8674';wsjModalSource='My Hero Academia, Chapter 115';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8674,'/shonenjump/my-hero-academia-chapter-115/chapter/8674?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-115/chapter/8674?action=read',targetTitle:'My Hero Academia, Chapter 115'};wsjModalPromoId='wsj_subscribe_modal_8674';wsjModalSource='My Hero Academia, Chapter 115';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8674,'/shonenjump/my-hero-academia-chapter-115/chapter/8674?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8673"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1140">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-114/chapter/8673?action=read',targetTitle:'My Hero Academia, Chapter 114'};wsjModalPromoId='wsj_subscribe_modal_8673';wsjModalSource='My Hero Academia, Chapter 114';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8673,'/shonenjump/my-hero-academia-chapter-114/chapter/8673?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 114
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-114/chapter/8673?action=read',targetTitle:'My Hero Academia, Chapter 114'};wsjModalPromoId='wsj_subscribe_modal_8673';wsjModalSource='My Hero Academia, Chapter 114';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8673,'/shonenjump/my-hero-academia-chapter-114/chapter/8673?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-114/chapter/8673?action=read',targetTitle:'My Hero Academia, Chapter 114'};wsjModalPromoId='wsj_subscribe_modal_8673';wsjModalSource='My Hero Academia, Chapter 114';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8673,'/shonenjump/my-hero-academia-chapter-114/chapter/8673?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8672"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1130">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-113/chapter/8672?action=read',targetTitle:'My Hero Academia, Chapter 113'};wsjModalPromoId='wsj_subscribe_modal_8672';wsjModalSource='My Hero Academia, Chapter 113';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8672,'/shonenjump/my-hero-academia-chapter-113/chapter/8672?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 113
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-113/chapter/8672?action=read',targetTitle:'My Hero Academia, Chapter 113'};wsjModalPromoId='wsj_subscribe_modal_8672';wsjModalSource='My Hero Academia, Chapter 113';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8672,'/shonenjump/my-hero-academia-chapter-113/chapter/8672?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-113/chapter/8672?action=read',targetTitle:'My Hero Academia, Chapter 113'};wsjModalPromoId='wsj_subscribe_modal_8672';wsjModalSource='My Hero Academia, Chapter 113';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8672,'/shonenjump/my-hero-academia-chapter-113/chapter/8672?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8671"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1120">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-112/chapter/8671?action=read',targetTitle:'My Hero Academia, Chapter 112'};wsjModalPromoId='wsj_subscribe_modal_8671';wsjModalSource='My Hero Academia, Chapter 112';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8671,'/shonenjump/my-hero-academia-chapter-112/chapter/8671?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 112
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-112/chapter/8671?action=read',targetTitle:'My Hero Academia, Chapter 112'};wsjModalPromoId='wsj_subscribe_modal_8671';wsjModalSource='My Hero Academia, Chapter 112';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8671,'/shonenjump/my-hero-academia-chapter-112/chapter/8671?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-112/chapter/8671?action=read',targetTitle:'My Hero Academia, Chapter 112'};wsjModalPromoId='wsj_subscribe_modal_8671';wsjModalSource='My Hero Academia, Chapter 112';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8671,'/shonenjump/my-hero-academia-chapter-112/chapter/8671?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8670"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1110">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-111/chapter/8670?action=read',targetTitle:'My Hero Academia, Chapter 111'};wsjModalPromoId='wsj_subscribe_modal_8670';wsjModalSource='My Hero Academia, Chapter 111';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8670,'/shonenjump/my-hero-academia-chapter-111/chapter/8670?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 111
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-111/chapter/8670?action=read',targetTitle:'My Hero Academia, Chapter 111'};wsjModalPromoId='wsj_subscribe_modal_8670';wsjModalSource='My Hero Academia, Chapter 111';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8670,'/shonenjump/my-hero-academia-chapter-111/chapter/8670?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-111/chapter/8670?action=read',targetTitle:'My Hero Academia, Chapter 111'};wsjModalPromoId='wsj_subscribe_modal_8670';wsjModalSource='My Hero Academia, Chapter 111';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8670,'/shonenjump/my-hero-academia-chapter-111/chapter/8670?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8669"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1100">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-110/chapter/8669?action=read',targetTitle:'My Hero Academia, Chapter 110'};wsjModalPromoId='wsj_subscribe_modal_8669';wsjModalSource='My Hero Academia, Chapter 110';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8669,'/shonenjump/my-hero-academia-chapter-110/chapter/8669?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 110
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-110/chapter/8669?action=read',targetTitle:'My Hero Academia, Chapter 110'};wsjModalPromoId='wsj_subscribe_modal_8669';wsjModalSource='My Hero Academia, Chapter 110';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8669,'/shonenjump/my-hero-academia-chapter-110/chapter/8669?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-110/chapter/8669?action=read',targetTitle:'My Hero Academia, Chapter 110'};wsjModalPromoId='wsj_subscribe_modal_8669';wsjModalSource='My Hero Academia, Chapter 110';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8669,'/shonenjump/my-hero-academia-chapter-110/chapter/8669?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8668"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1090">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-109/chapter/8668?action=read',targetTitle:'My Hero Academia, Chapter 109'};wsjModalPromoId='wsj_subscribe_modal_8668';wsjModalSource='My Hero Academia, Chapter 109';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8668,'/shonenjump/my-hero-academia-chapter-109/chapter/8668?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 109
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-109/chapter/8668?action=read',targetTitle:'My Hero Academia, Chapter 109'};wsjModalPromoId='wsj_subscribe_modal_8668';wsjModalSource='My Hero Academia, Chapter 109';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8668,'/shonenjump/my-hero-academia-chapter-109/chapter/8668?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-109/chapter/8668?action=read',targetTitle:'My Hero Academia, Chapter 109'};wsjModalPromoId='wsj_subscribe_modal_8668';wsjModalSource='My Hero Academia, Chapter 109';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8668,'/shonenjump/my-hero-academia-chapter-109/chapter/8668?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="55"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="1080">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-12/product/5464/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421597012.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-12/product/5464/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8686"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1080">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-108/chapter/8686?action=read',targetTitle:'My Hero Academia, Chapter 108'};wsjModalPromoId='wsj_subscribe_modal_8686';wsjModalSource='My Hero Academia, Chapter 108';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8686,'/shonenjump/my-hero-academia-chapter-108/chapter/8686?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 108
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-108/chapter/8686?action=read',targetTitle:'My Hero Academia, Chapter 108'};wsjModalPromoId='wsj_subscribe_modal_8686';wsjModalSource='My Hero Academia, Chapter 108';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8686,'/shonenjump/my-hero-academia-chapter-108/chapter/8686?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-108/chapter/8686?action=read',targetTitle:'My Hero Academia, Chapter 108'};wsjModalPromoId='wsj_subscribe_modal_8686';wsjModalSource='My Hero Academia, Chapter 108';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8686,'/shonenjump/my-hero-academia-chapter-108/chapter/8686?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8685"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1070">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-107/chapter/8685?action=read',targetTitle:'My Hero Academia, Chapter 107'};wsjModalPromoId='wsj_subscribe_modal_8685';wsjModalSource='My Hero Academia, Chapter 107';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8685,'/shonenjump/my-hero-academia-chapter-107/chapter/8685?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 107
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-107/chapter/8685?action=read',targetTitle:'My Hero Academia, Chapter 107'};wsjModalPromoId='wsj_subscribe_modal_8685';wsjModalSource='My Hero Academia, Chapter 107';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8685,'/shonenjump/my-hero-academia-chapter-107/chapter/8685?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-107/chapter/8685?action=read',targetTitle:'My Hero Academia, Chapter 107'};wsjModalPromoId='wsj_subscribe_modal_8685';wsjModalSource='My Hero Academia, Chapter 107';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8685,'/shonenjump/my-hero-academia-chapter-107/chapter/8685?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8684"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1060">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-106/chapter/8684?action=read',targetTitle:'My Hero Academia, Chapter 106'};wsjModalPromoId='wsj_subscribe_modal_8684';wsjModalSource='My Hero Academia, Chapter 106';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8684,'/shonenjump/my-hero-academia-chapter-106/chapter/8684?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 106
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-106/chapter/8684?action=read',targetTitle:'My Hero Academia, Chapter 106'};wsjModalPromoId='wsj_subscribe_modal_8684';wsjModalSource='My Hero Academia, Chapter 106';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8684,'/shonenjump/my-hero-academia-chapter-106/chapter/8684?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-106/chapter/8684?action=read',targetTitle:'My Hero Academia, Chapter 106'};wsjModalPromoId='wsj_subscribe_modal_8684';wsjModalSource='My Hero Academia, Chapter 106';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8684,'/shonenjump/my-hero-academia-chapter-106/chapter/8684?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8683"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1050">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-105/chapter/8683?action=read',targetTitle:'My Hero Academia, Chapter 105'};wsjModalPromoId='wsj_subscribe_modal_8683';wsjModalSource='My Hero Academia, Chapter 105';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8683,'/shonenjump/my-hero-academia-chapter-105/chapter/8683?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 105
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-105/chapter/8683?action=read',targetTitle:'My Hero Academia, Chapter 105'};wsjModalPromoId='wsj_subscribe_modal_8683';wsjModalSource='My Hero Academia, Chapter 105';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8683,'/shonenjump/my-hero-academia-chapter-105/chapter/8683?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-105/chapter/8683?action=read',targetTitle:'My Hero Academia, Chapter 105'};wsjModalPromoId='wsj_subscribe_modal_8683';wsjModalSource='My Hero Academia, Chapter 105';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8683,'/shonenjump/my-hero-academia-chapter-105/chapter/8683?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8682"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1040">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-104/chapter/8682?action=read',targetTitle:'My Hero Academia, Chapter 104'};wsjModalPromoId='wsj_subscribe_modal_8682';wsjModalSource='My Hero Academia, Chapter 104';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8682,'/shonenjump/my-hero-academia-chapter-104/chapter/8682?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 104
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-104/chapter/8682?action=read',targetTitle:'My Hero Academia, Chapter 104'};wsjModalPromoId='wsj_subscribe_modal_8682';wsjModalSource='My Hero Academia, Chapter 104';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8682,'/shonenjump/my-hero-academia-chapter-104/chapter/8682?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-104/chapter/8682?action=read',targetTitle:'My Hero Academia, Chapter 104'};wsjModalPromoId='wsj_subscribe_modal_8682';wsjModalSource='My Hero Academia, Chapter 104';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8682,'/shonenjump/my-hero-academia-chapter-104/chapter/8682?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8681"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1030">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-103/chapter/8681?action=read',targetTitle:'My Hero Academia, Chapter 103'};wsjModalPromoId='wsj_subscribe_modal_8681';wsjModalSource='My Hero Academia, Chapter 103';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8681,'/shonenjump/my-hero-academia-chapter-103/chapter/8681?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 103
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-103/chapter/8681?action=read',targetTitle:'My Hero Academia, Chapter 103'};wsjModalPromoId='wsj_subscribe_modal_8681';wsjModalSource='My Hero Academia, Chapter 103';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8681,'/shonenjump/my-hero-academia-chapter-103/chapter/8681?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-103/chapter/8681?action=read',targetTitle:'My Hero Academia, Chapter 103'};wsjModalPromoId='wsj_subscribe_modal_8681';wsjModalSource='My Hero Academia, Chapter 103';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8681,'/shonenjump/my-hero-academia-chapter-103/chapter/8681?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8680"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1020">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-102/chapter/8680?action=read',targetTitle:'My Hero Academia, Chapter 102'};wsjModalPromoId='wsj_subscribe_modal_8680';wsjModalSource='My Hero Academia, Chapter 102';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8680,'/shonenjump/my-hero-academia-chapter-102/chapter/8680?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 102
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-102/chapter/8680?action=read',targetTitle:'My Hero Academia, Chapter 102'};wsjModalPromoId='wsj_subscribe_modal_8680';wsjModalSource='My Hero Academia, Chapter 102';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8680,'/shonenjump/my-hero-academia-chapter-102/chapter/8680?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-102/chapter/8680?action=read',targetTitle:'My Hero Academia, Chapter 102'};wsjModalPromoId='wsj_subscribe_modal_8680';wsjModalSource='My Hero Academia, Chapter 102';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8680,'/shonenjump/my-hero-academia-chapter-102/chapter/8680?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8679"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1010">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-101/chapter/8679?action=read',targetTitle:'My Hero Academia, Chapter 101'};wsjModalPromoId='wsj_subscribe_modal_8679';wsjModalSource='My Hero Academia, Chapter 101';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8679,'/shonenjump/my-hero-academia-chapter-101/chapter/8679?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 101
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-101/chapter/8679?action=read',targetTitle:'My Hero Academia, Chapter 101'};wsjModalPromoId='wsj_subscribe_modal_8679';wsjModalSource='My Hero Academia, Chapter 101';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8679,'/shonenjump/my-hero-academia-chapter-101/chapter/8679?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-101/chapter/8679?action=read',targetTitle:'My Hero Academia, Chapter 101'};wsjModalPromoId='wsj_subscribe_modal_8679';wsjModalSource='My Hero Academia, Chapter 101';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8679,'/shonenjump/my-hero-academia-chapter-101/chapter/8679?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8678"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="1000">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-100/chapter/8678?action=read',targetTitle:'My Hero Academia, Chapter 100'};wsjModalPromoId='wsj_subscribe_modal_8678';wsjModalSource='My Hero Academia, Chapter 100';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8678,'/shonenjump/my-hero-academia-chapter-100/chapter/8678?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 100
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-100/chapter/8678?action=read',targetTitle:'My Hero Academia, Chapter 100'};wsjModalPromoId='wsj_subscribe_modal_8678';wsjModalSource='My Hero Academia, Chapter 100';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8678,'/shonenjump/my-hero-academia-chapter-100/chapter/8678?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-100/chapter/8678?action=read',targetTitle:'My Hero Academia, Chapter 100'};wsjModalPromoId='wsj_subscribe_modal_8678';wsjModalSource='My Hero Academia, Chapter 100';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8678,'/shonenjump/my-hero-academia-chapter-100/chapter/8678?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="56"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="990">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-11/product/5409/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421595834.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-11/product/5409/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8667"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="990">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-99/chapter/8667?action=read',targetTitle:'My Hero Academia, Chapter 99'};wsjModalPromoId='wsj_subscribe_modal_8667';wsjModalSource='My Hero Academia, Chapter 99';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8667,'/shonenjump/my-hero-academia-chapter-99/chapter/8667?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 99
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-99/chapter/8667?action=read',targetTitle:'My Hero Academia, Chapter 99'};wsjModalPromoId='wsj_subscribe_modal_8667';wsjModalSource='My Hero Academia, Chapter 99';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8667,'/shonenjump/my-hero-academia-chapter-99/chapter/8667?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-99/chapter/8667?action=read',targetTitle:'My Hero Academia, Chapter 99'};wsjModalPromoId='wsj_subscribe_modal_8667';wsjModalSource='My Hero Academia, Chapter 99';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8667,'/shonenjump/my-hero-academia-chapter-99/chapter/8667?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8666"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="980">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-98/chapter/8666?action=read',targetTitle:'My Hero Academia, Chapter 98'};wsjModalPromoId='wsj_subscribe_modal_8666';wsjModalSource='My Hero Academia, Chapter 98';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8666,'/shonenjump/my-hero-academia-chapter-98/chapter/8666?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 98
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-98/chapter/8666?action=read',targetTitle:'My Hero Academia, Chapter 98'};wsjModalPromoId='wsj_subscribe_modal_8666';wsjModalSource='My Hero Academia, Chapter 98';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8666,'/shonenjump/my-hero-academia-chapter-98/chapter/8666?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-98/chapter/8666?action=read',targetTitle:'My Hero Academia, Chapter 98'};wsjModalPromoId='wsj_subscribe_modal_8666';wsjModalSource='My Hero Academia, Chapter 98';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8666,'/shonenjump/my-hero-academia-chapter-98/chapter/8666?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8665"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="970">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-97/chapter/8665?action=read',targetTitle:'My Hero Academia, Chapter 97'};wsjModalPromoId='wsj_subscribe_modal_8665';wsjModalSource='My Hero Academia, Chapter 97';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8665,'/shonenjump/my-hero-academia-chapter-97/chapter/8665?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 97
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-97/chapter/8665?action=read',targetTitle:'My Hero Academia, Chapter 97'};wsjModalPromoId='wsj_subscribe_modal_8665';wsjModalSource='My Hero Academia, Chapter 97';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8665,'/shonenjump/my-hero-academia-chapter-97/chapter/8665?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-97/chapter/8665?action=read',targetTitle:'My Hero Academia, Chapter 97'};wsjModalPromoId='wsj_subscribe_modal_8665';wsjModalSource='My Hero Academia, Chapter 97';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8665,'/shonenjump/my-hero-academia-chapter-97/chapter/8665?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8664"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="960">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-96/chapter/8664?action=read',targetTitle:'My Hero Academia, Chapter 96'};wsjModalPromoId='wsj_subscribe_modal_8664';wsjModalSource='My Hero Academia, Chapter 96';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8664,'/shonenjump/my-hero-academia-chapter-96/chapter/8664?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 96
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-96/chapter/8664?action=read',targetTitle:'My Hero Academia, Chapter 96'};wsjModalPromoId='wsj_subscribe_modal_8664';wsjModalSource='My Hero Academia, Chapter 96';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8664,'/shonenjump/my-hero-academia-chapter-96/chapter/8664?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-96/chapter/8664?action=read',targetTitle:'My Hero Academia, Chapter 96'};wsjModalPromoId='wsj_subscribe_modal_8664';wsjModalSource='My Hero Academia, Chapter 96';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8664,'/shonenjump/my-hero-academia-chapter-96/chapter/8664?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8663"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="950">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-95/chapter/8663?action=read',targetTitle:'My Hero Academia, Chapter 95'};wsjModalPromoId='wsj_subscribe_modal_8663';wsjModalSource='My Hero Academia, Chapter 95';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8663,'/shonenjump/my-hero-academia-chapter-95/chapter/8663?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 95
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-95/chapter/8663?action=read',targetTitle:'My Hero Academia, Chapter 95'};wsjModalPromoId='wsj_subscribe_modal_8663';wsjModalSource='My Hero Academia, Chapter 95';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8663,'/shonenjump/my-hero-academia-chapter-95/chapter/8663?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-95/chapter/8663?action=read',targetTitle:'My Hero Academia, Chapter 95'};wsjModalPromoId='wsj_subscribe_modal_8663';wsjModalSource='My Hero Academia, Chapter 95';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8663,'/shonenjump/my-hero-academia-chapter-95/chapter/8663?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8662"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="940">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-94/chapter/8662?action=read',targetTitle:'My Hero Academia, Chapter 94'};wsjModalPromoId='wsj_subscribe_modal_8662';wsjModalSource='My Hero Academia, Chapter 94';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8662,'/shonenjump/my-hero-academia-chapter-94/chapter/8662?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 94
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-94/chapter/8662?action=read',targetTitle:'My Hero Academia, Chapter 94'};wsjModalPromoId='wsj_subscribe_modal_8662';wsjModalSource='My Hero Academia, Chapter 94';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8662,'/shonenjump/my-hero-academia-chapter-94/chapter/8662?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-94/chapter/8662?action=read',targetTitle:'My Hero Academia, Chapter 94'};wsjModalPromoId='wsj_subscribe_modal_8662';wsjModalSource='My Hero Academia, Chapter 94';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8662,'/shonenjump/my-hero-academia-chapter-94/chapter/8662?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8661"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="930">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-93/chapter/8661?action=read',targetTitle:'My Hero Academia, Chapter 93'};wsjModalPromoId='wsj_subscribe_modal_8661';wsjModalSource='My Hero Academia, Chapter 93';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8661,'/shonenjump/my-hero-academia-chapter-93/chapter/8661?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 93
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-93/chapter/8661?action=read',targetTitle:'My Hero Academia, Chapter 93'};wsjModalPromoId='wsj_subscribe_modal_8661';wsjModalSource='My Hero Academia, Chapter 93';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8661,'/shonenjump/my-hero-academia-chapter-93/chapter/8661?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-93/chapter/8661?action=read',targetTitle:'My Hero Academia, Chapter 93'};wsjModalPromoId='wsj_subscribe_modal_8661';wsjModalSource='My Hero Academia, Chapter 93';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8661,'/shonenjump/my-hero-academia-chapter-93/chapter/8661?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8660"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="920">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-92/chapter/8660?action=read',targetTitle:'My Hero Academia, Chapter 92'};wsjModalPromoId='wsj_subscribe_modal_8660';wsjModalSource='My Hero Academia, Chapter 92';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8660,'/shonenjump/my-hero-academia-chapter-92/chapter/8660?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 92
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-92/chapter/8660?action=read',targetTitle:'My Hero Academia, Chapter 92'};wsjModalPromoId='wsj_subscribe_modal_8660';wsjModalSource='My Hero Academia, Chapter 92';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8660,'/shonenjump/my-hero-academia-chapter-92/chapter/8660?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-92/chapter/8660?action=read',targetTitle:'My Hero Academia, Chapter 92'};wsjModalPromoId='wsj_subscribe_modal_8660';wsjModalSource='My Hero Academia, Chapter 92';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8660,'/shonenjump/my-hero-academia-chapter-92/chapter/8660?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8659"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="910">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-91/chapter/8659?action=read',targetTitle:'My Hero Academia, Chapter 91'};wsjModalPromoId='wsj_subscribe_modal_8659';wsjModalSource='My Hero Academia, Chapter 91';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8659,'/shonenjump/my-hero-academia-chapter-91/chapter/8659?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 91
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-91/chapter/8659?action=read',targetTitle:'My Hero Academia, Chapter 91'};wsjModalPromoId='wsj_subscribe_modal_8659';wsjModalSource='My Hero Academia, Chapter 91';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8659,'/shonenjump/my-hero-academia-chapter-91/chapter/8659?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-91/chapter/8659?action=read',targetTitle:'My Hero Academia, Chapter 91'};wsjModalPromoId='wsj_subscribe_modal_8659';wsjModalSource='My Hero Academia, Chapter 91';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8659,'/shonenjump/my-hero-academia-chapter-91/chapter/8659?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8658"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="900">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-90/chapter/8658?action=read',targetTitle:'My Hero Academia, Chapter 90'};wsjModalPromoId='wsj_subscribe_modal_8658';wsjModalSource='My Hero Academia, Chapter 90';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8658,'/shonenjump/my-hero-academia-chapter-90/chapter/8658?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 90
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-90/chapter/8658?action=read',targetTitle:'My Hero Academia, Chapter 90'};wsjModalPromoId='wsj_subscribe_modal_8658';wsjModalSource='My Hero Academia, Chapter 90';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8658,'/shonenjump/my-hero-academia-chapter-90/chapter/8658?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-90/chapter/8658?action=read',targetTitle:'My Hero Academia, Chapter 90'};wsjModalPromoId='wsj_subscribe_modal_8658';wsjModalSource='My Hero Academia, Chapter 90';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8658,'/shonenjump/my-hero-academia-chapter-90/chapter/8658?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="57"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="890">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-10/product/5322/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421594374.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-10/product/5322/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8656"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="890">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-89/chapter/8656?action=read',targetTitle:'My Hero Academia, Chapter 89'};wsjModalPromoId='wsj_subscribe_modal_8656';wsjModalSource='My Hero Academia, Chapter 89';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8656,'/shonenjump/my-hero-academia-chapter-89/chapter/8656?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 89
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-89/chapter/8656?action=read',targetTitle:'My Hero Academia, Chapter 89'};wsjModalPromoId='wsj_subscribe_modal_8656';wsjModalSource='My Hero Academia, Chapter 89';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8656,'/shonenjump/my-hero-academia-chapter-89/chapter/8656?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-89/chapter/8656?action=read',targetTitle:'My Hero Academia, Chapter 89'};wsjModalPromoId='wsj_subscribe_modal_8656';wsjModalSource='My Hero Academia, Chapter 89';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8656,'/shonenjump/my-hero-academia-chapter-89/chapter/8656?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8655"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="880">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-88/chapter/8655?action=read',targetTitle:'My Hero Academia, Chapter 88'};wsjModalPromoId='wsj_subscribe_modal_8655';wsjModalSource='My Hero Academia, Chapter 88';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8655,'/shonenjump/my-hero-academia-chapter-88/chapter/8655?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 88
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-88/chapter/8655?action=read',targetTitle:'My Hero Academia, Chapter 88'};wsjModalPromoId='wsj_subscribe_modal_8655';wsjModalSource='My Hero Academia, Chapter 88';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8655,'/shonenjump/my-hero-academia-chapter-88/chapter/8655?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-88/chapter/8655?action=read',targetTitle:'My Hero Academia, Chapter 88'};wsjModalPromoId='wsj_subscribe_modal_8655';wsjModalSource='My Hero Academia, Chapter 88';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8655,'/shonenjump/my-hero-academia-chapter-88/chapter/8655?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8654"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="870">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-87/chapter/8654?action=read',targetTitle:'My Hero Academia, Chapter 87'};wsjModalPromoId='wsj_subscribe_modal_8654';wsjModalSource='My Hero Academia, Chapter 87';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8654,'/shonenjump/my-hero-academia-chapter-87/chapter/8654?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 87
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-87/chapter/8654?action=read',targetTitle:'My Hero Academia, Chapter 87'};wsjModalPromoId='wsj_subscribe_modal_8654';wsjModalSource='My Hero Academia, Chapter 87';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8654,'/shonenjump/my-hero-academia-chapter-87/chapter/8654?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-87/chapter/8654?action=read',targetTitle:'My Hero Academia, Chapter 87'};wsjModalPromoId='wsj_subscribe_modal_8654';wsjModalSource='My Hero Academia, Chapter 87';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8654,'/shonenjump/my-hero-academia-chapter-87/chapter/8654?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8653"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="860">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-86/chapter/8653?action=read',targetTitle:'My Hero Academia, Chapter 86'};wsjModalPromoId='wsj_subscribe_modal_8653';wsjModalSource='My Hero Academia, Chapter 86';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8653,'/shonenjump/my-hero-academia-chapter-86/chapter/8653?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 86
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-86/chapter/8653?action=read',targetTitle:'My Hero Academia, Chapter 86'};wsjModalPromoId='wsj_subscribe_modal_8653';wsjModalSource='My Hero Academia, Chapter 86';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8653,'/shonenjump/my-hero-academia-chapter-86/chapter/8653?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-86/chapter/8653?action=read',targetTitle:'My Hero Academia, Chapter 86'};wsjModalPromoId='wsj_subscribe_modal_8653';wsjModalSource='My Hero Academia, Chapter 86';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8653,'/shonenjump/my-hero-academia-chapter-86/chapter/8653?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8652"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="850">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-85/chapter/8652?action=read',targetTitle:'My Hero Academia, Chapter 85'};wsjModalPromoId='wsj_subscribe_modal_8652';wsjModalSource='My Hero Academia, Chapter 85';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8652,'/shonenjump/my-hero-academia-chapter-85/chapter/8652?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 85
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-85/chapter/8652?action=read',targetTitle:'My Hero Academia, Chapter 85'};wsjModalPromoId='wsj_subscribe_modal_8652';wsjModalSource='My Hero Academia, Chapter 85';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8652,'/shonenjump/my-hero-academia-chapter-85/chapter/8652?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-85/chapter/8652?action=read',targetTitle:'My Hero Academia, Chapter 85'};wsjModalPromoId='wsj_subscribe_modal_8652';wsjModalSource='My Hero Academia, Chapter 85';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8652,'/shonenjump/my-hero-academia-chapter-85/chapter/8652?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8651"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="840">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-84/chapter/8651?action=read',targetTitle:'My Hero Academia, Chapter 84'};wsjModalPromoId='wsj_subscribe_modal_8651';wsjModalSource='My Hero Academia, Chapter 84';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8651,'/shonenjump/my-hero-academia-chapter-84/chapter/8651?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 84
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-84/chapter/8651?action=read',targetTitle:'My Hero Academia, Chapter 84'};wsjModalPromoId='wsj_subscribe_modal_8651';wsjModalSource='My Hero Academia, Chapter 84';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8651,'/shonenjump/my-hero-academia-chapter-84/chapter/8651?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-84/chapter/8651?action=read',targetTitle:'My Hero Academia, Chapter 84'};wsjModalPromoId='wsj_subscribe_modal_8651';wsjModalSource='My Hero Academia, Chapter 84';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8651,'/shonenjump/my-hero-academia-chapter-84/chapter/8651?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8650"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="830">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-83/chapter/8650?action=read',targetTitle:'My Hero Academia, Chapter 83'};wsjModalPromoId='wsj_subscribe_modal_8650';wsjModalSource='My Hero Academia, Chapter 83';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8650,'/shonenjump/my-hero-academia-chapter-83/chapter/8650?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 83
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-83/chapter/8650?action=read',targetTitle:'My Hero Academia, Chapter 83'};wsjModalPromoId='wsj_subscribe_modal_8650';wsjModalSource='My Hero Academia, Chapter 83';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8650,'/shonenjump/my-hero-academia-chapter-83/chapter/8650?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-83/chapter/8650?action=read',targetTitle:'My Hero Academia, Chapter 83'};wsjModalPromoId='wsj_subscribe_modal_8650';wsjModalSource='My Hero Academia, Chapter 83';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8650,'/shonenjump/my-hero-academia-chapter-83/chapter/8650?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8649"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="820">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-82/chapter/8649?action=read',targetTitle:'My Hero Academia, Chapter 82'};wsjModalPromoId='wsj_subscribe_modal_8649';wsjModalSource='My Hero Academia, Chapter 82';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8649,'/shonenjump/my-hero-academia-chapter-82/chapter/8649?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 82
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-82/chapter/8649?action=read',targetTitle:'My Hero Academia, Chapter 82'};wsjModalPromoId='wsj_subscribe_modal_8649';wsjModalSource='My Hero Academia, Chapter 82';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8649,'/shonenjump/my-hero-academia-chapter-82/chapter/8649?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-82/chapter/8649?action=read',targetTitle:'My Hero Academia, Chapter 82'};wsjModalPromoId='wsj_subscribe_modal_8649';wsjModalSource='My Hero Academia, Chapter 82';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8649,'/shonenjump/my-hero-academia-chapter-82/chapter/8649?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8648"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="810">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-81/chapter/8648?action=read',targetTitle:'My Hero Academia, Chapter 81'};wsjModalPromoId='wsj_subscribe_modal_8648';wsjModalSource='My Hero Academia, Chapter 81';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8648,'/shonenjump/my-hero-academia-chapter-81/chapter/8648?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 81
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-81/chapter/8648?action=read',targetTitle:'My Hero Academia, Chapter 81'};wsjModalPromoId='wsj_subscribe_modal_8648';wsjModalSource='My Hero Academia, Chapter 81';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8648,'/shonenjump/my-hero-academia-chapter-81/chapter/8648?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-81/chapter/8648?action=read',targetTitle:'My Hero Academia, Chapter 81'};wsjModalPromoId='wsj_subscribe_modal_8648';wsjModalSource='My Hero Academia, Chapter 81';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8648,'/shonenjump/my-hero-academia-chapter-81/chapter/8648?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="58"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="800">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-9/product/5229/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421593408.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-9/product/5229/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8647"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="800">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-80/chapter/8647?action=read',targetTitle:'My Hero Academia, Chapter 80'};wsjModalPromoId='wsj_subscribe_modal_8647';wsjModalSource='My Hero Academia, Chapter 80';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8647,'/shonenjump/my-hero-academia-chapter-80/chapter/8647?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 80
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-80/chapter/8647?action=read',targetTitle:'My Hero Academia, Chapter 80'};wsjModalPromoId='wsj_subscribe_modal_8647';wsjModalSource='My Hero Academia, Chapter 80';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8647,'/shonenjump/my-hero-academia-chapter-80/chapter/8647?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-80/chapter/8647?action=read',targetTitle:'My Hero Academia, Chapter 80'};wsjModalPromoId='wsj_subscribe_modal_8647';wsjModalSource='My Hero Academia, Chapter 80';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8647,'/shonenjump/my-hero-academia-chapter-80/chapter/8647?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8646"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="790">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-79/chapter/8646?action=read',targetTitle:'My Hero Academia, Chapter 79'};wsjModalPromoId='wsj_subscribe_modal_8646';wsjModalSource='My Hero Academia, Chapter 79';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8646,'/shonenjump/my-hero-academia-chapter-79/chapter/8646?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 79
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-79/chapter/8646?action=read',targetTitle:'My Hero Academia, Chapter 79'};wsjModalPromoId='wsj_subscribe_modal_8646';wsjModalSource='My Hero Academia, Chapter 79';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8646,'/shonenjump/my-hero-academia-chapter-79/chapter/8646?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-79/chapter/8646?action=read',targetTitle:'My Hero Academia, Chapter 79'};wsjModalPromoId='wsj_subscribe_modal_8646';wsjModalSource='My Hero Academia, Chapter 79';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8646,'/shonenjump/my-hero-academia-chapter-79/chapter/8646?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8645"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="780">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-78/chapter/8645?action=read',targetTitle:'My Hero Academia, Chapter 78'};wsjModalPromoId='wsj_subscribe_modal_8645';wsjModalSource='My Hero Academia, Chapter 78';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8645,'/shonenjump/my-hero-academia-chapter-78/chapter/8645?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 78
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-78/chapter/8645?action=read',targetTitle:'My Hero Academia, Chapter 78'};wsjModalPromoId='wsj_subscribe_modal_8645';wsjModalSource='My Hero Academia, Chapter 78';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8645,'/shonenjump/my-hero-academia-chapter-78/chapter/8645?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-78/chapter/8645?action=read',targetTitle:'My Hero Academia, Chapter 78'};wsjModalPromoId='wsj_subscribe_modal_8645';wsjModalSource='My Hero Academia, Chapter 78';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8645,'/shonenjump/my-hero-academia-chapter-78/chapter/8645?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8644"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="770">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-77/chapter/8644?action=read',targetTitle:'My Hero Academia, Chapter 77'};wsjModalPromoId='wsj_subscribe_modal_8644';wsjModalSource='My Hero Academia, Chapter 77';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8644,'/shonenjump/my-hero-academia-chapter-77/chapter/8644?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 77
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-77/chapter/8644?action=read',targetTitle:'My Hero Academia, Chapter 77'};wsjModalPromoId='wsj_subscribe_modal_8644';wsjModalSource='My Hero Academia, Chapter 77';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8644,'/shonenjump/my-hero-academia-chapter-77/chapter/8644?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-77/chapter/8644?action=read',targetTitle:'My Hero Academia, Chapter 77'};wsjModalPromoId='wsj_subscribe_modal_8644';wsjModalSource='My Hero Academia, Chapter 77';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8644,'/shonenjump/my-hero-academia-chapter-77/chapter/8644?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8643"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="760">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-76/chapter/8643?action=read',targetTitle:'My Hero Academia, Chapter 76'};wsjModalPromoId='wsj_subscribe_modal_8643';wsjModalSource='My Hero Academia, Chapter 76';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8643,'/shonenjump/my-hero-academia-chapter-76/chapter/8643?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 76
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-76/chapter/8643?action=read',targetTitle:'My Hero Academia, Chapter 76'};wsjModalPromoId='wsj_subscribe_modal_8643';wsjModalSource='My Hero Academia, Chapter 76';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8643,'/shonenjump/my-hero-academia-chapter-76/chapter/8643?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-76/chapter/8643?action=read',targetTitle:'My Hero Academia, Chapter 76'};wsjModalPromoId='wsj_subscribe_modal_8643';wsjModalSource='My Hero Academia, Chapter 76';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8643,'/shonenjump/my-hero-academia-chapter-76/chapter/8643?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8642"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="750">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-75/chapter/8642?action=read',targetTitle:'My Hero Academia, Chapter 75'};wsjModalPromoId='wsj_subscribe_modal_8642';wsjModalSource='My Hero Academia, Chapter 75';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8642,'/shonenjump/my-hero-academia-chapter-75/chapter/8642?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 75
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-75/chapter/8642?action=read',targetTitle:'My Hero Academia, Chapter 75'};wsjModalPromoId='wsj_subscribe_modal_8642';wsjModalSource='My Hero Academia, Chapter 75';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8642,'/shonenjump/my-hero-academia-chapter-75/chapter/8642?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-75/chapter/8642?action=read',targetTitle:'My Hero Academia, Chapter 75'};wsjModalPromoId='wsj_subscribe_modal_8642';wsjModalSource='My Hero Academia, Chapter 75';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8642,'/shonenjump/my-hero-academia-chapter-75/chapter/8642?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8641"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="740">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-74/chapter/8641?action=read',targetTitle:'My Hero Academia, Chapter 74'};wsjModalPromoId='wsj_subscribe_modal_8641';wsjModalSource='My Hero Academia, Chapter 74';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8641,'/shonenjump/my-hero-academia-chapter-74/chapter/8641?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 74
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-74/chapter/8641?action=read',targetTitle:'My Hero Academia, Chapter 74'};wsjModalPromoId='wsj_subscribe_modal_8641';wsjModalSource='My Hero Academia, Chapter 74';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8641,'/shonenjump/my-hero-academia-chapter-74/chapter/8641?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-74/chapter/8641?action=read',targetTitle:'My Hero Academia, Chapter 74'};wsjModalPromoId='wsj_subscribe_modal_8641';wsjModalSource='My Hero Academia, Chapter 74';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8641,'/shonenjump/my-hero-academia-chapter-74/chapter/8641?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8640"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="730">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-73/chapter/8640?action=read',targetTitle:'My Hero Academia, Chapter 73'};wsjModalPromoId='wsj_subscribe_modal_8640';wsjModalSource='My Hero Academia, Chapter 73';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8640,'/shonenjump/my-hero-academia-chapter-73/chapter/8640?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 73
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-73/chapter/8640?action=read',targetTitle:'My Hero Academia, Chapter 73'};wsjModalPromoId='wsj_subscribe_modal_8640';wsjModalSource='My Hero Academia, Chapter 73';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8640,'/shonenjump/my-hero-academia-chapter-73/chapter/8640?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-73/chapter/8640?action=read',targetTitle:'My Hero Academia, Chapter 73'};wsjModalPromoId='wsj_subscribe_modal_8640';wsjModalSource='My Hero Academia, Chapter 73';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8640,'/shonenjump/my-hero-academia-chapter-73/chapter/8640?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8639"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="720">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-72/chapter/8639?action=read',targetTitle:'My Hero Academia, Chapter 72'};wsjModalPromoId='wsj_subscribe_modal_8639';wsjModalSource='My Hero Academia, Chapter 72';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8639,'/shonenjump/my-hero-academia-chapter-72/chapter/8639?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 72
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-72/chapter/8639?action=read',targetTitle:'My Hero Academia, Chapter 72'};wsjModalPromoId='wsj_subscribe_modal_8639';wsjModalSource='My Hero Academia, Chapter 72';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8639,'/shonenjump/my-hero-academia-chapter-72/chapter/8639?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-72/chapter/8639?action=read',targetTitle:'My Hero Academia, Chapter 72'};wsjModalPromoId='wsj_subscribe_modal_8639';wsjModalSource='My Hero Academia, Chapter 72';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8639,'/shonenjump/my-hero-academia-chapter-72/chapter/8639?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="59"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="710">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-8/product/5131/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421591677.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-8/product/5131/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8637"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="710">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-71/chapter/8637?action=read',targetTitle:'My Hero Academia, Chapter 71'};wsjModalPromoId='wsj_subscribe_modal_8637';wsjModalSource='My Hero Academia, Chapter 71';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8637,'/shonenjump/my-hero-academia-chapter-71/chapter/8637?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 71
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-71/chapter/8637?action=read',targetTitle:'My Hero Academia, Chapter 71'};wsjModalPromoId='wsj_subscribe_modal_8637';wsjModalSource='My Hero Academia, Chapter 71';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8637,'/shonenjump/my-hero-academia-chapter-71/chapter/8637?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-71/chapter/8637?action=read',targetTitle:'My Hero Academia, Chapter 71'};wsjModalPromoId='wsj_subscribe_modal_8637';wsjModalSource='My Hero Academia, Chapter 71';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8637,'/shonenjump/my-hero-academia-chapter-71/chapter/8637?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8636"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="700">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-70/chapter/8636?action=read',targetTitle:'My Hero Academia, Chapter 70'};wsjModalPromoId='wsj_subscribe_modal_8636';wsjModalSource='My Hero Academia, Chapter 70';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8636,'/shonenjump/my-hero-academia-chapter-70/chapter/8636?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 70
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-70/chapter/8636?action=read',targetTitle:'My Hero Academia, Chapter 70'};wsjModalPromoId='wsj_subscribe_modal_8636';wsjModalSource='My Hero Academia, Chapter 70';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8636,'/shonenjump/my-hero-academia-chapter-70/chapter/8636?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-70/chapter/8636?action=read',targetTitle:'My Hero Academia, Chapter 70'};wsjModalPromoId='wsj_subscribe_modal_8636';wsjModalSource='My Hero Academia, Chapter 70';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8636,'/shonenjump/my-hero-academia-chapter-70/chapter/8636?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8635"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="690">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-69/chapter/8635?action=read',targetTitle:'My Hero Academia, Chapter 69'};wsjModalPromoId='wsj_subscribe_modal_8635';wsjModalSource='My Hero Academia, Chapter 69';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8635,'/shonenjump/my-hero-academia-chapter-69/chapter/8635?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 69
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-69/chapter/8635?action=read',targetTitle:'My Hero Academia, Chapter 69'};wsjModalPromoId='wsj_subscribe_modal_8635';wsjModalSource='My Hero Academia, Chapter 69';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8635,'/shonenjump/my-hero-academia-chapter-69/chapter/8635?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-69/chapter/8635?action=read',targetTitle:'My Hero Academia, Chapter 69'};wsjModalPromoId='wsj_subscribe_modal_8635';wsjModalSource='My Hero Academia, Chapter 69';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8635,'/shonenjump/my-hero-academia-chapter-69/chapter/8635?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8634"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="680">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-68/chapter/8634?action=read',targetTitle:'My Hero Academia, Chapter 68'};wsjModalPromoId='wsj_subscribe_modal_8634';wsjModalSource='My Hero Academia, Chapter 68';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8634,'/shonenjump/my-hero-academia-chapter-68/chapter/8634?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 68
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-68/chapter/8634?action=read',targetTitle:'My Hero Academia, Chapter 68'};wsjModalPromoId='wsj_subscribe_modal_8634';wsjModalSource='My Hero Academia, Chapter 68';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8634,'/shonenjump/my-hero-academia-chapter-68/chapter/8634?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-68/chapter/8634?action=read',targetTitle:'My Hero Academia, Chapter 68'};wsjModalPromoId='wsj_subscribe_modal_8634';wsjModalSource='My Hero Academia, Chapter 68';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8634,'/shonenjump/my-hero-academia-chapter-68/chapter/8634?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8633"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="670">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-67/chapter/8633?action=read',targetTitle:'My Hero Academia, Chapter 67'};wsjModalPromoId='wsj_subscribe_modal_8633';wsjModalSource='My Hero Academia, Chapter 67';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8633,'/shonenjump/my-hero-academia-chapter-67/chapter/8633?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 67
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-67/chapter/8633?action=read',targetTitle:'My Hero Academia, Chapter 67'};wsjModalPromoId='wsj_subscribe_modal_8633';wsjModalSource='My Hero Academia, Chapter 67';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8633,'/shonenjump/my-hero-academia-chapter-67/chapter/8633?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-67/chapter/8633?action=read',targetTitle:'My Hero Academia, Chapter 67'};wsjModalPromoId='wsj_subscribe_modal_8633';wsjModalSource='My Hero Academia, Chapter 67';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8633,'/shonenjump/my-hero-academia-chapter-67/chapter/8633?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8632"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="660">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-66/chapter/8632?action=read',targetTitle:'My Hero Academia, Chapter 66'};wsjModalPromoId='wsj_subscribe_modal_8632';wsjModalSource='My Hero Academia, Chapter 66';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8632,'/shonenjump/my-hero-academia-chapter-66/chapter/8632?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 66
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-66/chapter/8632?action=read',targetTitle:'My Hero Academia, Chapter 66'};wsjModalPromoId='wsj_subscribe_modal_8632';wsjModalSource='My Hero Academia, Chapter 66';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8632,'/shonenjump/my-hero-academia-chapter-66/chapter/8632?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-66/chapter/8632?action=read',targetTitle:'My Hero Academia, Chapter 66'};wsjModalPromoId='wsj_subscribe_modal_8632';wsjModalSource='My Hero Academia, Chapter 66';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8632,'/shonenjump/my-hero-academia-chapter-66/chapter/8632?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8631"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="650">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-65/chapter/8631?action=read',targetTitle:'My Hero Academia, Chapter 65'};wsjModalPromoId='wsj_subscribe_modal_8631';wsjModalSource='My Hero Academia, Chapter 65';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8631,'/shonenjump/my-hero-academia-chapter-65/chapter/8631?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 65
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-65/chapter/8631?action=read',targetTitle:'My Hero Academia, Chapter 65'};wsjModalPromoId='wsj_subscribe_modal_8631';wsjModalSource='My Hero Academia, Chapter 65';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8631,'/shonenjump/my-hero-academia-chapter-65/chapter/8631?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-65/chapter/8631?action=read',targetTitle:'My Hero Academia, Chapter 65'};wsjModalPromoId='wsj_subscribe_modal_8631';wsjModalSource='My Hero Academia, Chapter 65';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8631,'/shonenjump/my-hero-academia-chapter-65/chapter/8631?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8630"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="640">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-64/chapter/8630?action=read',targetTitle:'My Hero Academia, Chapter 64'};wsjModalPromoId='wsj_subscribe_modal_8630';wsjModalSource='My Hero Academia, Chapter 64';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8630,'/shonenjump/my-hero-academia-chapter-64/chapter/8630?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 64
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-64/chapter/8630?action=read',targetTitle:'My Hero Academia, Chapter 64'};wsjModalPromoId='wsj_subscribe_modal_8630';wsjModalSource='My Hero Academia, Chapter 64';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8630,'/shonenjump/my-hero-academia-chapter-64/chapter/8630?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-64/chapter/8630?action=read',targetTitle:'My Hero Academia, Chapter 64'};wsjModalPromoId='wsj_subscribe_modal_8630';wsjModalSource='My Hero Academia, Chapter 64';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8630,'/shonenjump/my-hero-academia-chapter-64/chapter/8630?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8629"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="630">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-63/chapter/8629?action=read',targetTitle:'My Hero Academia, Chapter 63'};wsjModalPromoId='wsj_subscribe_modal_8629';wsjModalSource='My Hero Academia, Chapter 63';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8629,'/shonenjump/my-hero-academia-chapter-63/chapter/8629?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 63
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-63/chapter/8629?action=read',targetTitle:'My Hero Academia, Chapter 63'};wsjModalPromoId='wsj_subscribe_modal_8629';wsjModalSource='My Hero Academia, Chapter 63';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8629,'/shonenjump/my-hero-academia-chapter-63/chapter/8629?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-63/chapter/8629?action=read',targetTitle:'My Hero Academia, Chapter 63'};wsjModalPromoId='wsj_subscribe_modal_8629';wsjModalSource='My Hero Academia, Chapter 63';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8629,'/shonenjump/my-hero-academia-chapter-63/chapter/8629?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="60"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="620">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-7/product/5040/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421590409.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-7/product/5040/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8628"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="620">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-62/chapter/8628?action=read',targetTitle:'My Hero Academia, Chapter 62'};wsjModalPromoId='wsj_subscribe_modal_8628';wsjModalSource='My Hero Academia, Chapter 62';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8628,'/shonenjump/my-hero-academia-chapter-62/chapter/8628?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 62
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-62/chapter/8628?action=read',targetTitle:'My Hero Academia, Chapter 62'};wsjModalPromoId='wsj_subscribe_modal_8628';wsjModalSource='My Hero Academia, Chapter 62';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8628,'/shonenjump/my-hero-academia-chapter-62/chapter/8628?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-62/chapter/8628?action=read',targetTitle:'My Hero Academia, Chapter 62'};wsjModalPromoId='wsj_subscribe_modal_8628';wsjModalSource='My Hero Academia, Chapter 62';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8628,'/shonenjump/my-hero-academia-chapter-62/chapter/8628?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8627"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="610">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-61/chapter/8627?action=read',targetTitle:'My Hero Academia, Chapter 61'};wsjModalPromoId='wsj_subscribe_modal_8627';wsjModalSource='My Hero Academia, Chapter 61';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8627,'/shonenjump/my-hero-academia-chapter-61/chapter/8627?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 61
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-61/chapter/8627?action=read',targetTitle:'My Hero Academia, Chapter 61'};wsjModalPromoId='wsj_subscribe_modal_8627';wsjModalSource='My Hero Academia, Chapter 61';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8627,'/shonenjump/my-hero-academia-chapter-61/chapter/8627?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-61/chapter/8627?action=read',targetTitle:'My Hero Academia, Chapter 61'};wsjModalPromoId='wsj_subscribe_modal_8627';wsjModalSource='My Hero Academia, Chapter 61';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8627,'/shonenjump/my-hero-academia-chapter-61/chapter/8627?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8626"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="600">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-60/chapter/8626?action=read',targetTitle:'My Hero Academia, Chapter 60'};wsjModalPromoId='wsj_subscribe_modal_8626';wsjModalSource='My Hero Academia, Chapter 60';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8626,'/shonenjump/my-hero-academia-chapter-60/chapter/8626?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 60
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-60/chapter/8626?action=read',targetTitle:'My Hero Academia, Chapter 60'};wsjModalPromoId='wsj_subscribe_modal_8626';wsjModalSource='My Hero Academia, Chapter 60';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8626,'/shonenjump/my-hero-academia-chapter-60/chapter/8626?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-60/chapter/8626?action=read',targetTitle:'My Hero Academia, Chapter 60'};wsjModalPromoId='wsj_subscribe_modal_8626';wsjModalSource='My Hero Academia, Chapter 60';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8626,'/shonenjump/my-hero-academia-chapter-60/chapter/8626?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8625"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="590">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-59/chapter/8625?action=read',targetTitle:'My Hero Academia, Chapter 59'};wsjModalPromoId='wsj_subscribe_modal_8625';wsjModalSource='My Hero Academia, Chapter 59';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8625,'/shonenjump/my-hero-academia-chapter-59/chapter/8625?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 59
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-59/chapter/8625?action=read',targetTitle:'My Hero Academia, Chapter 59'};wsjModalPromoId='wsj_subscribe_modal_8625';wsjModalSource='My Hero Academia, Chapter 59';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8625,'/shonenjump/my-hero-academia-chapter-59/chapter/8625?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-59/chapter/8625?action=read',targetTitle:'My Hero Academia, Chapter 59'};wsjModalPromoId='wsj_subscribe_modal_8625';wsjModalSource='My Hero Academia, Chapter 59';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8625,'/shonenjump/my-hero-academia-chapter-59/chapter/8625?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8624"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="580">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-58/chapter/8624?action=read',targetTitle:'My Hero Academia, Chapter 58'};wsjModalPromoId='wsj_subscribe_modal_8624';wsjModalSource='My Hero Academia, Chapter 58';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8624,'/shonenjump/my-hero-academia-chapter-58/chapter/8624?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 58
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-58/chapter/8624?action=read',targetTitle:'My Hero Academia, Chapter 58'};wsjModalPromoId='wsj_subscribe_modal_8624';wsjModalSource='My Hero Academia, Chapter 58';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8624,'/shonenjump/my-hero-academia-chapter-58/chapter/8624?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-58/chapter/8624?action=read',targetTitle:'My Hero Academia, Chapter 58'};wsjModalPromoId='wsj_subscribe_modal_8624';wsjModalSource='My Hero Academia, Chapter 58';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8624,'/shonenjump/my-hero-academia-chapter-58/chapter/8624?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8623"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="570">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-57/chapter/8623?action=read',targetTitle:'My Hero Academia, Chapter 57'};wsjModalPromoId='wsj_subscribe_modal_8623';wsjModalSource='My Hero Academia, Chapter 57';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8623,'/shonenjump/my-hero-academia-chapter-57/chapter/8623?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 57
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-57/chapter/8623?action=read',targetTitle:'My Hero Academia, Chapter 57'};wsjModalPromoId='wsj_subscribe_modal_8623';wsjModalSource='My Hero Academia, Chapter 57';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8623,'/shonenjump/my-hero-academia-chapter-57/chapter/8623?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-57/chapter/8623?action=read',targetTitle:'My Hero Academia, Chapter 57'};wsjModalPromoId='wsj_subscribe_modal_8623';wsjModalSource='My Hero Academia, Chapter 57';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8623,'/shonenjump/my-hero-academia-chapter-57/chapter/8623?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8622"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="560">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-56/chapter/8622?action=read',targetTitle:'My Hero Academia, Chapter 56'};wsjModalPromoId='wsj_subscribe_modal_8622';wsjModalSource='My Hero Academia, Chapter 56';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8622,'/shonenjump/my-hero-academia-chapter-56/chapter/8622?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 56
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-56/chapter/8622?action=read',targetTitle:'My Hero Academia, Chapter 56'};wsjModalPromoId='wsj_subscribe_modal_8622';wsjModalSource='My Hero Academia, Chapter 56';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8622,'/shonenjump/my-hero-academia-chapter-56/chapter/8622?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-56/chapter/8622?action=read',targetTitle:'My Hero Academia, Chapter 56'};wsjModalPromoId='wsj_subscribe_modal_8622';wsjModalSource='My Hero Academia, Chapter 56';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8622,'/shonenjump/my-hero-academia-chapter-56/chapter/8622?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8621"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="550">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-55/chapter/8621?action=read',targetTitle:'My Hero Academia, Chapter 55'};wsjModalPromoId='wsj_subscribe_modal_8621';wsjModalSource='My Hero Academia, Chapter 55';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8621,'/shonenjump/my-hero-academia-chapter-55/chapter/8621?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 55
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-55/chapter/8621?action=read',targetTitle:'My Hero Academia, Chapter 55'};wsjModalPromoId='wsj_subscribe_modal_8621';wsjModalSource='My Hero Academia, Chapter 55';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8621,'/shonenjump/my-hero-academia-chapter-55/chapter/8621?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-55/chapter/8621?action=read',targetTitle:'My Hero Academia, Chapter 55'};wsjModalPromoId='wsj_subscribe_modal_8621';wsjModalSource='My Hero Academia, Chapter 55';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8621,'/shonenjump/my-hero-academia-chapter-55/chapter/8621?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8620"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="540">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-54/chapter/8620?action=read',targetTitle:'My Hero Academia, Chapter 54'};wsjModalPromoId='wsj_subscribe_modal_8620';wsjModalSource='My Hero Academia, Chapter 54';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8620,'/shonenjump/my-hero-academia-chapter-54/chapter/8620?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 54
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-54/chapter/8620?action=read',targetTitle:'My Hero Academia, Chapter 54'};wsjModalPromoId='wsj_subscribe_modal_8620';wsjModalSource='My Hero Academia, Chapter 54';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8620,'/shonenjump/my-hero-academia-chapter-54/chapter/8620?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-54/chapter/8620?action=read',targetTitle:'My Hero Academia, Chapter 54'};wsjModalPromoId='wsj_subscribe_modal_8620';wsjModalSource='My Hero Academia, Chapter 54';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8620,'/shonenjump/my-hero-academia-chapter-54/chapter/8620?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="61"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="530">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-6/product/4938/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421588668.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-6/product/4938/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8619"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="530">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-53/chapter/8619?action=read',targetTitle:'My Hero Academia, Chapter 53'};wsjModalPromoId='wsj_subscribe_modal_8619';wsjModalSource='My Hero Academia, Chapter 53';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8619,'/shonenjump/my-hero-academia-chapter-53/chapter/8619?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 53
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-53/chapter/8619?action=read',targetTitle:'My Hero Academia, Chapter 53'};wsjModalPromoId='wsj_subscribe_modal_8619';wsjModalSource='My Hero Academia, Chapter 53';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8619,'/shonenjump/my-hero-academia-chapter-53/chapter/8619?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-53/chapter/8619?action=read',targetTitle:'My Hero Academia, Chapter 53'};wsjModalPromoId='wsj_subscribe_modal_8619';wsjModalSource='My Hero Academia, Chapter 53';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8619,'/shonenjump/my-hero-academia-chapter-53/chapter/8619?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8618"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="520">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-52/chapter/8618?action=read',targetTitle:'My Hero Academia, Chapter 52'};wsjModalPromoId='wsj_subscribe_modal_8618';wsjModalSource='My Hero Academia, Chapter 52';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8618,'/shonenjump/my-hero-academia-chapter-52/chapter/8618?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 52
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-52/chapter/8618?action=read',targetTitle:'My Hero Academia, Chapter 52'};wsjModalPromoId='wsj_subscribe_modal_8618';wsjModalSource='My Hero Academia, Chapter 52';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8618,'/shonenjump/my-hero-academia-chapter-52/chapter/8618?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-52/chapter/8618?action=read',targetTitle:'My Hero Academia, Chapter 52'};wsjModalPromoId='wsj_subscribe_modal_8618';wsjModalSource='My Hero Academia, Chapter 52';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8618,'/shonenjump/my-hero-academia-chapter-52/chapter/8618?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8617"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="510">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-51/chapter/8617?action=read',targetTitle:'My Hero Academia, Chapter 51'};wsjModalPromoId='wsj_subscribe_modal_8617';wsjModalSource='My Hero Academia, Chapter 51';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8617,'/shonenjump/my-hero-academia-chapter-51/chapter/8617?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 51
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-51/chapter/8617?action=read',targetTitle:'My Hero Academia, Chapter 51'};wsjModalPromoId='wsj_subscribe_modal_8617';wsjModalSource='My Hero Academia, Chapter 51';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8617,'/shonenjump/my-hero-academia-chapter-51/chapter/8617?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-51/chapter/8617?action=read',targetTitle:'My Hero Academia, Chapter 51'};wsjModalPromoId='wsj_subscribe_modal_8617';wsjModalSource='My Hero Academia, Chapter 51';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8617,'/shonenjump/my-hero-academia-chapter-51/chapter/8617?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8616"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="500">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-50/chapter/8616?action=read',targetTitle:'My Hero Academia, Chapter 50'};wsjModalPromoId='wsj_subscribe_modal_8616';wsjModalSource='My Hero Academia, Chapter 50';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8616,'/shonenjump/my-hero-academia-chapter-50/chapter/8616?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 50
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-50/chapter/8616?action=read',targetTitle:'My Hero Academia, Chapter 50'};wsjModalPromoId='wsj_subscribe_modal_8616';wsjModalSource='My Hero Academia, Chapter 50';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8616,'/shonenjump/my-hero-academia-chapter-50/chapter/8616?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-50/chapter/8616?action=read',targetTitle:'My Hero Academia, Chapter 50'};wsjModalPromoId='wsj_subscribe_modal_8616';wsjModalSource='My Hero Academia, Chapter 50';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8616,'/shonenjump/my-hero-academia-chapter-50/chapter/8616?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8615"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="490">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-49/chapter/8615?action=read',targetTitle:'My Hero Academia, Chapter 49'};wsjModalPromoId='wsj_subscribe_modal_8615';wsjModalSource='My Hero Academia, Chapter 49';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8615,'/shonenjump/my-hero-academia-chapter-49/chapter/8615?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 49
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-49/chapter/8615?action=read',targetTitle:'My Hero Academia, Chapter 49'};wsjModalPromoId='wsj_subscribe_modal_8615';wsjModalSource='My Hero Academia, Chapter 49';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8615,'/shonenjump/my-hero-academia-chapter-49/chapter/8615?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-49/chapter/8615?action=read',targetTitle:'My Hero Academia, Chapter 49'};wsjModalPromoId='wsj_subscribe_modal_8615';wsjModalSource='My Hero Academia, Chapter 49';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8615,'/shonenjump/my-hero-academia-chapter-49/chapter/8615?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8614"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="480">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-48/chapter/8614?action=read',targetTitle:'My Hero Academia, Chapter 48'};wsjModalPromoId='wsj_subscribe_modal_8614';wsjModalSource='My Hero Academia, Chapter 48';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8614,'/shonenjump/my-hero-academia-chapter-48/chapter/8614?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 48
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-48/chapter/8614?action=read',targetTitle:'My Hero Academia, Chapter 48'};wsjModalPromoId='wsj_subscribe_modal_8614';wsjModalSource='My Hero Academia, Chapter 48';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8614,'/shonenjump/my-hero-academia-chapter-48/chapter/8614?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-48/chapter/8614?action=read',targetTitle:'My Hero Academia, Chapter 48'};wsjModalPromoId='wsj_subscribe_modal_8614';wsjModalSource='My Hero Academia, Chapter 48';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8614,'/shonenjump/my-hero-academia-chapter-48/chapter/8614?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8613"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="470">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-47/chapter/8613?action=read',targetTitle:'My Hero Academia, Chapter 47'};wsjModalPromoId='wsj_subscribe_modal_8613';wsjModalSource='My Hero Academia, Chapter 47';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8613,'/shonenjump/my-hero-academia-chapter-47/chapter/8613?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 47
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-47/chapter/8613?action=read',targetTitle:'My Hero Academia, Chapter 47'};wsjModalPromoId='wsj_subscribe_modal_8613';wsjModalSource='My Hero Academia, Chapter 47';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8613,'/shonenjump/my-hero-academia-chapter-47/chapter/8613?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-47/chapter/8613?action=read',targetTitle:'My Hero Academia, Chapter 47'};wsjModalPromoId='wsj_subscribe_modal_8613';wsjModalSource='My Hero Academia, Chapter 47';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8613,'/shonenjump/my-hero-academia-chapter-47/chapter/8613?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8612"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="460">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-46/chapter/8612?action=read',targetTitle:'My Hero Academia, Chapter 46'};wsjModalPromoId='wsj_subscribe_modal_8612';wsjModalSource='My Hero Academia, Chapter 46';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8612,'/shonenjump/my-hero-academia-chapter-46/chapter/8612?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 46
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-46/chapter/8612?action=read',targetTitle:'My Hero Academia, Chapter 46'};wsjModalPromoId='wsj_subscribe_modal_8612';wsjModalSource='My Hero Academia, Chapter 46';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8612,'/shonenjump/my-hero-academia-chapter-46/chapter/8612?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-46/chapter/8612?action=read',targetTitle:'My Hero Academia, Chapter 46'};wsjModalPromoId='wsj_subscribe_modal_8612';wsjModalSource='My Hero Academia, Chapter 46';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8612,'/shonenjump/my-hero-academia-chapter-46/chapter/8612?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8611"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="450">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-45/chapter/8611?action=read',targetTitle:'My Hero Academia, Chapter 45'};wsjModalPromoId='wsj_subscribe_modal_8611';wsjModalSource='My Hero Academia, Chapter 45';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8611,'/shonenjump/my-hero-academia-chapter-45/chapter/8611?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 45
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-45/chapter/8611?action=read',targetTitle:'My Hero Academia, Chapter 45'};wsjModalPromoId='wsj_subscribe_modal_8611';wsjModalSource='My Hero Academia, Chapter 45';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8611,'/shonenjump/my-hero-academia-chapter-45/chapter/8611?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-45/chapter/8611?action=read',targetTitle:'My Hero Academia, Chapter 45'};wsjModalPromoId='wsj_subscribe_modal_8611';wsjModalSource='My Hero Academia, Chapter 45';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8611,'/shonenjump/my-hero-academia-chapter-45/chapter/8611?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="62"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="440">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-5/product/4858/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421587025.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-5/product/4858/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8610"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="440">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-44/chapter/8610?action=read',targetTitle:'My Hero Academia, Chapter 44'};wsjModalPromoId='wsj_subscribe_modal_8610';wsjModalSource='My Hero Academia, Chapter 44';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8610,'/shonenjump/my-hero-academia-chapter-44/chapter/8610?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 44
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-44/chapter/8610?action=read',targetTitle:'My Hero Academia, Chapter 44'};wsjModalPromoId='wsj_subscribe_modal_8610';wsjModalSource='My Hero Academia, Chapter 44';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8610,'/shonenjump/my-hero-academia-chapter-44/chapter/8610?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-44/chapter/8610?action=read',targetTitle:'My Hero Academia, Chapter 44'};wsjModalPromoId='wsj_subscribe_modal_8610';wsjModalSource='My Hero Academia, Chapter 44';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8610,'/shonenjump/my-hero-academia-chapter-44/chapter/8610?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8609"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="430">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-43/chapter/8609?action=read',targetTitle:'My Hero Academia, Chapter 43'};wsjModalPromoId='wsj_subscribe_modal_8609';wsjModalSource='My Hero Academia, Chapter 43';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8609,'/shonenjump/my-hero-academia-chapter-43/chapter/8609?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 43
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-43/chapter/8609?action=read',targetTitle:'My Hero Academia, Chapter 43'};wsjModalPromoId='wsj_subscribe_modal_8609';wsjModalSource='My Hero Academia, Chapter 43';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8609,'/shonenjump/my-hero-academia-chapter-43/chapter/8609?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-43/chapter/8609?action=read',targetTitle:'My Hero Academia, Chapter 43'};wsjModalPromoId='wsj_subscribe_modal_8609';wsjModalSource='My Hero Academia, Chapter 43';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8609,'/shonenjump/my-hero-academia-chapter-43/chapter/8609?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8608"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="420">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-42/chapter/8608?action=read',targetTitle:'My Hero Academia, Chapter 42'};wsjModalPromoId='wsj_subscribe_modal_8608';wsjModalSource='My Hero Academia, Chapter 42';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8608,'/shonenjump/my-hero-academia-chapter-42/chapter/8608?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 42
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-42/chapter/8608?action=read',targetTitle:'My Hero Academia, Chapter 42'};wsjModalPromoId='wsj_subscribe_modal_8608';wsjModalSource='My Hero Academia, Chapter 42';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8608,'/shonenjump/my-hero-academia-chapter-42/chapter/8608?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-42/chapter/8608?action=read',targetTitle:'My Hero Academia, Chapter 42'};wsjModalPromoId='wsj_subscribe_modal_8608';wsjModalSource='My Hero Academia, Chapter 42';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8608,'/shonenjump/my-hero-academia-chapter-42/chapter/8608?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8607"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="410">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-41/chapter/8607?action=read',targetTitle:'My Hero Academia, Chapter 41'};wsjModalPromoId='wsj_subscribe_modal_8607';wsjModalSource='My Hero Academia, Chapter 41';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8607,'/shonenjump/my-hero-academia-chapter-41/chapter/8607?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 41
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-41/chapter/8607?action=read',targetTitle:'My Hero Academia, Chapter 41'};wsjModalPromoId='wsj_subscribe_modal_8607';wsjModalSource='My Hero Academia, Chapter 41';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8607,'/shonenjump/my-hero-academia-chapter-41/chapter/8607?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-41/chapter/8607?action=read',targetTitle:'My Hero Academia, Chapter 41'};wsjModalPromoId='wsj_subscribe_modal_8607';wsjModalSource='My Hero Academia, Chapter 41';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8607,'/shonenjump/my-hero-academia-chapter-41/chapter/8607?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8606"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="400">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-40/chapter/8606?action=read',targetTitle:'My Hero Academia, Chapter 40'};wsjModalPromoId='wsj_subscribe_modal_8606';wsjModalSource='My Hero Academia, Chapter 40';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8606,'/shonenjump/my-hero-academia-chapter-40/chapter/8606?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 40
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-40/chapter/8606?action=read',targetTitle:'My Hero Academia, Chapter 40'};wsjModalPromoId='wsj_subscribe_modal_8606';wsjModalSource='My Hero Academia, Chapter 40';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8606,'/shonenjump/my-hero-academia-chapter-40/chapter/8606?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-40/chapter/8606?action=read',targetTitle:'My Hero Academia, Chapter 40'};wsjModalPromoId='wsj_subscribe_modal_8606';wsjModalSource='My Hero Academia, Chapter 40';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8606,'/shonenjump/my-hero-academia-chapter-40/chapter/8606?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8605"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="390">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-39/chapter/8605?action=read',targetTitle:'My Hero Academia, Chapter 39'};wsjModalPromoId='wsj_subscribe_modal_8605';wsjModalSource='My Hero Academia, Chapter 39';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8605,'/shonenjump/my-hero-academia-chapter-39/chapter/8605?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 39
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-39/chapter/8605?action=read',targetTitle:'My Hero Academia, Chapter 39'};wsjModalPromoId='wsj_subscribe_modal_8605';wsjModalSource='My Hero Academia, Chapter 39';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8605,'/shonenjump/my-hero-academia-chapter-39/chapter/8605?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-39/chapter/8605?action=read',targetTitle:'My Hero Academia, Chapter 39'};wsjModalPromoId='wsj_subscribe_modal_8605';wsjModalSource='My Hero Academia, Chapter 39';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8605,'/shonenjump/my-hero-academia-chapter-39/chapter/8605?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8604"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="380">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-38/chapter/8604?action=read',targetTitle:'My Hero Academia, Chapter 38'};wsjModalPromoId='wsj_subscribe_modal_8604';wsjModalSource='My Hero Academia, Chapter 38';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8604,'/shonenjump/my-hero-academia-chapter-38/chapter/8604?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 38
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-38/chapter/8604?action=read',targetTitle:'My Hero Academia, Chapter 38'};wsjModalPromoId='wsj_subscribe_modal_8604';wsjModalSource='My Hero Academia, Chapter 38';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8604,'/shonenjump/my-hero-academia-chapter-38/chapter/8604?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-38/chapter/8604?action=read',targetTitle:'My Hero Academia, Chapter 38'};wsjModalPromoId='wsj_subscribe_modal_8604';wsjModalSource='My Hero Academia, Chapter 38';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8604,'/shonenjump/my-hero-academia-chapter-38/chapter/8604?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8603"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="370">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-37/chapter/8603?action=read',targetTitle:'My Hero Academia, Chapter 37'};wsjModalPromoId='wsj_subscribe_modal_8603';wsjModalSource='My Hero Academia, Chapter 37';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8603,'/shonenjump/my-hero-academia-chapter-37/chapter/8603?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 37
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-37/chapter/8603?action=read',targetTitle:'My Hero Academia, Chapter 37'};wsjModalPromoId='wsj_subscribe_modal_8603';wsjModalSource='My Hero Academia, Chapter 37';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8603,'/shonenjump/my-hero-academia-chapter-37/chapter/8603?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-37/chapter/8603?action=read',targetTitle:'My Hero Academia, Chapter 37'};wsjModalPromoId='wsj_subscribe_modal_8603';wsjModalSource='My Hero Academia, Chapter 37';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8603,'/shonenjump/my-hero-academia-chapter-37/chapter/8603?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="8602"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="360">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-36/chapter/8602?action=read',targetTitle:'My Hero Academia, Chapter 36'};wsjModalPromoId='wsj_subscribe_modal_8602';wsjModalSource='My Hero Academia, Chapter 36';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8602,'/shonenjump/my-hero-academia-chapter-36/chapter/8602?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 36
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-36/chapter/8602?action=read',targetTitle:'My Hero Academia, Chapter 36'};wsjModalPromoId='wsj_subscribe_modal_8602';wsjModalSource='My Hero Academia, Chapter 36';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8602,'/shonenjump/my-hero-academia-chapter-36/chapter/8602?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-36/chapter/8602?action=read',targetTitle:'My Hero Academia, Chapter 36'};wsjModalPromoId='wsj_subscribe_modal_8602';wsjModalSource='My Hero Academia, Chapter 36';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(8602,'/shonenjump/my-hero-academia-chapter-36/chapter/8602?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="63"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="350">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-4/product/3770/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421585111.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-4/product/3770/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="7563"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="350">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-35/chapter/7563?action=read',targetTitle:'My Hero Academia, Chapter 35'};wsjModalPromoId='wsj_subscribe_modal_7563';wsjModalSource='My Hero Academia, Chapter 35';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7563,'/shonenjump/my-hero-academia-chapter-35/chapter/7563?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 35
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-35/chapter/7563?action=read',targetTitle:'My Hero Academia, Chapter 35'};wsjModalPromoId='wsj_subscribe_modal_7563';wsjModalSource='My Hero Academia, Chapter 35';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7563,'/shonenjump/my-hero-academia-chapter-35/chapter/7563?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-35/chapter/7563?action=read',targetTitle:'My Hero Academia, Chapter 35'};wsjModalPromoId='wsj_subscribe_modal_7563';wsjModalSource='My Hero Academia, Chapter 35';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7563,'/shonenjump/my-hero-academia-chapter-35/chapter/7563?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="7562"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="340">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-34/chapter/7562?action=read',targetTitle:'My Hero Academia, Chapter 34'};wsjModalPromoId='wsj_subscribe_modal_7562';wsjModalSource='My Hero Academia, Chapter 34';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7562,'/shonenjump/my-hero-academia-chapter-34/chapter/7562?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 34
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-34/chapter/7562?action=read',targetTitle:'My Hero Academia, Chapter 34'};wsjModalPromoId='wsj_subscribe_modal_7562';wsjModalSource='My Hero Academia, Chapter 34';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7562,'/shonenjump/my-hero-academia-chapter-34/chapter/7562?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-34/chapter/7562?action=read',targetTitle:'My Hero Academia, Chapter 34'};wsjModalPromoId='wsj_subscribe_modal_7562';wsjModalSource='My Hero Academia, Chapter 34';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7562,'/shonenjump/my-hero-academia-chapter-34/chapter/7562?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="7561"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="330">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-33/chapter/7561?action=read',targetTitle:'My Hero Academia, Chapter 33'};wsjModalPromoId='wsj_subscribe_modal_7561';wsjModalSource='My Hero Academia, Chapter 33';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7561,'/shonenjump/my-hero-academia-chapter-33/chapter/7561?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 33
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-33/chapter/7561?action=read',targetTitle:'My Hero Academia, Chapter 33'};wsjModalPromoId='wsj_subscribe_modal_7561';wsjModalSource='My Hero Academia, Chapter 33';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7561,'/shonenjump/my-hero-academia-chapter-33/chapter/7561?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-33/chapter/7561?action=read',targetTitle:'My Hero Academia, Chapter 33'};wsjModalPromoId='wsj_subscribe_modal_7561';wsjModalSource='My Hero Academia, Chapter 33';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7561,'/shonenjump/my-hero-academia-chapter-33/chapter/7561?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="7560"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="320">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-32/chapter/7560?action=read',targetTitle:'My Hero Academia, Chapter 32'};wsjModalPromoId='wsj_subscribe_modal_7560';wsjModalSource='My Hero Academia, Chapter 32';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7560,'/shonenjump/my-hero-academia-chapter-32/chapter/7560?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 32
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-32/chapter/7560?action=read',targetTitle:'My Hero Academia, Chapter 32'};wsjModalPromoId='wsj_subscribe_modal_7560';wsjModalSource='My Hero Academia, Chapter 32';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7560,'/shonenjump/my-hero-academia-chapter-32/chapter/7560?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-32/chapter/7560?action=read',targetTitle:'My Hero Academia, Chapter 32'};wsjModalPromoId='wsj_subscribe_modal_7560';wsjModalSource='My Hero Academia, Chapter 32';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7560,'/shonenjump/my-hero-academia-chapter-32/chapter/7560?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="7559"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="310">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-31/chapter/7559?action=read',targetTitle:'My Hero Academia, Chapter 31'};wsjModalPromoId='wsj_subscribe_modal_7559';wsjModalSource='My Hero Academia, Chapter 31';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7559,'/shonenjump/my-hero-academia-chapter-31/chapter/7559?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 31
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-31/chapter/7559?action=read',targetTitle:'My Hero Academia, Chapter 31'};wsjModalPromoId='wsj_subscribe_modal_7559';wsjModalSource='My Hero Academia, Chapter 31';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7559,'/shonenjump/my-hero-academia-chapter-31/chapter/7559?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-31/chapter/7559?action=read',targetTitle:'My Hero Academia, Chapter 31'};wsjModalPromoId='wsj_subscribe_modal_7559';wsjModalSource='My Hero Academia, Chapter 31';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7559,'/shonenjump/my-hero-academia-chapter-31/chapter/7559?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="7558"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="300">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-30/chapter/7558?action=read',targetTitle:'My Hero Academia, Chapter 30'};wsjModalPromoId='wsj_subscribe_modal_7558';wsjModalSource='My Hero Academia, Chapter 30';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7558,'/shonenjump/my-hero-academia-chapter-30/chapter/7558?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 30
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-30/chapter/7558?action=read',targetTitle:'My Hero Academia, Chapter 30'};wsjModalPromoId='wsj_subscribe_modal_7558';wsjModalSource='My Hero Academia, Chapter 30';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7558,'/shonenjump/my-hero-academia-chapter-30/chapter/7558?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-30/chapter/7558?action=read',targetTitle:'My Hero Academia, Chapter 30'};wsjModalPromoId='wsj_subscribe_modal_7558';wsjModalSource='My Hero Academia, Chapter 30';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7558,'/shonenjump/my-hero-academia-chapter-30/chapter/7558?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="7557"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="290">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-29/chapter/7557?action=read',targetTitle:'My Hero Academia, Chapter 29'};wsjModalPromoId='wsj_subscribe_modal_7557';wsjModalSource='My Hero Academia, Chapter 29';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7557,'/shonenjump/my-hero-academia-chapter-29/chapter/7557?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 29
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-29/chapter/7557?action=read',targetTitle:'My Hero Academia, Chapter 29'};wsjModalPromoId='wsj_subscribe_modal_7557';wsjModalSource='My Hero Academia, Chapter 29';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7557,'/shonenjump/my-hero-academia-chapter-29/chapter/7557?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-29/chapter/7557?action=read',targetTitle:'My Hero Academia, Chapter 29'};wsjModalPromoId='wsj_subscribe_modal_7557';wsjModalSource='My Hero Academia, Chapter 29';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7557,'/shonenjump/my-hero-academia-chapter-29/chapter/7557?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="7556"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="280">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-28/chapter/7556?action=read',targetTitle:'My Hero Academia, Chapter 28'};wsjModalPromoId='wsj_subscribe_modal_7556';wsjModalSource='My Hero Academia, Chapter 28';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7556,'/shonenjump/my-hero-academia-chapter-28/chapter/7556?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 28
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-28/chapter/7556?action=read',targetTitle:'My Hero Academia, Chapter 28'};wsjModalPromoId='wsj_subscribe_modal_7556';wsjModalSource='My Hero Academia, Chapter 28';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7556,'/shonenjump/my-hero-academia-chapter-28/chapter/7556?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-28/chapter/7556?action=read',targetTitle:'My Hero Academia, Chapter 28'};wsjModalPromoId='wsj_subscribe_modal_7556';wsjModalSource='My Hero Academia, Chapter 28';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7556,'/shonenjump/my-hero-academia-chapter-28/chapter/7556?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="7555"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="270">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-27/chapter/7555?action=read',targetTitle:'My Hero Academia, Chapter 27'};wsjModalPromoId='wsj_subscribe_modal_7555';wsjModalSource='My Hero Academia, Chapter 27';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7555,'/shonenjump/my-hero-academia-chapter-27/chapter/7555?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 27
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-27/chapter/7555?action=read',targetTitle:'My Hero Academia, Chapter 27'};wsjModalPromoId='wsj_subscribe_modal_7555';wsjModalSource='My Hero Academia, Chapter 27';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7555,'/shonenjump/my-hero-academia-chapter-27/chapter/7555?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-27/chapter/7555?action=read',targetTitle:'My Hero Academia, Chapter 27'};wsjModalPromoId='wsj_subscribe_modal_7555';wsjModalSource='My Hero Academia, Chapter 27';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(7555,'/shonenjump/my-hero-academia-chapter-27/chapter/7555?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="64"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="260">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-3/product/3769/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421585103.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-3/product/3769/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5607"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="260">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-26/chapter/5607?action=read',targetTitle:'My Hero Academia, Chapter 26'};wsjModalPromoId='wsj_subscribe_modal_5607';wsjModalSource='My Hero Academia, Chapter 26';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5607,'/shonenjump/my-hero-academia-chapter-26/chapter/5607?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 26
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-26/chapter/5607?action=read',targetTitle:'My Hero Academia, Chapter 26'};wsjModalPromoId='wsj_subscribe_modal_5607';wsjModalSource='My Hero Academia, Chapter 26';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5607,'/shonenjump/my-hero-academia-chapter-26/chapter/5607?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-26/chapter/5607?action=read',targetTitle:'My Hero Academia, Chapter 26'};wsjModalPromoId='wsj_subscribe_modal_5607';wsjModalSource='My Hero Academia, Chapter 26';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5607,'/shonenjump/my-hero-academia-chapter-26/chapter/5607?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5606"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="250">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-25/chapter/5606?action=read',targetTitle:'My Hero Academia, Chapter 25'};wsjModalPromoId='wsj_subscribe_modal_5606';wsjModalSource='My Hero Academia, Chapter 25';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5606,'/shonenjump/my-hero-academia-chapter-25/chapter/5606?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 25
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-25/chapter/5606?action=read',targetTitle:'My Hero Academia, Chapter 25'};wsjModalPromoId='wsj_subscribe_modal_5606';wsjModalSource='My Hero Academia, Chapter 25';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5606,'/shonenjump/my-hero-academia-chapter-25/chapter/5606?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-25/chapter/5606?action=read',targetTitle:'My Hero Academia, Chapter 25'};wsjModalPromoId='wsj_subscribe_modal_5606';wsjModalSource='My Hero Academia, Chapter 25';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5606,'/shonenjump/my-hero-academia-chapter-25/chapter/5606?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5605"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="240">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-24/chapter/5605?action=read',targetTitle:'My Hero Academia, Chapter 24'};wsjModalPromoId='wsj_subscribe_modal_5605';wsjModalSource='My Hero Academia, Chapter 24';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5605,'/shonenjump/my-hero-academia-chapter-24/chapter/5605?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 24
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-24/chapter/5605?action=read',targetTitle:'My Hero Academia, Chapter 24'};wsjModalPromoId='wsj_subscribe_modal_5605';wsjModalSource='My Hero Academia, Chapter 24';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5605,'/shonenjump/my-hero-academia-chapter-24/chapter/5605?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-24/chapter/5605?action=read',targetTitle:'My Hero Academia, Chapter 24'};wsjModalPromoId='wsj_subscribe_modal_5605';wsjModalSource='My Hero Academia, Chapter 24';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5605,'/shonenjump/my-hero-academia-chapter-24/chapter/5605?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5604"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="230">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-23/chapter/5604?action=read',targetTitle:'My Hero Academia, Chapter 23'};wsjModalPromoId='wsj_subscribe_modal_5604';wsjModalSource='My Hero Academia, Chapter 23';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5604,'/shonenjump/my-hero-academia-chapter-23/chapter/5604?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 23
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-23/chapter/5604?action=read',targetTitle:'My Hero Academia, Chapter 23'};wsjModalPromoId='wsj_subscribe_modal_5604';wsjModalSource='My Hero Academia, Chapter 23';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5604,'/shonenjump/my-hero-academia-chapter-23/chapter/5604?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-23/chapter/5604?action=read',targetTitle:'My Hero Academia, Chapter 23'};wsjModalPromoId='wsj_subscribe_modal_5604';wsjModalSource='My Hero Academia, Chapter 23';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5604,'/shonenjump/my-hero-academia-chapter-23/chapter/5604?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5603"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="220">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-22/chapter/5603?action=read',targetTitle:'My Hero Academia, Chapter 22'};wsjModalPromoId='wsj_subscribe_modal_5603';wsjModalSource='My Hero Academia, Chapter 22';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5603,'/shonenjump/my-hero-academia-chapter-22/chapter/5603?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 22
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-22/chapter/5603?action=read',targetTitle:'My Hero Academia, Chapter 22'};wsjModalPromoId='wsj_subscribe_modal_5603';wsjModalSource='My Hero Academia, Chapter 22';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5603,'/shonenjump/my-hero-academia-chapter-22/chapter/5603?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-22/chapter/5603?action=read',targetTitle:'My Hero Academia, Chapter 22'};wsjModalPromoId='wsj_subscribe_modal_5603';wsjModalSource='My Hero Academia, Chapter 22';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5603,'/shonenjump/my-hero-academia-chapter-22/chapter/5603?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5602"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="210">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-21/chapter/5602?action=read',targetTitle:'My Hero Academia, Chapter 21'};wsjModalPromoId='wsj_subscribe_modal_5602';wsjModalSource='My Hero Academia, Chapter 21';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5602,'/shonenjump/my-hero-academia-chapter-21/chapter/5602?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 21
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-21/chapter/5602?action=read',targetTitle:'My Hero Academia, Chapter 21'};wsjModalPromoId='wsj_subscribe_modal_5602';wsjModalSource='My Hero Academia, Chapter 21';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5602,'/shonenjump/my-hero-academia-chapter-21/chapter/5602?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-21/chapter/5602?action=read',targetTitle:'My Hero Academia, Chapter 21'};wsjModalPromoId='wsj_subscribe_modal_5602';wsjModalSource='My Hero Academia, Chapter 21';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5602,'/shonenjump/my-hero-academia-chapter-21/chapter/5602?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5601"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="200">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-20/chapter/5601?action=read',targetTitle:'My Hero Academia, Chapter 20'};wsjModalPromoId='wsj_subscribe_modal_5601';wsjModalSource='My Hero Academia, Chapter 20';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5601,'/shonenjump/my-hero-academia-chapter-20/chapter/5601?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 20
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-20/chapter/5601?action=read',targetTitle:'My Hero Academia, Chapter 20'};wsjModalPromoId='wsj_subscribe_modal_5601';wsjModalSource='My Hero Academia, Chapter 20';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5601,'/shonenjump/my-hero-academia-chapter-20/chapter/5601?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-20/chapter/5601?action=read',targetTitle:'My Hero Academia, Chapter 20'};wsjModalPromoId='wsj_subscribe_modal_5601';wsjModalSource='My Hero Academia, Chapter 20';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5601,'/shonenjump/my-hero-academia-chapter-20/chapter/5601?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5600"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="190">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-19/chapter/5600?action=read',targetTitle:'My Hero Academia, Chapter 19'};wsjModalPromoId='wsj_subscribe_modal_5600';wsjModalSource='My Hero Academia, Chapter 19';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5600,'/shonenjump/my-hero-academia-chapter-19/chapter/5600?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 19
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-19/chapter/5600?action=read',targetTitle:'My Hero Academia, Chapter 19'};wsjModalPromoId='wsj_subscribe_modal_5600';wsjModalSource='My Hero Academia, Chapter 19';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5600,'/shonenjump/my-hero-academia-chapter-19/chapter/5600?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-19/chapter/5600?action=read',targetTitle:'My Hero Academia, Chapter 19'};wsjModalPromoId='wsj_subscribe_modal_5600';wsjModalSource='My Hero Academia, Chapter 19';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5600,'/shonenjump/my-hero-academia-chapter-19/chapter/5600?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5599"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="180">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-18/chapter/5599?action=read',targetTitle:'My Hero Academia, Chapter 18'};wsjModalPromoId='wsj_subscribe_modal_5599';wsjModalSource='My Hero Academia, Chapter 18';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5599,'/shonenjump/my-hero-academia-chapter-18/chapter/5599?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 18
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-18/chapter/5599?action=read',targetTitle:'My Hero Academia, Chapter 18'};wsjModalPromoId='wsj_subscribe_modal_5599';wsjModalSource='My Hero Academia, Chapter 18';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5599,'/shonenjump/my-hero-academia-chapter-18/chapter/5599?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-18/chapter/5599?action=read',targetTitle:'My Hero Academia, Chapter 18'};wsjModalPromoId='wsj_subscribe_modal_5599';wsjModalSource='My Hero Academia, Chapter 18';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5599,'/shonenjump/my-hero-academia-chapter-18/chapter/5599?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="65"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="170">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-2/product/3768/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421582708.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-2/product/3768/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="5615"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="170">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-17/chapter/5615?action=read',targetTitle:'My Hero Academia, Chapter 17'};wsjModalPromoId='wsj_subscribe_modal_5615';wsjModalSource='My Hero Academia, Chapter 17';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5615,'/shonenjump/my-hero-academia-chapter-17/chapter/5615?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 17
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-17/chapter/5615?action=read',targetTitle:'My Hero Academia, Chapter 17'};wsjModalPromoId='wsj_subscribe_modal_5615';wsjModalSource='My Hero Academia, Chapter 17';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5615,'/shonenjump/my-hero-academia-chapter-17/chapter/5615?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-17/chapter/5615?action=read',targetTitle:'My Hero Academia, Chapter 17'};wsjModalPromoId='wsj_subscribe_modal_5615';wsjModalSource='My Hero Academia, Chapter 17';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(5615,'/shonenjump/my-hero-academia-chapter-17/chapter/5615?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4752"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="160">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-16/chapter/4752?action=read',targetTitle:'My Hero Academia, Chapter 16'};wsjModalPromoId='wsj_subscribe_modal_4752';wsjModalSource='My Hero Academia, Chapter 16';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4752,'/shonenjump/my-hero-academia-chapter-16/chapter/4752?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 16
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-16/chapter/4752?action=read',targetTitle:'My Hero Academia, Chapter 16'};wsjModalPromoId='wsj_subscribe_modal_4752';wsjModalSource='My Hero Academia, Chapter 16';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4752,'/shonenjump/my-hero-academia-chapter-16/chapter/4752?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-16/chapter/4752?action=read',targetTitle:'My Hero Academia, Chapter 16'};wsjModalPromoId='wsj_subscribe_modal_4752';wsjModalSource='My Hero Academia, Chapter 16';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4752,'/shonenjump/my-hero-academia-chapter-16/chapter/4752?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4751"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="150">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-15/chapter/4751?action=read',targetTitle:'My Hero Academia, Chapter 15'};wsjModalPromoId='wsj_subscribe_modal_4751';wsjModalSource='My Hero Academia, Chapter 15';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4751,'/shonenjump/my-hero-academia-chapter-15/chapter/4751?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 15
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-15/chapter/4751?action=read',targetTitle:'My Hero Academia, Chapter 15'};wsjModalPromoId='wsj_subscribe_modal_4751';wsjModalSource='My Hero Academia, Chapter 15';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4751,'/shonenjump/my-hero-academia-chapter-15/chapter/4751?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-15/chapter/4751?action=read',targetTitle:'My Hero Academia, Chapter 15'};wsjModalPromoId='wsj_subscribe_modal_4751';wsjModalSource='My Hero Academia, Chapter 15';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4751,'/shonenjump/my-hero-academia-chapter-15/chapter/4751?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4750"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="140">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-14/chapter/4750?action=read',targetTitle:'My Hero Academia, Chapter 14'};wsjModalPromoId='wsj_subscribe_modal_4750';wsjModalSource='My Hero Academia, Chapter 14';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4750,'/shonenjump/my-hero-academia-chapter-14/chapter/4750?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 14
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-14/chapter/4750?action=read',targetTitle:'My Hero Academia, Chapter 14'};wsjModalPromoId='wsj_subscribe_modal_4750';wsjModalSource='My Hero Academia, Chapter 14';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4750,'/shonenjump/my-hero-academia-chapter-14/chapter/4750?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-14/chapter/4750?action=read',targetTitle:'My Hero Academia, Chapter 14'};wsjModalPromoId='wsj_subscribe_modal_4750';wsjModalSource='My Hero Academia, Chapter 14';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4750,'/shonenjump/my-hero-academia-chapter-14/chapter/4750?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4749"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="130">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-13/chapter/4749?action=read',targetTitle:'My Hero Academia, Chapter 13'};wsjModalPromoId='wsj_subscribe_modal_4749';wsjModalSource='My Hero Academia, Chapter 13';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4749,'/shonenjump/my-hero-academia-chapter-13/chapter/4749?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 13
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-13/chapter/4749?action=read',targetTitle:'My Hero Academia, Chapter 13'};wsjModalPromoId='wsj_subscribe_modal_4749';wsjModalSource='My Hero Academia, Chapter 13';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4749,'/shonenjump/my-hero-academia-chapter-13/chapter/4749?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-13/chapter/4749?action=read',targetTitle:'My Hero Academia, Chapter 13'};wsjModalPromoId='wsj_subscribe_modal_4749';wsjModalSource='My Hero Academia, Chapter 13';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4749,'/shonenjump/my-hero-academia-chapter-13/chapter/4749?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4748"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="120">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-12/chapter/4748?action=read',targetTitle:'My Hero Academia, Chapter 12'};wsjModalPromoId='wsj_subscribe_modal_4748';wsjModalSource='My Hero Academia, Chapter 12';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4748,'/shonenjump/my-hero-academia-chapter-12/chapter/4748?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 12
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-12/chapter/4748?action=read',targetTitle:'My Hero Academia, Chapter 12'};wsjModalPromoId='wsj_subscribe_modal_4748';wsjModalSource='My Hero Academia, Chapter 12';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4748,'/shonenjump/my-hero-academia-chapter-12/chapter/4748?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-12/chapter/4748?action=read',targetTitle:'My Hero Academia, Chapter 12'};wsjModalPromoId='wsj_subscribe_modal_4748';wsjModalSource='My Hero Academia, Chapter 12';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4748,'/shonenjump/my-hero-academia-chapter-12/chapter/4748?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4747"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="110">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-11/chapter/4747?action=read',targetTitle:'My Hero Academia, Chapter 11'};wsjModalPromoId='wsj_subscribe_modal_4747';wsjModalSource='My Hero Academia, Chapter 11';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4747,'/shonenjump/my-hero-academia-chapter-11/chapter/4747?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 11
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-11/chapter/4747?action=read',targetTitle:'My Hero Academia, Chapter 11'};wsjModalPromoId='wsj_subscribe_modal_4747';wsjModalSource='My Hero Academia, Chapter 11';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4747,'/shonenjump/my-hero-academia-chapter-11/chapter/4747?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-11/chapter/4747?action=read',targetTitle:'My Hero Academia, Chapter 11'};wsjModalPromoId='wsj_subscribe_modal_4747';wsjModalSource='My Hero Academia, Chapter 11';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4747,'/shonenjump/my-hero-academia-chapter-11/chapter/4747?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4746"
                data-sort-recent="8"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="100">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-10/chapter/4746?action=read',targetTitle:'My Hero Academia, Chapter 10'};wsjModalPromoId='wsj_subscribe_modal_4746';wsjModalSource='My Hero Academia, Chapter 10';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4746,'/shonenjump/my-hero-academia-chapter-10/chapter/4746?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 10
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-10/chapter/4746?action=read',targetTitle:'My Hero Academia, Chapter 10'};wsjModalPromoId='wsj_subscribe_modal_4746';wsjModalSource='My Hero Academia, Chapter 10';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4746,'/shonenjump/my-hero-academia-chapter-10/chapter/4746?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-10/chapter/4746?action=read',targetTitle:'My Hero Academia, Chapter 10'};wsjModalPromoId='wsj_subscribe_modal_4746';wsjModalSource='My Hero Academia, Chapter 10';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4746,'/shonenjump/my-hero-academia-chapter-10/chapter/4746?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4745"
                data-sort-recent="9"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="90">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-9/chapter/4745?action=read',targetTitle:'My Hero Academia, Chapter 9'};wsjModalPromoId='wsj_subscribe_modal_4745';wsjModalSource='My Hero Academia, Chapter 9';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4745,'/shonenjump/my-hero-academia-chapter-9/chapter/4745?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 9
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-9/chapter/4745?action=read',targetTitle:'My Hero Academia, Chapter 9'};wsjModalPromoId='wsj_subscribe_modal_4745';wsjModalSource='My Hero Academia, Chapter 9';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4745,'/shonenjump/my-hero-academia-chapter-9/chapter/4745?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-9/chapter/4745?action=read',targetTitle:'My Hero Academia, Chapter 9'};wsjModalPromoId='wsj_subscribe_modal_4745';wsjModalSource='My Hero Academia, Chapter 9';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4745,'/shonenjump/my-hero-academia-chapter-9/chapter/4745?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4744"
                data-sort-recent="10"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="80">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-8/chapter/4744?action=read',targetTitle:'My Hero Academia, Chapter 8'};wsjModalPromoId='wsj_subscribe_modal_4744';wsjModalSource='My Hero Academia, Chapter 8';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4744,'/shonenjump/my-hero-academia-chapter-8/chapter/4744?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 8
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-8/chapter/4744?action=read',targetTitle:'My Hero Academia, Chapter 8'};wsjModalPromoId='wsj_subscribe_modal_4744';wsjModalSource='My Hero Academia, Chapter 8';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4744,'/shonenjump/my-hero-academia-chapter-8/chapter/4744?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-8/chapter/4744?action=read',targetTitle:'My Hero Academia, Chapter 8'};wsjModalPromoId='wsj_subscribe_modal_4744';wsjModalSource='My Hero Academia, Chapter 8';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4744,'/shonenjump/my-hero-academia-chapter-8/chapter/4744?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


<div style="width:100%;" class="o_sortable brdr-dotted-lid"
     data-sort-recent="66"
     data-sort-alpha-label="myheroacademia"
     data-sort-alpha-num="70">

    <div class="flex o_chapter-vol-container">
      <div class="c1-image flex-width-2 pad-y-lg pos-r">
        <table height="100%" class="float-r">
          <tr>
            <td class="o_sticky-container" align="center" valign="top">
              <div class="o_sticky">
                <a href="/read/manga/my-hero-academia-volume-1/product/3767/digital" target="_gn">
                  <img style="max-height:280px;" class="lazy"
                       data-original="https://dw9to29mmj727.cloudfront.net/products/1421582694.jpg"
                       src="https://dw9to29mmj727.cloudfront.net/misc/placeholder_200x300.png">
                </a>
                <div class="mar-y-rg">
                  <a href="/read/manga/my-hero-academia-volume-1/product/3767/digital" target="_gn" class="o_manga-buy-now btn-primary pad-y-rg pad-x-md type-sm">Buy the volume</a>
                </div>
              </div>
            </td>
          </tr>
        </table>
      </div>
      <div class="pad-l-md pad-l-lg--lg type-rg--lg type-sm line-caption flex-width-2">
        <table class="o_gn-chapter-list o_sort_container-b" width="100%" height="100%">
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4743"
                data-sort-recent="1"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="70">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-7/chapter/4743?action=read',targetTitle:'My Hero Academia, Chapter 7'};wsjModalPromoId='wsj_subscribe_modal_4743';wsjModalSource='My Hero Academia, Chapter 7';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4743,'/shonenjump/my-hero-academia-chapter-7/chapter/4743?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 7
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-7/chapter/4743?action=read',targetTitle:'My Hero Academia, Chapter 7'};wsjModalPromoId='wsj_subscribe_modal_4743';wsjModalSource='My Hero Academia, Chapter 7';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4743,'/shonenjump/my-hero-academia-chapter-7/chapter/4743?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-7/chapter/4743?action=read',targetTitle:'My Hero Academia, Chapter 7'};wsjModalPromoId='wsj_subscribe_modal_4743';wsjModalSource='My Hero Academia, Chapter 7';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4743,'/shonenjump/my-hero-academia-chapter-7/chapter/4743?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4742"
                data-sort-recent="2"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="60">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-6/chapter/4742?action=read',targetTitle:'My Hero Academia, Chapter 6'};wsjModalPromoId='wsj_subscribe_modal_4742';wsjModalSource='My Hero Academia, Chapter 6';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4742,'/shonenjump/my-hero-academia-chapter-6/chapter/4742?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 6
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-6/chapter/4742?action=read',targetTitle:'My Hero Academia, Chapter 6'};wsjModalPromoId='wsj_subscribe_modal_4742';wsjModalSource='My Hero Academia, Chapter 6';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4742,'/shonenjump/my-hero-academia-chapter-6/chapter/4742?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-6/chapter/4742?action=read',targetTitle:'My Hero Academia, Chapter 6'};wsjModalPromoId='wsj_subscribe_modal_4742';wsjModalSource='My Hero Academia, Chapter 6';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4742,'/shonenjump/my-hero-academia-chapter-6/chapter/4742?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4741"
                data-sort-recent="3"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="50">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-5/chapter/4741?action=read',targetTitle:'My Hero Academia, Chapter 5'};wsjModalPromoId='wsj_subscribe_modal_4741';wsjModalSource='My Hero Academia, Chapter 5';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4741,'/shonenjump/my-hero-academia-chapter-5/chapter/4741?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 5
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-5/chapter/4741?action=read',targetTitle:'My Hero Academia, Chapter 5'};wsjModalPromoId='wsj_subscribe_modal_4741';wsjModalSource='My Hero Academia, Chapter 5';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4741,'/shonenjump/my-hero-academia-chapter-5/chapter/4741?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-5/chapter/4741?action=read',targetTitle:'My Hero Academia, Chapter 5'};wsjModalPromoId='wsj_subscribe_modal_4741';wsjModalSource='My Hero Academia, Chapter 5';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4741,'/shonenjump/my-hero-academia-chapter-5/chapter/4741?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4740"
                data-sort-recent="4"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="40">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-4/chapter/4740?action=read',targetTitle:'My Hero Academia, Chapter 4'};wsjModalPromoId='wsj_subscribe_modal_4740';wsjModalSource='My Hero Academia, Chapter 4';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4740,'/shonenjump/my-hero-academia-chapter-4/chapter/4740?action=read');" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 4
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-4/chapter/4740?action=read',targetTitle:'My Hero Academia, Chapter 4'};wsjModalPromoId='wsj_subscribe_modal_4740';wsjModalSource='My Hero Academia, Chapter 4';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4740,'/shonenjump/my-hero-academia-chapter-4/chapter/4740?action=read');" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-archive o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-black bg-yellow hover-bg-orange"><span style="white-space:nowrap;"><i class="icon-lock"    style="margin-right:5px;"></i>Join to read</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="javascript:void('join to read');" onclick="Modals.context={targetUrl:'/shonenjump/my-hero-academia-chapter-4/chapter/4740?action=read',targetTitle:'My Hero Academia, Chapter 4'};wsjModalPromoId='wsj_subscribe_modal_4740';wsjModalSource='My Hero Academia, Chapter 4';dataLayer.push({'ecommerce':{'promoView':{'promotions':[{'id':wsjModalPromoId,'name':'WSJ Subscribe Modal','creative':wsjModalSource,'position':wsjModalPosition}]}}});Modals.toggle('#modal-sj-join');Tracking.sendEvent({'category':'Join to Read','action':'Click [button]','label':'title'});" data-target-url="javascript:tryReadChapter(4740,'/shonenjump/my-hero-academia-chapter-4/chapter/4740?action=read');" style="height:100%; width:100%;"
                   class="o_chapter-archive o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4739"
                data-sort-recent="5"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="30">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="/shonenjump/my-hero-academia-chapter-3/chapter/4739?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-3/chapter/4739?action=read" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 3
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="/shonenjump/my-hero-academia-chapter-3/chapter/4739?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-3/chapter/4739?action=read" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-white bg-green  hover-bg-green"><span style="white-space:nowrap;"><i class="icon-eye"     style="margin-right:5px;"></i>FREE</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="/shonenjump/my-hero-academia-chapter-3/chapter/4739?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-3/chapter/4739?action=read" style="height:100%; width:100%;"
                   class="o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4738"
                data-sort-recent="6"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="20">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="/shonenjump/my-hero-academia-chapter-2/chapter/4738?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-2/chapter/4738?action=read" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 2
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="/shonenjump/my-hero-academia-chapter-2/chapter/4738?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-2/chapter/4738?action=read" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-white bg-green  hover-bg-green"><span style="white-space:nowrap;"><i class="icon-eye"     style="margin-right:5px;"></i>FREE</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="/shonenjump/my-hero-academia-chapter-2/chapter/4738?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-2/chapter/4738?action=read" style="height:100%; width:100%;"
                   class="o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
            <tr class="o_chapter o_sortable-b hover-bg-lighter-gray brdr-dotted-inner" 
                data-mc_id="4737"
                data-sort-recent="7"
                data-sort-alpha-label="myheroacademia"
                data-sort-alpha-num="10">
              <td valign="middle" class="pad-y-0 ch-num-list-spacing">
                <a href="/shonenjump/my-hero-academia-chapter-1/chapter/4737?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-1/chapter/4737?action=read" style="height:100%; width:100%; white-space:nowrap; display:table-cell;"
                   class="o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg pad-r-0 pad-r-rg--sm">
                  Ch. 1
                </a>
              </td>
              <td valign="middle" class="pad-y-0">
                <a href="/shonenjump/my-hero-academia-chapter-1/chapter/4737?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-1/chapter/4737?action=read" style="height:100%; width:100%; display:table-cell;"
                   class="o_chapter-container color-off-black hover-off-black pad-y-rg pad-y-md--lg">
                  <div class="o_read-link-label pad-y-sm pad-x-rg type-sm o_read-link-label btn-primary color-off-white bg-green  hover-bg-green"><span style="white-space:nowrap;"><i class="icon-eye"     style="margin-right:5px;"></i>FREE</span></div>
                </a>
              </td>
              <td width="99%" class="pad-y-0">
                <a href="/shonenjump/my-hero-academia-chapter-1/chapter/4737?action=read" data-target-url="/shonenjump/my-hero-academia-chapter-1/chapter/4737?action=read" style="height:100%; width:100%;"
                   class="o_chapter-container disp-bl">&nbsp;</a>
              </td>
            </tr>
        </table>
      </div>
    </div>

</div>


        </div>
      </div>
  
  </section>


      <section class="section_manga mar-t-xl bg-off-white" id="section1">
  <div class="row mar-last-row">
      <div class="clearfix mar-t-md mar-b-lg">
            <h3 class="type-md type-lg--lg line-solid float-l--lg">Get the whole series</h3>
          <div class="section_see_all float-r--lg mar-t-md type-rg disp-n disp-bl--md">
            <a href="/read/my-hero-academia/section/50287/more" class="color-mid-gray hover-red">
              See all
            </a>
          </div>
      </div>
      <div class="shelf flex flex-wrap clearfix type-rg line-caption">
          <article class="g-3 g-3--md mar-b-lg bg-white color-off-black type-sm type-rg--lg">
  <figure class="ar-square">
      <a href="javascript:void('Favorite')" class="heart-btn o_requires-login pad-x-md pad-y-sm pos-a t-0 l-0 z-2 color-mid-gray hover-red"
         data-target-id="pr_13857" 
         data-target-title="My Hero Academia, Vol. 23">
        <i class="icon-like"></i>
        <span class="o_votes-up disp-ib v-mid type-sm color-mid-gray mar-l-sm">
          +51
        </span>
      </a>
      <span class="product-tag pad-x-rg pad-y-sm pos-a t-0 r-0 z-2 bg-mid-gray color-white">Pre-Order</span>
    <a href="/read/manga/my-hero-academia-volume-23/product/6162" class="product-thumb ar-inner type-center">
      <img class="lazy" data-original="https://dw9to29mmj727.cloudfront.net/products/1974709663.jpg" onerror="imgError(this);" />
    </a>
  </figure>
  <div class="pad-x-md pad-x-lg--lg pad-b-md pad-b-lg--lg">
    <div class="mar-b-sm"><a class="color-mid-gray hover-red">Manga</a></div>
    <h4>
      <a class="color-off-black hover-red" href="/read/manga/my-hero-academia-volume-23/product/6162">My Hero Academia, Vol. 23</a>
    </h4>
  </div>
</article>

          <article class="g-3 g-3--md mar-b-lg g-omega bg-white color-off-black type-sm type-rg--lg">
  <figure class="ar-square">
      <a href="javascript:void('Favorite')" class="heart-btn o_requires-login pad-x-md pad-y-sm pos-a t-0 l-0 z-2 color-mid-gray hover-red"
         data-target-id="pr_13772" 
         data-target-title="My Hero Academia: Smash!!, Vol. 3">
        <i class="icon-like"></i>
        <span class="o_votes-up disp-ib v-mid type-sm color-mid-gray mar-l-sm">
          +19
        </span>
      </a>
      <span class="product-tag pad-x-rg pad-y-sm pos-a t-0 r-0 z-2 bg-mid-gray color-white">Pre-Order</span>
    <a href="/read/manga/my-hero-academia-smash-volume-3/product/6175" class="product-thumb ar-inner type-center">
      <img class="lazy" data-original="https://dw9to29mmj727.cloudfront.net/products/1974708683.jpg" onerror="imgError(this);" />
    </a>
  </figure>
  <div class="pad-x-md pad-x-lg--lg pad-b-md pad-b-lg--lg">
    <div class="mar-b-sm"><a class="color-mid-gray hover-red">Manga</a></div>
    <h4>
      <a class="color-off-black hover-red" href="/read/manga/my-hero-academia-smash-volume-3/product/6175">My Hero Academia: Smash!!, Vol. 3</a>
    </h4>
  </div>
</article>

          <article class="g-3 g-3--md mar-b-lg bg-white color-off-black type-sm type-rg--lg">
  <figure class="ar-square">
      <a href="javascript:void('Favorite')" class="heart-btn o_requires-login pad-x-md pad-y-sm pos-a t-0 l-0 z-2 color-mid-gray hover-red"
         data-target-id="pr_13947" 
         data-target-title="My Hero Academia: Vigilantes, Vol. 6">
        <i class="icon-like"></i>
        <span class="o_votes-up disp-ib v-mid type-sm color-mid-gray mar-l-sm">
          +56
        </span>
      </a>
    <a href="/read/manga/my-hero-academia-vigilantes-volume-6/product/6060" class="product-thumb ar-inner type-center">
      <img class="lazy" data-original="https://dw9to29mmj727.cloudfront.net/products/197471053X.jpg" onerror="imgError(this);" />
    </a>
  </figure>
  <div class="pad-x-md pad-x-lg--lg pad-b-md pad-b-lg--lg">
    <div class="mar-b-sm"><a class="color-mid-gray hover-red">Manga</a></div>
    <h4>
      <a class="color-off-black hover-red" href="/read/manga/my-hero-academia-vigilantes-volume-6/product/6060">My Hero Academia: Vigilantes, Vol. 6</a>
    </h4>
  </div>
</article>

          <article class="g-3 g-3--md mar-b-lg g-omega g-omega--md bg-white color-off-black type-sm type-rg--lg">
  <figure class="ar-square">
      <a href="javascript:void('Favorite')" class="heart-btn o_requires-login pad-x-md pad-y-sm pos-a t-0 l-0 z-2 color-mid-gray hover-red"
         data-target-id="pr_13856" 
         data-target-title="My Hero Academia, Vol. 22">
        <i class="icon-like"></i>
        <span class="o_votes-up disp-ib v-mid type-sm color-mid-gray mar-l-sm">
          +109
        </span>
      </a>
    <a href="/read/manga/my-hero-academia-volume-22/product/6124" class="product-thumb ar-inner type-center">
      <img class="lazy" data-original="https://dw9to29mmj727.cloudfront.net/products/1974709655.jpg" onerror="imgError(this);" />
    </a>
  </figure>
  <div class="pad-x-md pad-x-lg--lg pad-b-md pad-b-lg--lg">
    <div class="mar-b-sm"><a class="color-mid-gray hover-red">Manga</a></div>
    <h4>
      <a class="color-off-black hover-red" href="/read/manga/my-hero-academia-volume-22/product/6124">My Hero Academia, Vol. 22</a>
    </h4>
  </div>
</article>

      </div>

        <div class="section_see_all mar-b-md type-rg disp-bl disp-n--md">
          <a href="/read/my-hero-academia/section/50287/more" class="color-mid-gray hover-red">
            See all
          </a>
        </div>

  </div>
</section>



</div>

  
<script type="text/javascript">
    showSmartBanner(true, 1000);
</script>




    <div id="modal-err" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg" data-modal-state="off">
  <a href="#modal-err" data-modal-btn class="modal-close">
    <i class="icon-close"></i>
  </a>
  <div class="modal-g-lg shift mar-b-lg">
    <h2 class="o_err-title type-md weight-bold style-caps line-solid"></h2>
    <div class="o_err-msg type-rg mar-t-md"><p></p></div>
  </div>
  <div class="modal-actions">
    <div class="modal-g-lg shift">
      <input type="button" class="btn-primary type-rg pad-x-xl" value="OK" />
    </div>
  </div>
</div>

<div id="modal-confirm" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg" data-modal-state="off">
  <a href="#modal-confirm" data-modal-btn class="modal-close">
    <i class="icon-close"></i>
  </a>
  <div class="modal-g-lg shift mar-b-lg">
    <h2 class="o_confirm-title type-md weight-bold style-caps line-solid"></h2>
    <div class="o_confirm-msg type-rg mar-t-md"></div>
  </div>
  <div class="modal-actions">
    <div class="modal-g-lg shift">
      <div class="disp-ib mar-b-rg">
        <input type="button" class="o_confirm-yes btn-primary type-rg pad-x-md mar-r-md" value="Yes" />
      </div>
      <div class="disp-ib mar-b-rg">
        <input type="button" class="o_confirm-no btn-primary type-rg pad-x-md" value="No" />
      </div>
    </div>
  </div>
</div>


<script type="text/javascript">
  $(document).on("modal-signup-open", function() {
    var pageCtxt = pageCategory();
    if      ("wsj"   == pageCtxt) { $("#signup_wsj"  ).prop("checked", true); }
    else if ("read"  == pageCtxt) { $("#signup_manga").prop("checked", true); }
    else if ("watch" == pageCtxt) { $("#signup_anime").prop("checked", true); }
  });
</script>

<div id="modal-signup" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg" data-modal-state="off">
  <a href="#modal-signup" data-modal-btn class="modal-close">
    <i class="icon-close"></i>
  </a>
  <div class="modal-g-lg shift mar-b-lg o_modal-header">
    <h2 class="type-md weight-bold style-caps line-solid">Sign up for a new VIZ account</h2>
    <div class="color-mid-gray type-rg mar-t-rg">
      <p>Already have a VIZ account? <a href="#modal-login" data-modal-btn>Log in</a>.</p>
    </div>
    <div id="create_account_error" class="feedback type-sm mar-t-rg disp-n"></div>
  </div>
  <form class="clearfix clear-b">

    <div class="modal-field type-rg o_signup-login">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>
          Username
          <i data-tooltip aria-haspopup="true" title="Your username is public." class="icon-tool-tip tooltip-target"></i>
        </label>
      </div>
      <div class="modal-g-lg">
        <input id="login" name="login" type="text"></input>
        <div id="login-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-field type-rg o_signup-email">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>E-mail</label>
      </div>
      <div class="modal-g-lg">
        <input type="text" name="email" id="new_email"></input>
        <div id="email-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-field type-rg o_signup-password">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>Password</label>
       </div>
      <div class="modal-g-lg">
        <input type="password" name="pass" id="pass" autocomplete="new-password"></input>
        <div id="password-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-field type-rg o_signup-birthday">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>
          Birthday
          <i data-tooltip aria-haspopup="true" title="To sign up, you must be 13 or older. Other people won’t see your birthday." class="icon-tool-tip tooltip-target"></i>
        </label>
      </div>
      <div class="modal-g-lg">
        <div class="select-wrapper disp-bl disp-ib--sm mar-b-rg mar-r-rg--sm">
          <select id="signup_date_month" name="date[month]" class="expand">
<option value="">Month</option>
<option value="1">Jan</option>
<option value="2">Feb</option>
<option value="3">Mar</option>
<option value="4">Apr</option>
<option value="5">May</option>
<option value="6">Jun</option>
<option value="7">Jul</option>
<option value="8">Aug</option>
<option value="9">Sep</option>
<option value="10">Oct</option>
<option value="11">Nov</option>
<option value="12">Dec</option>
</select>

        </div>
        <div class="select-wrapper disp-bl disp-ib--sm mar-b-rg mar-r-rg--sm">
          <select id="signup_date_day" name="date[day]" class="expand">
<option value="">Day</option>
<option value="1">1</option>
<option value="2">2</option>
<option value="3">3</option>
<option value="4">4</option>
<option value="5">5</option>
<option value="6">6</option>
<option value="7">7</option>
<option value="8">8</option>
<option value="9">9</option>
<option value="10">10</option>
<option value="11">11</option>
<option value="12">12</option>
<option value="13">13</option>
<option value="14">14</option>
<option value="15">15</option>
<option value="16">16</option>
<option value="17">17</option>
<option value="18">18</option>
<option value="19">19</option>
<option value="20">20</option>
<option value="21">21</option>
<option value="22">22</option>
<option value="23">23</option>
<option value="24">24</option>
<option value="25">25</option>
<option value="26">26</option>
<option value="27">27</option>
<option value="28">28</option>
<option value="29">29</option>
<option value="30">30</option>
<option value="31">31</option>
</select>

        </div>
        <div class="select-wrapper disp-bl disp-ib--sm mar-b-rg mar-r-rg--sm">
           <select id="signup_date_year" name="date[year]" class="expand">
<option value="">Year</option>
<option value="2020">2020</option>
<option value="2019">2019</option>
<option value="2018">2018</option>
<option value="2017">2017</option>
<option value="2016">2016</option>
<option value="2015">2015</option>
<option value="2014">2014</option>
<option value="2013">2013</option>
<option value="2012">2012</option>
<option value="2011">2011</option>
<option value="2010">2010</option>
<option value="2009">2009</option>
<option value="2008">2008</option>
<option value="2007">2007</option>
<option value="2006">2006</option>
<option value="2005">2005</option>
<option value="2004">2004</option>
<option value="2003">2003</option>
<option value="2002">2002</option>
<option value="2001">2001</option>
<option value="2000">2000</option>
<option value="1999">1999</option>
<option value="1998">1998</option>
<option value="1997">1997</option>
<option value="1996">1996</option>
<option value="1995">1995</option>
<option value="1994">1994</option>
<option value="1993">1993</option>
<option value="1992">1992</option>
<option value="1991">1991</option>
<option value="1990">1990</option>
<option value="1989">1989</option>
<option value="1988">1988</option>
<option value="1987">1987</option>
<option value="1986">1986</option>
<option value="1985">1985</option>
<option value="1984">1984</option>
<option value="1983">1983</option>
<option value="1982">1982</option>
<option value="1981">1981</option>
<option value="1980">1980</option>
<option value="1979">1979</option>
<option value="1978">1978</option>
<option value="1977">1977</option>
<option value="1976">1976</option>
<option value="1975">1975</option>
<option value="1974">1974</option>
<option value="1973">1973</option>
<option value="1972">1972</option>
<option value="1971">1971</option>
<option value="1970">1970</option>
<option value="1969">1969</option>
<option value="1968">1968</option>
<option value="1967">1967</option>
<option value="1966">1966</option>
<option value="1965">1965</option>
<option value="1964">1964</option>
<option value="1963">1963</option>
<option value="1962">1962</option>
<option value="1961">1961</option>
<option value="1960">1960</option>
<option value="1959">1959</option>
<option value="1958">1958</option>
<option value="1957">1957</option>
<option value="1956">1956</option>
<option value="1955">1955</option>
<option value="1954">1954</option>
<option value="1953">1953</option>
<option value="1952">1952</option>
<option value="1951">1951</option>
<option value="1950">1950</option>
<option value="1949">1949</option>
<option value="1948">1948</option>
<option value="1947">1947</option>
<option value="1946">1946</option>
<option value="1945">1945</option>
<option value="1944">1944</option>
<option value="1943">1943</option>
<option value="1942">1942</option>
<option value="1941">1941</option>
<option value="1940">1940</option>
<option value="1939">1939</option>
<option value="1938">1938</option>
<option value="1937">1937</option>
<option value="1936">1936</option>
<option value="1935">1935</option>
<option value="1934">1934</option>
<option value="1933">1933</option>
<option value="1932">1932</option>
<option value="1931">1931</option>
<option value="1930">1930</option>
<option value="1929">1929</option>
<option value="1928">1928</option>
<option value="1927">1927</option>
<option value="1926">1926</option>
<option value="1925">1925</option>
<option value="1924">1924</option>
<option value="1923">1923</option>
<option value="1922">1922</option>
<option value="1921">1921</option>
<option value="1920">1920</option>
</select>

        </div>
        <div id="birthday-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-field type-rg o_signup-interests">
      <div class="modal-g-sm type-right--lg mar-b-sm">
        <label>
          Interests
        </label>
      </div>
      <div class="modal-g-lg flex--sm mar-b-sm type-sm type-rg--lg">
        <label style="white-space:nowrap" class="mar-r-md">
          <input type="checkbox" name="signup_anime" id="signup_anime" value="1" class="pad-r-sm"> Anime
        </label>
        <label style="white-space:nowrap" class="mar-r-md">
          <input type="checkbox" name="signup_manga" id="signup_manga" value="1" class="pad-r-sm"> Manga
        </label>
        <label style="white-space:nowrap">
          <input type="checkbox" name="signup_wsj" id="signup_wsj" value="1" class="pad-r-sm"> Shonen Jump
        </label>
      </div>
    </div>

    <div class="modal-field type-rg o_signup-captcha">
      <div class="modal-g-lg shift">
        <div id="captcha"></div>
        <div id="captcha-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-field type-rg o_signup-remember">
      <div class="modal-g-lg shift">
        <label class="disp-ib mar-0--lg">
          <input type="checkbox" class="v-mid mar-r-sm" name="signup_rem_user" id="signup_rem_user">
          <span class="color-mid-gray">Remember me</span>
        </label>
      </div>
    </div>

    <div class="modal-actions mar-b-rg o_signup-submit">
      <div class="modal-g-lg shift">
        <input type="button" onclick="javascript:createAccount()" class="btn-primary type-rg pad-x-xl" value="Sign up" />
        <div class="mar-t-md type-sm">
          <p>By signing up, I agree to VIZ's <a target="signupwin" href="/terms">Terms of Service</a> and <a target="signupwin" href="/privacy">Privacy Policy</a>.</p>
        </div>
      </div>
    </div>

  </form>
</div>

<script type="text/javascript">
  var recaptcha_response;
  var captcha_response = function(resp) { recaptcha_response = resp; }
  var feedback_recaptcha_response;
  var feedback_captcha_response = function(resp) { feedback_recaptcha_response = resp; }

  var recaptchaCallback = function() {
    //console.log('recaptchaCallback called');
    grecaptcha.render('captcha', { 
      "sitekey"  : "6LcOjgITAAAAADBlwgh-UTh4-2Hmh1LNWQE-Or9l",
      "callback" : captcha_response
    });
    grecaptcha.render('feedback-captcha', {
      "sitekey"  : "6Ldn5xoTAAAAAClzsqqpxV4ki8tGc9FnvZy53TCA",
      "callback" : feedback_captcha_response
    });
  }
</script>
<script src="https://www.google.com/recaptcha/api.js?onload=recaptchaCallback&render=explicit" async defer></script>

<div id="modal-login" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg" data-modal-state="off">
  <a href="#modal-login" data-modal-btn class="modal-close">
    <i class="icon-close"></i>
  </a>
  <div class="modal-g-lg shift mar-b-lg o_modal-header">
    <h2 class="type-md weight-bold style-caps line-solid">Log in to VIZ</h2>
    <div class="color-mid-gray type-rg mar-t-rg">
      <p>Don't have an account? <a href="#modal-signup" data-modal-btn data-event='{"category":"Account","action":"Begins Sign-up Process","label":"title"}'>Sign up</a>.</p>
    </div>
  </div>
  <div id="sign_in_feedback" class="feedback modal-g-lg shift mar-b-lg disp-n"></div>
  <form class="clearfix clear-b">

    <div class="modal-field type-rg o_login-account">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>
          Account
        </label>
      </div>
      <div class="modal-g-lg">
        <input type="text" name="try_login" id="try_login" onkeydown="if (event.keyCode == 13){$('.o_login-submit input').click();return false;}" placeholder="E-mail or username"></input>
      </div>
    </div>

    <div class="modal-field type-rg o_login-password">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>
          Password
        </label>
       </div>
      <div class="modal-g-lg">
        <input type="password" name="try_pass" id="try_pass" onkeydown="if (event.keyCode == 13){$('.o_login-submit input').click();return false;}"></input>
      </div>
    </div>

    <div class="modal-field type-rg o_login-remember">
      <div class="modal-g-lg shift">
         <label class="disp-ib mar-b-md mar-0--lg">
           <input type="checkbox" class="v-mid mar-r-sm" name="rem_user" id="rem_user">
           <span class="color-mid-gray">Remember me</span>
         </label>
         <a href="#modal-resetpass" data-modal-btn class="color-red hover-dark-red disp-bl float-r--lg">Forgot password?</a>
      </div>
    </div>

    <div class="modal-actions mar-b-rg o_login-submit">
      <div class="modal-g-lg shift">
        <input type="button" class="btn-primary type-rg pad-x-xl" value="Log in" onclick="javascript:tryLogin()" />
      </div>
    </div>

  </form>
</div>

<div id="modal-resetpass" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg" data-modal-state="off">
  <a href="#modal-resetpass" data-modal-btn class="modal-close">
    <i class="icon-close"></i>
  </a>
  <div id="hide_on_success">
    <div class="modal-g-lg shift mar-b-lg">
      <h2 class="type-md weight-bold style-caps line-solid">Reset Password</h2>
      <div class="type-rg mar-t-md"><p>Enter the e-mail address associated with your account and we'll email you a link to reset your password.</p></div>
    </div>

    <form class="clearfix clear-b">

      <div class="modal-field type-rg">
        <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
          <label>E-mail</label>
        </div>
        <div class="modal-g-lg">
          <input placeholder="Enter your e-mail address" type="text" id="forgot_pass_email" name="forgot_pass_email"></input>
        </div>
      </div>
      <div class="modal-actions">
        <div class="modal-g-lg shift mar-b-lg">
          <input id="btn_forgot_pass" type="button" class="btn-primary type-rg pad-x-xl" value="Send reset link" onClick="javascript:send_forgot_pass()" />
        </div>
      </div>

    </form>
  </div>

  <div id="messages" class="modal-g-lg shift mar-b-lg">
    <h3 id="msg_error"    class="type-md weight-bold line-solid color-red disp-n"></h3>
    <h3 id="msg_loading"  class="type-md weight-bold line-solid disp-n">Requesting Password Reset Instructions...</h3>
    <div id="msg_success" class="disp-n">
      <h3 class="type-md weight-bold line-solid">You have been sent an email with instructions on how to reset your password.</h3>
      <h4 class="type-rg bg-yellow weight-bold line-solid pad-md mar-t-md">NOTE: If you don't receive a message right away, please be patient. At times some customers have experienced delays of several minutes.</h4>
    </div>
  </div>

</div>

<script type="text/javascript">
  $(document).on("modal-newsletter-open", function() {
    var pageCtxt = pageCategory();
    if      ("wsj"   == pageCtxt) { $("#newsletter_wsj"  ).prop("checked", true); }
    else if ("read"  == pageCtxt) { $("#newsletter_manga").prop("checked", true); }
    else if ("watch" == pageCtxt) { $("#newsletter_anime").prop("checked", true); }
    else {
      $("#newsletter_wsj"  ).prop("checked", true);
      $("#newsletter_manga").prop("checked", true);
      $("#newsletter_anime").prop("checked", true);
    }
  });
</script>

<div id="modal-newsletter" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg" data-modal-state="off">
  <a href="#modal-newsletter" data-modal-btn class="modal-close">
    <i class="icon-close"></i>
  </a>
  <div class="modal-g-lg shift mar-b-lg">
    <h2 class="type-md weight-bold style-caps line-solid">Subscribe to the VIZ Newsletter</h2>
  </div>
  <form class="clearfix clear-b" onsubmit="javascript:newsletterSignup(); return false;">
    <div class="modal-field type-rg">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>E-mail</label>
      </div>
      <div class="modal-g-lg">
        <input type="text" name="newsletter_email" id="newsletter_email"></input>
        <div id="newsletter-email-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-field type-rg">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>
          First Name
        </label>
      </div>
      <div class="modal-g-lg">
        <input id="first_name" name="newsletter_first_name" type="text"></input>
        <div id="newsletter-first-name-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-field type-rg">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>
          Last Name
        </label>
      </div>
      <div class="modal-g-lg">
        <input id="last_name" name="newsletter_last_name" type="text"></input>
        <div id="newsletter-last-name-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-field type-rg">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>
          Birthday
          <i data-tooltip aria-haspopup="true" title="To sign up, you must be 13 or older. Other people won’t see your birthday." class="icon-tool-tip tooltip-target"></i>
        </label>
      </div>
      <div class="modal-g-lg">
        <div class="select-wrapper disp-bl disp-ib--sm mar-b-rg mar-r-rg--sm">
          <select id="newsletter_date_month" name="newsletter_date[month]" class="expand">
<option value="">Month</option>
<option value="1">Jan</option>
<option value="2">Feb</option>
<option value="3">Mar</option>
<option value="4">Apr</option>
<option value="5">May</option>
<option value="6">Jun</option>
<option value="7">Jul</option>
<option value="8">Aug</option>
<option value="9">Sep</option>
<option value="10">Oct</option>
<option value="11">Nov</option>
<option value="12">Dec</option>
</select>

        </div>
        <div class="select-wrapper disp-bl disp-ib--sm mar-b-rg mar-r-rg--sm">
          <select id="newsletter_date_day" name="newsletter_date[day]" class="expand">
<option value="">Day</option>
<option value="1">1</option>
<option value="2">2</option>
<option value="3">3</option>
<option value="4">4</option>
<option value="5">5</option>
<option value="6">6</option>
<option value="7">7</option>
<option value="8">8</option>
<option value="9">9</option>
<option value="10">10</option>
<option value="11">11</option>
<option value="12">12</option>
<option value="13">13</option>
<option value="14">14</option>
<option value="15">15</option>
<option value="16">16</option>
<option value="17">17</option>
<option value="18">18</option>
<option value="19">19</option>
<option value="20">20</option>
<option value="21">21</option>
<option value="22">22</option>
<option value="23">23</option>
<option value="24">24</option>
<option value="25">25</option>
<option value="26">26</option>
<option value="27">27</option>
<option value="28">28</option>
<option value="29">29</option>
<option value="30">30</option>
<option value="31">31</option>
</select>

        </div>
        <div class="select-wrapper disp-bl disp-ib--sm mar-b-rg mar-r-rg--sm">
           <select id="newsletter_date_year" name="newsletter_date[year]" class="expand">
<option value="">Year</option>
<option value="1920">1920</option>
<option value="1921">1921</option>
<option value="1922">1922</option>
<option value="1923">1923</option>
<option value="1924">1924</option>
<option value="1925">1925</option>
<option value="1926">1926</option>
<option value="1927">1927</option>
<option value="1928">1928</option>
<option value="1929">1929</option>
<option value="1930">1930</option>
<option value="1931">1931</option>
<option value="1932">1932</option>
<option value="1933">1933</option>
<option value="1934">1934</option>
<option value="1935">1935</option>
<option value="1936">1936</option>
<option value="1937">1937</option>
<option value="1938">1938</option>
<option value="1939">1939</option>
<option value="1940">1940</option>
<option value="1941">1941</option>
<option value="1942">1942</option>
<option value="1943">1943</option>
<option value="1944">1944</option>
<option value="1945">1945</option>
<option value="1946">1946</option>
<option value="1947">1947</option>
<option value="1948">1948</option>
<option value="1949">1949</option>
<option value="1950">1950</option>
<option value="1951">1951</option>
<option value="1952">1952</option>
<option value="1953">1953</option>
<option value="1954">1954</option>
<option value="1955">1955</option>
<option value="1956">1956</option>
<option value="1957">1957</option>
<option value="1958">1958</option>
<option value="1959">1959</option>
<option value="1960">1960</option>
<option value="1961">1961</option>
<option value="1962">1962</option>
<option value="1963">1963</option>
<option value="1964">1964</option>
<option value="1965">1965</option>
<option value="1966">1966</option>
<option value="1967">1967</option>
<option value="1968">1968</option>
<option value="1969">1969</option>
<option value="1970">1970</option>
<option value="1971">1971</option>
<option value="1972">1972</option>
<option value="1973">1973</option>
<option value="1974">1974</option>
<option value="1975">1975</option>
<option value="1976">1976</option>
<option value="1977">1977</option>
<option value="1978">1978</option>
<option value="1979">1979</option>
<option value="1980">1980</option>
<option value="1981">1981</option>
<option value="1982">1982</option>
<option value="1983">1983</option>
<option value="1984">1984</option>
<option value="1985">1985</option>
<option value="1986">1986</option>
<option value="1987">1987</option>
<option value="1988">1988</option>
<option value="1989">1989</option>
<option value="1990">1990</option>
<option value="1991">1991</option>
<option value="1992">1992</option>
<option value="1993">1993</option>
<option value="1994">1994</option>
<option value="1995">1995</option>
<option value="1996">1996</option>
<option value="1997">1997</option>
<option value="1998">1998</option>
<option value="1999">1999</option>
<option value="2000">2000</option>
<option value="2001">2001</option>
<option value="2002">2002</option>
<option value="2003">2003</option>
<option value="2004">2004</option>
<option value="2005">2005</option>
<option value="2006">2006</option>
<option value="2007">2007</option>
<option value="2008">2008</option>
<option value="2009">2009</option>
<option value="2010">2010</option>
<option value="2011">2011</option>
<option value="2012">2012</option>
<option value="2013">2013</option>
<option value="2014">2014</option>
<option value="2015">2015</option>
<option value="2016">2016</option>
<option value="2017">2017</option>
<option value="2018">2018</option>
<option value="2019">2019</option>
<option value="2020">2020</option>
</select>

        </div>
        <div id="newsletter-birthday-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-field type-rg">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>
          Newsletters
        </label>
      </div>
      <div class="modal-g-lg type-sm type-rg--lg">
        <div class="flex--sm mar-y-md--lg mar-b-sm">
          <label style="white-space:nowrap" class="mar-r-md">
            <input type="checkbox" name="newsletter_anime" id="newsletter_anime" value="1" class="pad-r-sm"> Anime
          </label>
          <label style="white-space:nowrap" class="mar-r-md">
            <input type="checkbox" name="newsletter_manga" id="newsletter_manga" value="1" class="pad-r-sm"> Manga
          </label>
          <label style="white-space:nowrap">
            <input type="checkbox" name="newsletter_wsj" id="newsletter_wsj" value="1" class="pad-r-sm"> Shonen Jump
          </label>
        </div>
        <div id="newsletter-interests-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>

    <div class="modal-actions">
      <div class="modal-g-lg shift">
        <button type="submit" class="btn-primary type-rg pad-x-xl">Subscribe</button>
        <div class="mar-t-md type-sm">
          <p>By subscribing, I agree to VIZ's <a href="/terms">Terms of Service</a> and <a href="/privacy">Privacy Policy</a>.</p>
        </div>
      </div>
    </div>

  </form>
</div>


<div id="modal-feedback" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg" data-modal-state="off">
  <a href="#modal-feedback" data-modal-btn class="modal-close">
    <i class="icon-close"></i>
  </a>
  <div class="modal-g-lg shift mar-b-lg">
    <h2 class="type-md weight-bold style-caps line-solid">Feedback</h2>
    <div class="type-rg mar-t-md"><p>Please submit a suggestion, comment or question - we would love to hear from you!</p></div>
  </div>
  <form id="feedback_form" class="clearfix clear-b">
    <div class="modal-field type-rg">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>E-mail <span class="type-sm">(optional)</span></label>
      </div>
      <div class="modal-g-lg">
        <input type="text" name="feedback_email" id="feedback_email"></input>
        <div id="feedback-email-feedback" class="feedback type-sm mar-t-rg disp-n"></div>
      </div>
    </div>
    <div class="modal-field type-rg">
      <div class="modal-g-sm type-right--lg mar-y-md--lg mar-b-sm">
        <label>
          Comments
        </label>
      </div>
      <div class="modal-g-lg">
        <textarea rows=4 id="feedback_comments" name="feedback_comments"></textarea>
        <div id="feedback-comments-feedback" class="feedback type-sm mar-t-rg disp-n color-red"></div>
      </div>
    </div>
    <div class="modal-field type-rg">
      <div class="modal-g-lg shift">
        <div id="feedback-captcha"></div>
        <div id="feedback-captcha-feedback" class="feedback type-sm mar-t-rg disp-n color-red"></div>
      </div>
    </div>
    <div class="modal-actions mar-b-lg">
      <div class="modal-g-lg shift">
        <input type="submit" class="btn-primary type-rg pad-x-xl" value="Send Feedback" />
      </div>
    </div>
  </form>
</div>
<script type="text/javascript">
  $("#feedback_form").submit(function(){
    var isWsjPage = 1;
    var errors    = false;

    // REM the email field is optional

    if ($("#feedback_comments").val() == "") {
      validate.feedback_msg( $("#feedback-comments-feedback"), 'Please enter a message to send.', true );
      errors = true;
    } 
    if (feedback_recaptcha_response) {
    
    } else {
      validate.feedback_msg( $("#feedback-captcha-feedback"), 'You must complete the captcha verification above', true );
      errors = true;
    }

    if (errors === true) {
      // No need to scroll since its a modal
    } else {
      var jqxhr = $.ajax({
        type: "POST",
        url:  "/company/feedback_send",
        data: {
          source:   "feedback",
          email:    $("#feedback_email").val(),
          comments: $("#feedback_comments").val(),
          is_wsj:   isWsjPage,
          recaptcha_response: feedback_recaptcha_response
        },
        dataType: "json"
      });
      jqxhr.done(function(data, textStatus, xhr) { 
        if (data.sent == 1) {
          $("#feedback_email, #feedback_comments").val("");

          Modals.toggle("#modal-thanks");
          $("#modal-thanks h2").html('Thank you!');
          $("#modal-thanks #thanks-left label").html('<div id="thanks-small-note" class="mar-t-md type-sm mar-b-lg">Your comments have been received.</div><a class="flex-width-1 btn-primary pad-x-sm pad-x-md--sm" href="javascript:Modals.toggle(\'#modal-thanks\')">Close</a>');

        } else {
          validate.feedback_msg( $("#feedback-captcha-feedback"), data.error, true );
        }
      });
      jqxhr.fail(function(xhr, textStatus, error) {
        showErr(xhr.statusText, JSON.stringify(error));
      });
    }
    return false; // stop default behavior
  });
</script>

<div id="modal-thanks" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg" data-modal-state="off">
  <a href="#modal-thanks" data-modal-btn class="modal-close">
    <i class="icon-close"></i>
  </a>
  <div class="mar-b-lg">
    <h2 class="type-md weight-bold style-caps line-solid"></h2>
  </div>
  <div class="modal-field type-rg">
    <div id="thanks-left" class="mar-y-md--lg mar-b-sm">
      <label></label>
    </div>
  </div>
</div>

<div id="modal-gdpr" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg" data-modal-state="off">
  <div class="modal-g-lg shift mar-b-lg">
    <h2 class="o_err-title type-md weight-bold style-caps line-solid">Note to our visitors in the EU</h2>
    <div class="o_err-msg type-rg mar-t-md">
This website uses cookies and tracking technologies to assist with your navigation, analyze use of our website and products and services, assist with your registration and login, and to assist with our marketing efforts. You may block cookies via standard web-browser settings, but this site may not function correctly without cookies.
    </div>
  </div>
  <div class="modal-actions">
    <div class="modal-g-lg shift">
      <input type="button" class="btn-primary type-rg pad-x-xl modal-close" value="OK" onclick="Modals.close(); setCookie('gdpr_seen', 1, 365);" />
    </div>
  </div>
</div>




        <div id="modal-sj-join" class="modal pad-md pad-b-lg pad-lg--md pad-xl--lg o_internal-promo-trackable" data-modal-state="off">
    <a href="#modal-sj-join" data-modal-btn class="modal-close"><i class="icon-close"></i></a>
    <div class="modal-field type-rg">
      <div class="mar-y-md--lg mar-b-sm">
        <label>
          <div class="pad-x-md pad-x-lg--md">
            <div class="subscribe_button_div" 
     id="sj_122"
     btn_type="sj"
     btn_item_type="s"
     btn_item_id="122">
    
<div class="clearfix type-rg type-md--md">

  <div id="membership_header_122" class="line-tight mar-b-md type-md type-lg--md">
    <p><strong>Join Shonen Jump!</strong></p>
  </div>

    <div id="membership_text_122" class="clear-b text-spacing line-tight color-mid-gray mar-b-md">
      <p>Become a member now and unlock the Shonen Jump digital vault of 10,000+ manga chapters!</p>
    </div>

  <div class="mar-b-md">
      <a href="/subscribe" class="o_subscribe pad-x-xl pad-x-xxl--md type-rg btn-primary">Learn more</a>
  </div>
</div>


</div>


            <p class="o_sj-nologin line-tight type-rg type-md--md pad-t-md pad-b-sm">Already have a Shonen Jump membership? <a href="#modal-login" data-modal-btn>Log in</a> now.</p>
          </div>
        </label>
      </div>
    </div>
    <script type="text/javascript">
      var wsjModalPromoId  = "";
      var wsjModalSource   = "";
      var wsjModalPosition = "Read My Hero Academia Manga Free - Official Shonen Jump From Japan";

      $(document).on('modal-sj-join-open', function() {
        $("a.o_subscribe", this).on('click', function(e) {
          e.preventDefault();

          setCookieForMinutes('postsublink',  Modals.context.targetUrl,   30);
          setCookieForMinutes('postsubtitle', Modals.context.targetTitle, 30);

          ga('ec:addPromo', {
            'id': wsjModalPromoId,
            'name': 'WSJ Subscribe Modal',
            'creative': wsjModalSource,
            'position': wsjModalPosition
          });
          ga('ec:setAction', 'promo_click');
          ga('send', 'event', 'Internal Promotions', 'click', 'WSJ Subscribe Modal', {
            hitCallback: function() {
              document.location = '/subscribe';
            }
          });
          Tracking.sendEvent({"category":"WSJ Modal Subscribe Learn More Button Clicked","action":wsjModalSource,"label":wsjModalPosition});


          return false;
        });
      });
    </script>
  </div>



      <section id="newsletter-footer" class="bg-lighter-gray">
  <div class="row flex--lg flex-items-center pad-y-lg pos-r">
    <div class="g-2--lg mar-b-lg mar-b-0--lg pos-a--lg b-0 disp-n--nl">
      <img class="disp-bl" src="https://dw9to29mmj727.cloudfront.net/misc/newsletter-naruto3.png" />
    </div>
    <div class="g-6--lg g-shift-2--lg mar-b-md mar-b-0--lg">
      <h3 class="type-md type-lg--lg line-solid mar-b-rg">Get the latest manga &amp; anime news!</h3>
      <p class="type-sm type-rg--lg line-caption">You&rsquo;ll never miss a beat when you subscribe to our newsletter.</p>
    </div>
    <form class="g-4--lg flex flex--stretch type-sm type-rg--sm" onsubmit="raiseNewsletterSignupDialog($('#newsletter_footer_email').val()); $('#newsletter_footer_email').val(''); return false;">
      <input type="text" class="flex-width-3" placeholder="Enter your email address" id="newsletter_footer_email">
      <button type="submit" class="btn-primary flex-width-1 btn-primary pad-x-sm pad-x-md--sm" id="newsletter_footer_signup">Sign Up</button>
    </form>
  </div>
</section>


      <footer id="global-footer" class="o_site-footer bg-off-black">
  <div class="row flex">
    <div class="o_logo-bottom bg-black flex g-3--lg g-omega--lg">
      <a href="/" class="o_logo-img color-white type-md weight-bold">
        <img alt="VIZ" src="https://assets.viz.com/assets/logo@2x-b76f649f933ea15f45147ff5445a2501c85c7f863ba0aba5ea7bec93c3272cc6.png" />
      </a>
    </div>
  </div>
  <div class="row pad-y-xl">
    <div class="g-6 g-6--md mar-b-lg type-md style-caps weight-bold">
      <ul class="o_footer-primary-nav-col">
        <li class="o_footer-primary-nav-item"><a class="color-mid-gray hover-red" href="/read">Read</a></li>
        <li class="o_footer-primary-nav-item"><a class="color-mid-gray hover-red" href="/watch">Watch</a></li>
        <li class="o_footer-primary-nav-item"><a class="color-mid-gray hover-red" href="/shonenjump">Shonen Jump</a></li>
      </ul>
      <ul class="o_footer-primary-nav-col">
        <li class="o_footer-primary-nav-item"><a class="color-mid-gray hover-red" href="/community">Community</a></li>
        <li class="o_footer-primary-nav-item"><a class="color-mid-gray hover-red" href="/calendar">Calendar</a></li>
      </ul>
    </div>
    <div class="g-6 g-6--md g-omega--md type-rg">
      <ul class="o_footer-secondary-nav-col">
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/company-about">About VIZ</a></li>
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/company-contact">Contact VIZ</a></li>
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/company-faq">FAQ</a></li>
          <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/gifts/redeem">Redeem Gift</a></li>
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/events">Events</a></li>
      </ul>
      <ul class="o_footer-secondary-nav-col">
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/apps">Apps</a></li>
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/ratings">Ratings</a></li>
        <li class="o_footer-secondary-nav-item">
          <a class="color-mid-gray hover-red" href="/company-jobs">Jobs</a> <span class="color-mid-gray">/</span>
          <a class="color-mid-gray hover-red" href="/company-internships">Internships</a>
        </li>
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/news/newsroom">Press Releases</a></li>
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/copyrights">Copyrights</a></li>
      </ul>
      <ul class="o_footer-secondary-nav-col end">
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/privacy">Privacy Policy</a></li>
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="/terms">Terms of Use</a></li>
        <li class="o_footer-secondary-nav-item">&nbsp;</li>
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="https://twitter.com/VIZMedia" target="viz_twitter">Twitter</a></li>
        <li class="o_footer-secondary-nav-item"><a class="color-mid-gray hover-red" href="https://www.facebook.com/OfficialVIZMedia" target="viz_facebook">Facebook</a></li>
      </ul>
    </div>
  </div>
  <div id="footer_account" class="row"></div>
</footer>



    <div id="overlay"      data-overlay-state="off" class="o_overlay"></div>
    <div id="overlay_wait" data-overlay-state="off" class="o_overlay-wait"></div>
    <!-- Twitter universal website tag code -->
<script src="//platform.twitter.com/oct.js" type="text/javascript" async defer></script>
<script type="text/javascript">
setTimeout(function(){twttr.conversion.trackPid('nuvyy', { tw_sale_amount: 0, tw_order_quantity: 0 });}, 200);
</script>
<noscript>
<img height="1" width="1" style="display:none;" alt="" src="https://analytics.twitter.com/i/adsct?txn_id=nuvyy&p_id=Twitter&tw_sale_amount=0&tw_order_quantity=0" />
<img height="1" width="1" style="display:none;" alt="" src="//t.co/i/adsct?txn_id=nuvyy&p_id=Twitter&tw_sale_amount=0&tw_order_quantity=0" />
</noscript>
<!-- End Twitter universal website tag code -->

      <!-- Twitter universal website tag code -->
<script>
!function(e,t,n,s,u,a){e.twq||(s=e.twq=function(){s.exe?s.exe.apply(s,arguments):s.queue.push(arguments);
},s.version='1.1',s.queue=[],u=t.createElement(n),u.async=!0,u.src='//static.ads-twitter.com/uwt.js',
a=t.getElementsByTagName(n)[0],a.parentNode.insertBefore(u,a))}(window,document,'script');
// Insert Twitter Pixel ID and Standard Event data below
twq('init','o08y8');
twq('track','PageView');
</script>
<!-- End Twitter universal website tag code -->
  </body>
</html>
