## Steps
1. Create docker registry secret in kubernetes
    ```shell
    kubectl create secret docker-registry regcred --docker-server=https://index.docker.io/v1/ --docker-username=enter_name --docker-password=enter_password --docker-email=enter_mail
    ```
    > Note: Modify the docker-server url to private registry if required.


## Reference:
- https://www.youtube.com/watch?v=YnZQJAMK6JI&list=PL34sAs7_26wOuDEArkiGHjWtitsLsxGCL&index=7