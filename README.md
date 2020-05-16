# Zend Framework 1.8 Web Application Development

```
docker build -t zend .
```

```
docker run -i --rm --name zend \
-v $(pwd)/www:/var/www \
-v $(pwd)/sites-enabled:/etc/apache2/sites-enabled \
-v $(pwd)/logs:/var/logs/apache2/apps \
-p 80:80 \
-p 8001:8001 \
zend
```

hellozend => http://localhost:8001
