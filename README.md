 
 ​###​ ​[​SagerNet​](https://github.com/SagerNet/SagerNet) 
 ​1.​ فایل ​`iran.dat`​ را از [​این صفحه​][link-release] دانلود کنید. 
 ​2.​ فایل را از طریق ​`Route -> Three dots -> Manage Route Assets`​  به کلاینت اضافه کنید. 
 ​<p align="center"> 
 ​  <img alt="sagernet" src="https://user-images.githubusercontent.com/24422125/123522689-1cd40580-d6d4-11eb-90c1-a0341927e283.jpg"> 
 ​</p> 
  
 ​3.​  از بخش  ​`Route -> Create Route`​ قوانین زیر را اضافه کنید:    
 ​</div>   
  
 ​-​ Block Ads: 
 ​  ​-​ domain: ​`geosite:category-ads-all` 
 ​  ​-​ outbound: ​`Block` 
 ​-​ Block Iran Ads: 
 ​  ​-​ domain: ​`ext:iran.dat:ads` 
 ​  ​-​ outbound: ​`Block` 
 ​-​ Bypass Iran .ir Domains: 
 ​  ​-​ domain: ​`regexp:.+\.ir$` 
 ​  ​-​ outbound: ​`Bypass` 
 ​-​ Bypass Iran non .ir Domains: 
 ​  ​-​ domain: ​`ext:iran.dat:other` 
 ​  ​-​ outbound: ​`Bypass` 
 ​-​ Bypass Iran geoip: 
 ​  ​-​ ip: ​`geoip:ir` 
 ​  ​-​ outbound: ​`Bypass` 
  
 ​<div dir=rtl>   
  
 ​>​ برای مشاهده‌ی اسکرین شات از قوانین بالا [اینجا کلیک کنید](https://imgur.com/a/SEq1Bvg). 
  
 ​4.​ اتصال خود را قطع و وصل کنید.
