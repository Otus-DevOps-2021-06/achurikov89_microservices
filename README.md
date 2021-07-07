# achurikov89_microservices
achurikov89 microservices repository

## DZ docker-2
- Создание docker host
- Создание своего образа
- Работа с Docker Hub

## DZ docker-3
- Разбиваем наше приложение на несколько компонентов
- Проверяем что все работает (Post.py не работал с python 3.6.0)

## DZ docker-4
- Работа с сетями в Docker
- Практика с docker-compose
- Базовое имя проекта образуется из переменной COMPOSE_PROJECT_NAME, ее значение по умолчанию - название папки в которой запускается docker-compose
- Задать переменную COMPOSE_PROJECT_NAME, можно в файле .env, или используя export

## DZ monitoring-1
- Prometheus: запуск, конфигурация, знакомство с Web UI
- Мониторинг состояния микросервисов
- Сбор метрик хоста с использованием экспортера

## DZ monitoring-2
- Мониторинг Docker контейнеров
- Визуализация метрик
- Сбор метрик работы приложения и бизнес метрик
- Настройка и проверка алертинга

## DZ logging-1
- Подготовка окружения
- Логирование Docker-контейнеров
- Сбор неструктурированных логов
- Визуализация логов
- Сбор структурированных логов
- Распределенный трейсинг

## DZ kubernetes-1
- Установка k8s на двух нодах при помощи утилиты kubeadm
- Установка сетевого плагина Calico
- Проверка статусов нод и подов

## DZ kubernetes-2
- Развертывание локальное окружение для работы с Kubernetes
- Развертывание Kubernetes в Yandex Cloud
- Запуск reddit в Kubernetes


## DZ kubernetes-3
- Ingress Controller
- Ingress
- Secret
- TLS
- LoadBalancer Service
- Network Policies
- PersistentVolumes
- PersistentVolumeClaims

