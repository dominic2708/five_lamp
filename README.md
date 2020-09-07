# 小米FIVE智能消毒殺菌燈


小米FIVE智能消毒殺菌燈接入HomeAssistant組件


## 安装




###解壓後將five_lamp資料夾放入custom_components

### configuration.yaml
```
switch:
  - platform: five_lamp
    name: xxxxx
    host: xxx.xxx.xxx.xxx
    token: xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
    

```
```

可選屬性:scan_interval: x
每x秒更新一次


屬性內Time remaining為開啟消毒後之倒數計時秒數

```



## 功能服務

### switch服務  `turn_on`

### switch服務  `turn_off`


