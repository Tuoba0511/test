## 互联网平台开发第三方接口&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;版本号：2017081102929

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;最后修改者： zjh  2017-04-15 17:38:49
### 月租车辆充值
**编号:<font color="#FF0000">d0018</font>**

`GET-http://zjhwebpark.tunnel.qydev.com/ApiPlatform/chargeMonthCar`

 应用场景; 第三方平台调用该接口对月租车辆充值使用。


请求参数

|参数名            | 参数类型         |必传       |缺省值                          |描述|
| :---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
|SecretKey        | string            | <font color="#FF0000">Y</font>        |xx                              |第三方平台授权编码|
|parkKey          | string            | <font color="#FF0000">Y</font>          |e0b3ca87caf3a415bb3b3f52ca8aa795|停车场唯一编号|
|carNo            | string            | <font color="#FF0000">Y</font>         |粤B11119                        |车牌号码|
|mthCount      |int                   | <font color="#ff0000">Y</font>         |   1     |充值月数|
|mthChargyMoney|int|<font color="#ff0000">Y</font>|150|充值金额|
  
返回值

```
 {
  "Success": true,
  "Message": "ok",
  "Code": "0000",
  "Data": ""
      }
```

---
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;最后修改者： zjh  2017-04-15 17:38:49
### 月租车辆充值
**编号:<font color="#FF0000">d0018</font>**

`GET-http://zjhwebpark.tunnel.qydev.com/ApiPlatform/chargeMonthCar`

 应用场景; 第三方平台调用该接口对月租车辆充值使用。


请求参数

|参数名            | 参数类型         |必传       |缺省值                          |描述|
| :---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
|SecretKey        | string            | <font color="#FF0000">Y</font>        |xx                              |第三方平台授权编码|
|parkKey          | string            | <font color="#FF0000">Y</font>          |e0b3ca87caf3a415bb3b3f52ca8aa795|停车场唯一编号|
|carNo            | string            | <font color="#FF0000">Y</font>         |粤B11119                        |车牌号码|
|mthCount      |int                   | <font color="#ff0000">Y</font>         |   1     |充值月数|
|mthChargyMoney|int|<font color="#ff0000">Y</font>|150|充值金额|
  
返回值

```
 {
  "Success": true,
  "Message": "ok",
  "Code": "0000",
  "Data": ""
      }
```

