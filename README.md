# open-api-pets
https://garafu.blogspot.com/2020/06/multi-file-openapi.html

path, model 両方分割

build下のopen api.yml は、分割したファイルを下記コマンドで結合して生成したファイル

```
swagger-cli bundle -o ./build/openapi.yaml -t yaml ./openapi.yaml
```
