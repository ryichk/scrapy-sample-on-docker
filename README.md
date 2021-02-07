# Scrapy Sample on Docker

## Set UP

```docker
 docker build --tag scrapy-sample . --no-cache
 docker run -it --rm --name scrapy-sample -v $PWD:/app scrapy-sample
```

## Reference

[doc-ja-scrapy.readthedocs.io](https://doc-ja-scrapy.readthedocs.io/ja/latest/intro/tutorial.html)