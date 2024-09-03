# Создание L7-балансировщика Yandex Application Load Balancer с защитой от DDoS-атак

Разверните инфраструктуру для защиты бэкендов приложения от DDoS-атак в Yandex Cloud. Для этого создайте облачную сеть, настройте группы безопасности [Yandex Virtual Private Cloud](https://yandex.cloud/ru/docs/vpc/), создайте группу ВМ [Yandex Compute Cloud](https://yandex.cloud/ru/docs/compute/) и свяжете ее с инфраструктурой [L7-балансировщика](https://yandex.cloud/ru/docs/application-load-balancer/concepts/application-load-balancer) [Yandex Application Load Balancer](https://yandex.cloud/ru/docs/application-load-balancer/).

Подготовка инфраструктуры для L7-балансировщика с защитой от DDoS с помощью Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/security/alb-with-ddos-protection), необходимые для настройки конфигурационные файлы `alb-with-ddos-protection.tf` и `alb-with-ddos-protection.auto.tfvars` расположены в этом репозитории.
