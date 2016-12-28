## Cinder 创建consisgroup一致性组报错：

![img](/img/IMG_20161227_112120.jpg)


### 报错原因是***/etc/cinder/policy.json***文件中的**group:nobody**没有修改成**rule:admin_or_owner**导致的，修改后即可创建consisgroup一致性组了！