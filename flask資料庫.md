###### tags: `python`

# flask 資料庫

## 切換到資料庫範例時間點
```python=
git clone http://github.com./amostsai/flask_init.git
cd flask_init
git log
git checkout e36189630226f41f8d7d9f93f66dd787dfaee458
```

## python 存取資料庫 教學
{%youtube KxKRE7PBaO0 %}

----
## 讀取json格式資料

```python=
import requests
import json

res = requests.get("http://localhost/api/v1/users")

res = json.loads(res.text)
print(res['users'][0]['username'])
```

----
## 練習

參考本範例新增以下書籍管理功能
- 新增書本資料
- 修改書本資料
- 查詢所有書本資料
- 查詢單一書本資料
- 刪除書本資料