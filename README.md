# Reverse-IP-API-collections
Collect the API for ip reverse

IP反查接口收集。
    
    1. yougetsignal接口
    http://domains.yougetsignal.com/domains.php（已下线）
	现阶段Github上ipreverse程序使用最多的API，暂时因为负载过大的原因下线。
	可以在主站 http://www.yougetsignal.com/tools/web-sites-on-web-server
	进行在线查询，另外可以以接近500美刀的价格购买它的数据库。
	   
    2. bing接口
	https://api.datamarket.azure.com/Bing/SearchWeb/v1/Web?Query=
	该接口现在直接通过 https://login.microsoftonline.com 上的
	Microsoft Azure服务订阅Reserved IP Address。
	注意，这里地区选择中国貌似无法注册服务。
	
    3. hackertarget接口
    http://api.hackertarget.com/reverseiplookup/?q={ip}
	无身份验证调用方便快捷的接口，但是不适合批查询，单IP每天只能查询100次

	4. domaintools接口
	http://reverseip.domaintools.com/search/
	批查询账户需要付费使用，在线接口查询导出需付费

	5. robtex接口
	https://robtex.p.mashape.com/reverse/?q={query}&m={max}
	https://freeapi.robtex.com
	网站有一部分API接口可以免费使用，但是IP反查接口需要在mashape上注册账号

	6. pagesinventory接口
	http://www.pagesinventory.com/ip/{ip}.html
	可以通过账号调用API

	7. sameip接口
	http://www.sameip.org/{ip}
	数据量较其他接口相比较少

	8. dnstrails接口
	http://research.dnstrails.com/tools/lookup.htm?ip={ip}&date={date}
	正如网站的名字，支持通过时间轨迹来查看IP反查结果

	9. dnsdb.io接口
	https://dnsdb.io/zh-cn/search?q={ip}
	国内的反查IP接口

	10. viewdns接口
	http://pro.viewdns.info/reverseip/?host={ip}&apikey={apikey}&output=json
	可以申请到免费API的查询接口，免费接口提供250条查询试用。可以根据国家域名付费

	（持续更新ing）
	
	
