## 获取滑块验证信息接口

### 请求URL：
- http://localhost:8080/getVerifyData

### 请求方式：
- GET


### 返回示例

```
{
    "code":1,
    "data":{
        "position_y":165,
        "slide_img":"data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDACodICUgGiolIiUvLSoyP2lEPzo6P4FcYUxpmYagnpaGk5GovfLNqLPltZGT0v/V5fr/////o8v///////L/////2wBDAS0vLz83P3xERHz/rpOu////////////////////////////////////////////////////////////////////wAARCAAyADIDASIAAhEBAxEB/8QAHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUFBAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkKFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwCyc5PNHPrSnqaMVqZCc+tHPrS4oxQAmT60c+tLimswUgHjNAEgzgUUDoKKQxD1oxTiOaTFAhMUdKdikIA+9xQOwQqWO49O1MuFDDcB0FSZLcD5UA6UhI2lR1PBpdRkCn5RyelFTBFwPlP50U7jsPPWlAJ7fnUmwClxipuFiLYxBGevtTdgQcksfQVPR3pXHYiVGOd2BT/LXOcfnSnjntVZrr95hBwO5pq7AseYn96iq/2j2X8qKLCuWzTaKKkY49KKKKAI7j/UtVVFGDwKKK0iJkgAwOBRRRQB/9k=",
        "main_img":"data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDACodICUgGiolIiUvLSoyP2lEPzo6P4FcYUxpmYagnpaGk5GovfLNqLPltZGT0v/V5fr/////o8v///////L/////2wBDAS0vLz83P3xERHz/rpOu////////////////////////////////////////////////////////////////////wAARCAC0APoDASIAAhEBAxEB/8QAHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUFBAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkKFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwBxlkyf3j9f7xo82T/no/5mmn7x+tFb2Rlcf5sn/PR/zNHmyf8APRvzNMpaVkFx/myf89G/M0ebJ/fb8zTaKLILjvNk/wCejfnS+ZJ/z0b86bRRZBcd5kn99vzpfMk/vt+dMpaLILjvMf8Avt+dHmSf32/Om0tFkFxfMk/vt+dL5kn99vzptFKyC47zJP77fnR5kn99vzpKKLILi+Y/99vzo8x/77fnSUUWQXF8x/77fnR5j/32/OkoosguL5j/AN9vzo8x/wC+350lFFkAvmP/AH2/OjzH/vt+dJRRZAL5j/32/OjzH/vt+dJRRZAL5kn99vzo8yT++350lFFkAvmSf32/Ok8yT++350lFFkAvmSf32/Op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",
        "token":"abcdefff111222333"
    },
    "msg":""
}
```


## 验证滑块接口

### 请求URL：
- http://localhost:8080/getVerifyData

### 请求方式：
- POST - json

### 参数：

| 参数名 | 必选 | 类型 | 说明 |
| ---- | ---- | ---- | ---- |
| position_x | 是 | string | 位置X像素值 |
| token | 是 | string | 使用获取验签的token |

### 请求示例

```
{
    "position_x":"75.01",
    "token":"asd123zxc"
}
```


### 返回示例

```
{
	"code": 0,
	"data": {
		"is_success": true,
		"login_token": "test111222333"
	},
	"msg": "验证失败，请重新获取验证信息"
}
```
