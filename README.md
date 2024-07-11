# Criação de .tf para subir um EC2 e um S3

## Inicializar o Terraform
Executando o comando `terraform init`
![alt text](assets/init.png)

## Vizualizar o plano de Execução
Executando o comando `teraform plan`
![alt text](assets/plan-1.png)
![alt text](assets/plan-2.png)

## Aplicar plano 
Executando o comando `teraform apply`
![alt text](assets/apply-1.png)
![alt text](assets/apply-2.png)

## Verificação da criação dos recursos no console da AWS
![alt text](assets/EC2-1.png)
![alt text](assets/S3-1.png)

## Limpeza dos recursos
Execução do comando `terraform destroy`
![alt text](assets/destroy.png)

## Verificação final dos recursos no console da AWS
![alt text](assets/EC2-2.png)
![alt text](assets/S3-2.png)