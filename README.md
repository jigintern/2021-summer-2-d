# 2021-summer-2-d
```sh
deno run -A server.js
```

## API
### /api/get
海水浴場のデータを取得する<br>
call:("/api/get",{type,ID})<br>
return:{name,lat,lng,info,img}<br>
            
### /api/add
掲示板に書き込む<br>
call:("/api/badd",data{未定})<br>
return:"ok"<br>

### /api/list
全ての掲示板の内容を返却<br>
call:("/api/blist")<br>
return:[data{未定}, ...]<br>

### /api/blist
指定された掲示板の内容を返却<br>
call:("/api/blist",boardID)<br>
return:[data{未定}, ...]<br>

### /api/get-allID
メニュー画面用<br>
call:("/api/get-allID",mode)<br>
return:[{ID,name}, ...]<br>
            
### /api/wlevel
不明<br>
call:(/api/wlevel)<br>
return:[{data}, ...]<br>

### /api/rwlevel
指定した河川の水位情報を返却<br>
call:("/api/rwlevel",river)<br>
return:[{data}, ...]<br>

### /api/pull_pin
未使用<br>
call:("api/pull_pin")<br>
return:[{lat,lng}, ...]<br>

### /api/push_pin
未使用<br>
call:("api/push_pin",{lat,lng})<br>
return:ok<br>


