# Humanzepola 3000

---

Корневой репозиторий инфраструктуры программного продукта Humanzepola3000

---

#### Система демографического учета и анализа

---

Система планирует состоять из:

1. Узлы приёма данных (Роддома)
	- nginx
	- vue
	- laravel
	- mysql


2. Интерактивное хранилище данных о людях
	- nginx
	- vue
	- laravel
	- postgres
	- redis
	- elasticsearch


3. Архив (архивированные json файлы с данными за каждый час)
	- nginx
	- laravel
	- mysql


4. Любое множество consumer\`ов и producer\`ов



5. Обменник(и) обеспечивающий(ие) общение между сервисами
	- rabbitmq
