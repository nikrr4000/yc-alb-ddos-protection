# Создание балансировщика с защитой от DDoS

В этом руководстве вы развернете инфраструктуру для защиты от DDoS. Для этого вы создадите облачную сеть, настроите группы безопасности [Yandex Virtual Private Cloud](https://yandex.cloud/ru/docs/vpc/), создадите группу ВМ [Yandex Compute Cloud](https://yandex.cloud/ru/docs/compute/), свяжете с ней группу бэкендов, создадите HTTP-роутер и [L7-балансировщик](https://yandex.cloud/ru/docs/application-load-balancer/concepts/application-load-balancer) [Yandex Application Load Balancer](https://yandex.cloud/ru/docs/application-load-balancer/).

Подготовка инфраструктуры для балансировщика с защитой от DDoS с помощью Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/security/alb-with-ddos-protection), необходимые для настройки конфигурационные файлы `alb-with-ddos-protection.tf` и `alb-with-ddos-protection.auto.tfvars` расположены в этом репозитории.
