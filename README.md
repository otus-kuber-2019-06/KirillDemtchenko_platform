# KirillDemtchenko_platform
KirillDemtchenko Platform repository

# Домашнее задание 1:

1. Установил и запустил minikube.  
2. Настроил автодополнение для kubectl.  
3. Проверил работу кластера.  
4. Попробовал "убить" все поды в kube-system. При этом k8s восстановил их работу. Восстановление работы подов описывается в deployment. 
Посмотерть конфиги деплоймента можно следующей командой:  

`kubectl -n kube-system get deploy coredns  -o yaml`  

Если говорить о kubeapi-server, то это служба и запускается напрямую через kubelet.  

5. Создал Dockerfile из Python образа для веб-сервера.  
6. Далее описал манифест для запуска веб и инит подов в кластере.  
7. Проверил рабоспособность сервера.  
