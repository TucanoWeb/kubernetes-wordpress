[![Linkedin](https://img.shields.io/static/v1.svg?logo=linkedin&color=f78A38&labelColor=083468&logoColor=ffffff&style=for-the-badge&label=Linkedin&message=Public)](https://www.linkedin.com/in/eric-ricielle-2aa1ba237/) [![Elestio examples](https://img.shields.io/static/v1.svg?logo=github&color=f78A38&labelColor=083468&logoColor=ffffff&style=for-the-badge&label=github&message=open%20source)](https://github.com/TucanoWeb) [![Whatsapp](https://img.shields.io/static/v1.svg?logo=whatsapp&color=f78A38&labelColor=083468&logoColor=ffffff&style=for-the-badge&label=Whatsapp&message=Tirar%20Dúvidas)](https://api.whatsapp.com/send?phone=5531992936042)

# Deploy Wordpress App on Kubernetes

This repository contain the instructions to deploy the complete service for wordpress in kubernetes environment.

### Get Stater

1 - First, you need create a storage class. Execute the file storage_class.yml

2 - Now, let's create the secrets to own database. Execute the file secrets_db.yml. Remember of change the password into the file.

3 - Let's make the deployment of mysql and your respective service. Execute the file mysql.yml

4 - Now, let's create POD to run own wordpress. Execute the file wordpress.yml

5 - We want access the website through 80 port, so we need the create a foward to that. Execute the file ingress_wordpress.yml

6 - Enjoy!
