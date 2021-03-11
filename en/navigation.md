# VXDIAG WiKi

[Home](index.md)

<script type="text/javascript">
	var urls=window.location.href;
	urls=urls.replace('/en/','/zh/');
	var checkURL=urls.replace('/#!','/');
	$.ajax({
  url: checkURL,
  type: 'GET',
  complete: function(response) {
   if(response.status == 200) {
   // alert('有效');
   } else {
   	var urlsLeng = urls.length;
   	var replaceWord = urls.indexOf("#!");
   	var replaceString = urls.substring(replaceWord,urlsLeng);
    urls=urls.replace(replaceString,'');
   }
  }
 });

</script>

<script type="text/javascript">
  var _paq = window._paq || [];
  /* tracker methods like "setCustomDimension" should be called before "trackPageView" */
  _paq.push(['trackPageView']);
  _paq.push(['enableLinkTracking']);
  (function() {
    var u="//192.168.0.154/matomo/";
    _paq.push(['setTrackerUrl', u+'matomo.php']);
    _paq.push(['setSiteId', '1']);
    var d=document, g=d.createElement('script'), s=d.getElementsByTagName('script')[0];
    g.type='text/javascript'; g.async=true; g.defer=true; g.src=u+'matomo.js'; s.parentNode.insertBefore(g,s);
  })();
</script>

[![](../include/images/en.png) English]()

  * [![](../include/images/zh.png) 简体中文](javascript:window.location.href=urls)


[Equipment Guide]()

  * [VCX Firmware Reset][]
  * [Cloud Diagnostics][]
  * [Quick Start][]
  * [VXManager Installation][]
  * [VXDIAG Device Connection][]
  * [License Management][]
  * [Firmware Upgrade][]
  * [OEM Driver Installation][]

[Software Installation]()


  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/hino.png" />HINO ](pages/hino/hino_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/insite.png" />INSITE ](pages/cummins/insite_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/cat-et.png" />CAT ET ](pages/cat/caterpillarelectronictechnician_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/subaruselectmonitor.png" />Subaru](pages/subaru/subaruselectmonitor_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/toyota-techstream.png" />Techstream](pages/toyota/techstream_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/ford-ids.png" />Ford IDS](pages/ford/ids/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/odis.png" />ODIS](pages/volkswagen/odis_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/diagsystem.png" />HONDA HDS](pages/hds/hds_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/jlr-sdd.png" />JLR SDD](pages/jlr/jlr_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/piwis-ii.png" />PIWIS-II](pages/piwisii/install/index.md)


[Vehicle Diagnostics]()

  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/bmw.png" />BMW](pages/bmw/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/benz.png" />Benz](pages/benz/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/volkswagen.png" />Volkswagen](pages/volkswagen/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/buick.png" />Buick](pages/buick/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/volvo.png" />VOLVO](pages/volvo/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/honda.png" />HONDA](pages/hds/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/toyota.png" />TOYOTA](pages/toyota/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/jlr.png" />LANDROVER](pages/jlr/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/porsche.png" />PORSCHE](pages/piwisii/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/ford.png" />FORD](pages/ford/index.md)
  



[gimmick:theme](united)

<!-- show a theme chooser in the menu bar : flatly cerulean -->
[gimmick:ThemeChooser](Change Theme)


[VCX Firmware Reset]: pages/vxmanager/firmwarereset/index.md "VCX Firmware Reset"
[Cloud Diagnostics]: pages/vxmanager/yun/index.md "Cloud Diagnostics"
[Quick Start]: pages/vxmanager/guide.md "Quick Start"
[VXManager Installation]: pages/vxmanager/index.md "VXManager Installation"
[VXDIAG Device Connection]: pages/vxmanager/vxdiag_connect.md "VXDIAG Device Connection"
[License Management]: pages/vxmanager/license.md "License Management"
[Firmware Upgrade]: pages/vxmanager/firmware.md "Firmware Upgrade"
[OEM Driver Installation]: pages/vxmanager/oem.md "OEM diagnostic driver installation"






