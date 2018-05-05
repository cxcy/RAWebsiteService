# RAWebsiteService


## 接口
| Func| URL| Action| Body | 
|:-------| :----------------------------------------|:--------|:----------|
| 注册 | http://www.private-elves.xyz/account/signup/| Post | <br/>username:dv2</br> <br/>password:dv2</br> <br/>password_confirm:dv2</br> <br/>email:dv2@dv2.com</br> |
| 登录 | http://www.private-elves.xyz/account/login/	 | Post|<br/>username:dv1</br> <br/>password:dv1</br> |
| 退出 | http://www.private-elves.xyz/account/logout/ | Post |  |
| 交易账户设置 | http://www.private-elves.xyz/trade/setting/config| Get |  |
| 资金查询 | http://www.private-elves.xyz/trade/query/cash |  |
| 查询资产 | http://www.private-elves.xyz/trade/query/assets | Get |  |
| 委托 | http://www.private-elves.xyz/trade/query/orders | Get | Post |
