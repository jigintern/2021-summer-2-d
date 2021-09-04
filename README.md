# 2021-summer-2-d
```sh
deno run -A server.js
```

## API
### /api/get
海水浴場のデータを取得する
call:("/api/get",{type,ID}),return:{name,lat,lng,info,img}
            
### /api/add
掲示板に書き込む
call:("/api/badd",data{未定}),return:"ok"

### /api/list
全ての掲示板の内容を返却
call:("/api/blist"),return:[data{未定}, ...]

### /api/blist
指定された掲示板の内容を返却
call:("/api/blist",boardID),return:[data{未定}, ...]

### /api/get-allID
メニュー画面用
call:("/api/get-allID",mode),return:[{ID,name}, ...]
            
### /api/wlevel
不明
call:(/api/wlevel),return:[{data}, ...]

### /api/rwlevel
指定した河川の水位情報を返却
call:("/api/rwlevel",river),return:[{data}, ...]

### /api/pull_pin
未使用
call:("api/pull_pin"),return:[{lat,lng}, ...]

### /api/push_pin
未使用
call:("api/push_pin",{lat,lng}),return:ok


