# 编辑配置文件

本插件配置目录文件位于 `服务端根目录\plugins\JulySafe-Bin\config.yml` 。

本插件所有版本均使用 **UTF-8** 解码，请勿使用其他编码。推荐使用 `Visual Studio Code` 来编辑，请勿使用记事本编辑。

编辑完成后需要手动进行重载，重载指令：`/jsafe reload`。

## 默认配置文件

```yaml
item:
  stack: true # 堆叠物品
  keep_time: 3600 # 保管一小时
  max_count: 1000 # 最大物品数量
```

