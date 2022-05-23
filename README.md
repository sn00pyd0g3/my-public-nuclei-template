# my-public-nuclei-template
## swagger-ui-dom-xss
```
httpx -silent -mc 200 -ms "Swagger UI" -path swagger-path.txt -l url.txt | nuclei -silent -t swagger-ui-dom-xss.yaml -headless
```

