# magma-swagger-api

![](/magmaAPI.png)

After deploying magma orchestrator we want to access the swagger api.

### Copy admin_operator.pfx to your local
```bash
chmod 777 admin_operator.pfx
scp ubuntu@192.168.5.92:/home/ubuntu/magma-galaxy/secrets/admin_operator.pfx .
```
If copying a file from server shows the error of "permission denied" then do 'chmod 777 admin_operator.pfx'

### Import certificate to your browser

### Swagger API format
Use this format. In this you only need to update the nms domain. And paste it to your browser after updating the format to access swagger api.

```bash
https://api.magmalocal.com/swagger/v1/ui/
```

**Example:** Suppose we have nms domain as "galaxy.nitinrajput" so we replace from magmalocal to galaxy.nitinrajput
