## Checkpoint 5 - Technical Documentation 

# MinIO server command:

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
quay.io/minio/minio server /data --console-address ":9001"
```
**Note on image substitution:** The command given specifies the `minio/minio` image, but failed with pull access denied error. According to the internet its because the official MINIO team deleted their repositories from Docker Hub. I used `quay.io/minio/minio` since its a build straight from the original vendor. But you can also use `pgsty/minio` since its an active community fork that is a drop in replacement.


# Web Console Access
Port 9001 accesses the web console.

# Bucket Name
client-photos is the name of the bucket

# Environment Variables Explanation
The -e flags pass environment variables to the container. They configure the root username and password. This secures the MinIO server and enables administrator login.      