# kube-ansible-terraform

## How to use

```
terraform init \
-backend-config "endpoint=http://minio.xiaomo.io" \
-backend-config "access_key=minioadmin" \
-backend-config "secret_key=minioadmin" \
-backend-config "bucket=terraform" \
-backend-config "key=kube-salt.tfstate"
```