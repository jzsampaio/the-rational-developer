* Pgadmin

```
docker run -p 80:80 \
-e "PGADMIN_DEFAULT_EMAIL=admin@admin.com" \
-e "PGADMIN_DEFAULT_PASSWORD=adminadmin" \
--net=host \
-d dpage/pgadmin4
-v pgadmin_volume
```
