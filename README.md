```
terraform init
```

```
terraform plan -var "do_token=${DO_PAT}" -var "ssh_private_key=/root/.ssh/id_rsa" -var "docker_host=178.128.114.248" -var "docker_cert_path=/root/.docker/machine/machines/docker-nginx"
```

```
terraform apply -auto-approve -var "do_token=${DO_PAT}" -var "ssh_private_key=/root/.ssh/id_rsa" -var "docker_host=178.128.114.248" -var "docker_cert_path=/root/.docker/machine/machines/docker-nginx"
```

```
terraform destroy -auto-approve -var "do_token=${DO_PAT}" -var "ssh_private_key=/root/.ssh/id_rsa" -var "docker_host=178.128.114.248" -var "docker_cert_path=/root/.docker/machine/machines/docker-nginx"
```