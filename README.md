# pingstr
PiNgStR is a software application by Warren Woodhouse for personal use only. For commerical use, please [CLICK HERE](https://warrenwoodhouse.blogspot.com/contact) to request permission.

If you like what you see and want to support me, please subscribe to my YouTube channel by [CLICKING HERE](https://youtube.com/user/warrenwoodhouse).

# about
PiNgStR started in 2007 as a way to make my website load faster. My website at the time was called 798 and it was on the now defunct web builder and blogging platform Piczo (defunct since 2012). My 798 blog is still going, check it out by [CLICKING HERE](https://warrenwoodhouse.blogspot.com/798).

As a page speed booster, PiNgStR works in the background by loading images, files, data, etc. on the fly, alongside talking to your computer, web browser and your local mobile mast/cellular tower and instructs them to load them in under a second or near to it. Very cool! 😁🤓

# install
Installation Instructions

> [!IMPORTANT]
> Before installing, let me know in advance if you intend to use PiNgStR for commerical use.
> [CLICK HERE](https://warrenwoodhouse.blogspot.com/contact) to get in touch.
> PiNgStR is intended to be for free personal use only and for commerical use upon request via the contact form.

1. Read the [Code](https://github.com/warrenwoodhouse/pingstr/blob/main/README.md#code)
2. Follow the instructions in the section titled Code on how to install the plugin on your website
3. Enjoy!

# code
```
<head>
<!-- PiNgStR -->
<!-- author: Warren Woodhouse -->
<!-- notes: Speeds up the loading process of a website -->
<!-- warrenwoodhouse.blogspot.com/pingstr -->
<-- CODE BEGINS -->
<script type="text/javascript">(function() { (function(){function c(a){this.t={};this.tick=function(a,c,b){var d=void 0!=b?b:(new Date).getTime();this.t[a]=[d,c];if(void 0==b)try{window.console.timeStamp("CSI/"+a)}catch(e){}};this.tick("start",null,a)}var a;window.performance&&(a=window.performance.timing);var h=a?new c(a.responseStart):new c;window.jstiming={Timer:c,load:h};if(a){var b=a.navigationStart,e=a.responseStart;0<b&&e>=b&&(window.jstiming.srt=e-b)}if(a){var d=window.jstiming.load;0<b&&e>=b&&(d.tick("_wtsrt",void 0,b),d.tick("wtsrt_",
"_wtsrt",e),d.tick("tbsd_","wtsrt_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),d&&0<b&&(d.tick("_tbnd",void 0,window.chrome.csi().startE),d.tick("tbnd_","_tbnd",b))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,d&&0<b&&(d.tick("_tbnd",void 0,window.external.startE),d.tick("tbnd_","_tbnd",b))),a&&(window.jstiming.pt=a)}catch(k){}})();window.tickAboveFold=function(c){var a=0;if(c.offsetParent){do a+=c.offsetTop;while(c=c.offsetParent)}c=a;750>=c&&window.jstiming.load.tick("aft")};var f=!1;function g(){f||(f=!0,window.jstiming.load.tick("firstScrollTime"))}window.addEventListener?window.addEventListener("scroll",g,!1):window.attachEvent("onscroll",g);
 })();</script>
<-- CODE ENDS -->
</head>
```

# updates
[CLICK HERE](https://github.com/warrenwoodhouse/pingstr/blob/main/RELEASE-NOTES.md) to read the Updates.

# support
> [!TIP]
> If you want to help out with correcting mistakes in issues oppended to the bug reports in PiNgStR, please [CLICK HERE](https://github.com/warrenwoodhouse/forums/labels/pingstr).

# license
[CLICK HERE](https://github.com/warrenwoodhouse/pingstr/blob/main/LICENSE.md) to read the License Agreement.

# copyright
&copy;2007-present Warren Woodhouse
