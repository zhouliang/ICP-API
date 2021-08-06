ICP备案信息查询API接口  
采用管局官网备案接口，事实同步最新ICP备案数据
  
请求示例：https://check.lzfh.com/api/icp.php?domain=  
请求方式：get  
请求参数：domain=需查询的域名，可以包含http或二级  
返回示例：  
{  
	"icp": "粤B2-20090059-5",  
	"unitName": "深圳市腾讯计算机系统有限公司",  
	"natureName": "企业",  
	"msg": "查询成功",  
	"result": "1"  
}  
返回result为0则查询失败。  
  
小弟纯自学php，代码很搓，大神勿喷，咱只管能用就行！  
