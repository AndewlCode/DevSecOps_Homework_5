# DevSecOps_Homework_5
 
1. Kubernetes установлен. Информация о кластере отображена в консоли.

![01-cluster_info](images/01-cluster_info.png)


2. Подготовлен yaml файл для развёртывания nginx в 3-х репликах. По-умолчанию контейнер слушает 80 порт.

![02-deployment](images/02-deployment.png)


3. Поднимаем поды используя подготовленный yaml-файл.

![03-delpoyment_apply](images/03-delpoyment_apply.png)


4. Получаем информацию о состоянии подов / контейнеров.

![04-get_pods](images/04-get_pods.png)


5. Настраимваем форвардинг портов, чтобы иметь возможность обращаться к приложению, размещённому в контейнере.

![05-port_forwarding](images/05-port_forwarding.png)

6. При помощи утилиты curl проверяем доступность приложения.

![06-curl](images/06-curl.png)