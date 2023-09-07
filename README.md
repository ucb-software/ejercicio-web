# ejercicio-web

``` 
@ernestomar ➜ /workspaces/ejercicio-web (main) $ pwd
/workspaces/ejercicio-web
@ernestomar ➜ /workspaces/ejercicio-web (main) $ mkdir html
@ernestomar ➜ /workspaces/ejercicio-web (main) $ cd html/
@ernestomar ➜ /workspaces/ejercicio-web/html (main) $ pwd
/workspaces/ejercicio-web/html
@ernestomar ➜ /workspaces/ejercicio-web/html (main) $ 
```

Creamos el contenedor

docker run --name some-nginx -p 8080:80  -v /workspaces/ejercicio-web/html:/usr/share/nginx/html:ro -d nginx
