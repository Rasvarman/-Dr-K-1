# -Dr-K-1
 Dr K-1

 Домашнее задание к занятию 1 «Disaster recovery и Keepalived»

 Задание 1

 Дана схема для Cisco Packet Tracer, рассматриваемая в лекции.
На данной схеме уже настроено отслеживание интерфейсов маршрутизаторов Gi0/1 (для нулевой группы)
Необходимо аналогично настроить отслеживание состояния интерфейсов Gi0/0 (для первой группы).
Для проверки корректности настройки, разорвите один из кабелей между одним из маршрутизаторов и Switch0 и запустите ping между PC0 и Server0.
На проверку отправьте получившуюся схему в формате pkt и скриншот, где виден процесс настройки маршрутизатора.

![Screenshot_30](https://github.com/user-attachments/assets/5a4837c3-83af-4011-905a-823afd714a6e)
![Screenshot_31](https://github.com/user-attachments/assets/2bd9cb30-4c61-4261-ac20-96087401b679)

![Screenshot_23](https://github.com/user-attachments/assets/540eb7c5-7432-4c73-88ba-ba1a1f381ac0)


Задание 2
Запустите две виртуальные машины Linux, установите и настройте сервис Keepalived как в лекции, используя пример конфигурационного файла.
Настройте любой веб-сервер (например, nginx или simple python server) на двух виртуальных машинах
Напишите Bash-скрипт, который будет проверять доступность порта данного веб-сервера и существование файла index.html в root-директории данного веб-сервера.
Настройте Keepalived так, чтобы он запускал данный скрипт каждые 3 секунды и переносил виртуальный IP на другой сервер, если bash-скрипт завершался с кодом, отличным от нуля (то есть порт веб-сервера был недоступен или отсутствовал index.html). Используйте для этого секцию vrrp_script
На проверку отправьте получившейся bash-скрипт и конфигурационный файл keepalived, а также скриншот с демонстрацией переезда плавающего ip на другой сервер в случае недоступности порта или файла index.html



![Screenshot_95](https://github.com/user-attachments/assets/040ea4af-aeed-4ffe-86cd-f6809d4e59ab)
![Screenshot_94](https://github.com/user-attachments/assets/01496b34-827b-4c99-acde-ff6f15796c8f)

![Screenshot_96](https://github.com/user-attachments/assets/91b42d27-b599-40be-ad57-342db21f7771)

![Screenshot_97](https://github.com/user-attachments/assets/753c9744-2132-410c-95f8-2b3dea917ce2)
![Screenshot_98](https://github.com/user-attachments/assets/5c36cdea-530b-4709-8b84-4a4f3b15fba1)

![Screenshot_98](https://github.com/user-attachments/assets/78e8205a-0256-4e2b-aa0f-2e284977b7f0)
