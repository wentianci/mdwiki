# VXDIAG WiKi

[首页](index.md)

<script type="text/javascript">
	var urls=window.location.href;
	urls=urls.replace('/zh/','/en/');
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

[![](../include/images/zh.png) 简体中文 ]()

  * [![](../include/images/en.png) English](javascript:window.location.href=urls)


[设备使用指南]()

  * [VCX固件复位操作][]
  * [Vxmanager更新与使用说明][]
  * [云诊断使用说明][]
  * [快速开始指南][]
  * [VXManager安装][]
  * [VXDIAG设备连接][]
  * [设备授权管理][]
  * [设备固件升级][]
  * [OEM诊断驱动安装][]

[诊断软件安装]()

  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/subaruselectmonitor.png" />Subaru](pages/subaru/subaruselectmonitor_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/toyota-techstream.png" />Techstream](pages/toyota/techstream_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/ford-ids.png" />Ford IDS](pages/ford/ids/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/odis.png" />ODIS](pages/volkswagen/odis_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/diagsystem.png" />HONDA HDS](pages/hds/hds_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/jlr-sdd.png" />JLR SDD](pages/jlr/jlr_install/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/piwis-ii.png" />PIWIS-II](pages/piwisii/install/index.md)


[车辆诊断案例]()

  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/volvo.png" />沃尔沃](pages/volvo/index.md)
  * [<img style="margin:3px 10px 3px -10px;;height:30px;" src="../include/images/benz.png" />奔驰](pages/benz/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/bmw.png" />宝马](pages/bmw/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/honda.png" />本田](pages/hds/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/toyota.png" />丰田](pages/toyota/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/jlr.png" />路虎](pages/jlr/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/porsche.png" />保时捷](pages/piwisii/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/buick.png" />别克](pages/buick/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/ford.png" />福特](pages/ford/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/subaru.png" />斯巴鲁](pages/subaru/index.md)
  * [<img style="margin:3px 10px 3px -10px;height:30px;" src="../include/images/volkswagen.png" />大众](pages/volkswagen/index.md)
  
[资料下载](pages/download.md)


[gimmick:theme](united)

<!-- show a theme chooser in the menu bar : flatly cerulean -->
[gimmick:ThemeChooser](更换主题)

[VCX固件复位操作]:pages/vxmanager/firmwarereset/index.md "VCX固件复位操作"
[VXManager更新与使用说明]: pages/vxmanager/VXManagerUpdate.md	"VXManager更新与使用说明"
[云诊断使用说明]: pages/vxmanager/yun/index.md "云诊断使用说明"
[快速开始指南]: pages/vxmanager/guide.md "快速开始指南"
[VXManager安装]: pages/vxmanager/index.md "VXManager安装"
[VXDIAG设备连接]: pages/vxmanager/vxdiag_connect.md "VXDIAG设备连接"
[设备授权管理]: pages/vxmanager/license.md "设备授权管理"
[设备固件升级]: pages/vxmanager/firmware.md
[OEM诊断驱动安装]: pages/vxmanager/oem.md "OEM诊断驱动安装"






