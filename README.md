# positioning

1.利用高德   AMap.Geolocation 插件来进行定位

   AMap.Geolocation整合了浏览器定位、精确IP定位、sdk辅助定位多种手段
   
   注：默认情况下，PC端优先使用精确IP定位，解决多数浏览器无法完成定位的现状，IP定位失败后使用浏览器定位；手机端优先使用浏览器定位，失败后使用IP定位；
   
2.key的值很关键，如果key无效的话，只能获取经纬度，具体地址的相关信息会获取失败
