Домашнее задание для Netology.ru для курса Java Developer   

Описание и инструкция к выполнению [здесь](https://github.com/netology-code/jd-homeworks/tree/master/jvm/README.md)

Вывод программы:

<img width="561" alt="Снимок экрана 2023-02-17 в 22 44 14" src="https://user-images.githubusercontent.com/113035992/219951853-9e083dcf-e054-48f6-ba9f-d946405386ae.png">


21:27:33.656769: loading io.vertx // загрузка классов vertx в Metaspace

21:27:33.838026: loaded 529 classes // загружено 529 классов. Значительно увеличился объем Metaspace для хранения этих классов
![IMG_4428](https://user-images.githubusercontent.com/113035992/219950852-8971e64f-8670-4b66-ae9a-442500925855.PNG)
![IMG_4429](https://user-images.githubusercontent.com/113035992/219951880-49c5d5d4-0d4c-428c-9662-a88dedf60eca.PNG)
![IMG_4430](https://user-images.githubusercontent.com/113035992/219950905-d8464272-dd47-41a4-8617-a2c6224b069a.PNG)

21:27:36.844404: loading io.netty // загружено 815 классов netty в Metaspace
![IMG_4431](https://user-images.githubusercontent.com/113035992/219951034-f530a064-004f-4e1f-9407-fa6bdc68e93a.PNG)
![IMG_4432](https://user-images.githubusercontent.com/113035992/219951039-8b087165-e2f5-45ac-b2f6-22ceb50507aa.PNG)
![IMG_4433](https://user-images.githubusercontent.com/113035992/219951047-97465a59-af79-47c6-9b92-7cb8a26df4fe.PNG)

21:27:37.189070: loaded 2117 classes // загружено 2117 классов. Вырос объем Metaspace. Снизился Heap, значит были удалены неиспользуемые объекты
![IMG_4434](https://user-images.githubusercontent.com/113035992/219951201-554cf101-6848-4bd6-9830-79ef3e378474.PNG)
![IMG_4435](https://user-images.githubusercontent.com/113035992/219951231-bb47d10e-b5a3-4c79-9e41-b159ef4ee38d.PNG)
![IMG_4436](https://user-images.githubusercontent.com/113035992/219951234-416010fa-ee48-4510-9c86-3634fbe47f96.PNG)

21:27:40.194187: loading org.springframework // загрузка классов springframework в Metaspace

21:27:40.306425: loaded 869 classes // загружено 869 классов. Незначительно увеличился объем Heap, вырос Metaspace
![IMG_4437](https://user-images.githubusercontent.com/113035992/219951246-9fc42270-60ae-4cdf-a4c6-f1aa90f75250.PNG)
![IMG_4438](https://user-images.githubusercontent.com/113035992/219951251-a6771688-5da8-40a4-a3af-f6266b8f2444.PNG)
![IMG_4439](https://user-images.githubusercontent.com/113035992/219951254-897a48ee-6b24-4c0d-96dd-64e4df619832.PNG)
![IMG_4440](https://user-images.githubusercontent.com/113035992/219951258-6c3467bb-77bd-40ba-bf53-4fa8dcad2330.PNG)

21:27:43.311539: now see heap // сообщение об обращении внимания на Heap

21:27:43.312197: creating 5000000 objects // создано 5 000 000 объектов

21:27:43.498426: created //  В Classes загружен 1 класс. Значительно увеличились Heap и Metaspace, из-за создания большого количества объектов
![IMG_4441](https://user-images.githubusercontent.com/113035992/219951263-e1a882b3-ed30-42f4-9e89-bdbe143998a2.PNG)
![IMG_4442](https://user-images.githubusercontent.com/113035992/219951267-1037c940-1956-4a51-82ec-1c90eef48b40.PNG)
![IMG_4443](https://user-images.githubusercontent.com/113035992/219951269-e78bdbdf-76d7-4738-a61f-76be5ede18ed.PNG)
![IMG_4444](https://user-images.githubusercontent.com/113035992/219951271-176d813f-40fa-437f-a5d8-d116690162ec.PNG)
![IMG_4445](https://user-images.githubusercontent.com/113035992/219951278-7050fe25-ec59-4cb6-8fdf-52429ea806ac.PNG)

21:27:46.500730: creating 5000000 objects// создано 5 000 000 объектов

21:27:46.640653: created // В Classes движение отсутствует. Значительно увеличились Heap и Metaspace, из-за создания большого количества объектов
![IMG_4446](https://user-images.githubusercontent.com/113035992/219951609-520721bc-faed-4a1d-92f9-a112c272f156.PNG)
![IMG_4447](https://user-images.githubusercontent.com/113035992/219951614-b0a88767-322e-4ddf-a4f3-18d46427d23e.PNG)
![IMG_4448](https://user-images.githubusercontent.com/113035992/219951616-f3351f40-51b5-4816-87d1-ee047454e918.PNG)

21:27:49.672850: creating 5000000 objects // создано 5 000 000 объектов

21:27:49.842587: created // В Classes движение отсутствует. Значительный рост зарезервированного значения Heap, 
а использованное - снизилось в результате работы Garbage Collector. Отсутствие изменений в Metaspace
![IMG_4449](https://user-images.githubusercontent.com/113035992/219951622-b813e95e-e1a0-42a6-9e26-bd6ace3acaa3.PNG)
![IMG_4450](https://user-images.githubusercontent.com/113035992/219951626-836ea54f-0420-4a08-8bfb-b5f98ef113e0.PNG)
![IMG_4451](https://user-images.githubusercontent.com/113035992/219951627-ab06edfd-cc36-4490-a66c-cea6f4f9a035.PNG)
![IMG_4452](https://user-images.githubusercontent.com/113035992/219951631-f7319235-8e22-4770-bb9e-a38a8327fd31.PNG)

BUILD SUCCESSFUL in 51s

2 actionable tasks: 2 executed

21:27:53: Execution finished ':JvmExperience.main()'. // Созданы 2 класса, что видно в Classes. Незначительно увеличился объем используемой памяти Heap и Metaspace. Программа завершила работу
![IMG_4453](https://user-images.githubusercontent.com/113035992/219951783-d0e91568-c179-4e28-a95b-1f5a1b4025c4.PNG)
![IMG_4454](https://user-images.githubusercontent.com/113035992/219951788-e125ae3b-f3bf-4eb4-b34b-936318cdb8a7.PNG)
![IMG_4455](https://user-images.githubusercontent.com/113035992/219951792-5fa08b56-f67a-43c2-8311-2a6ae8e500a2.PNG)
![IMG_4456](https://user-images.githubusercontent.com/113035992/219951794-7af91f28-fed7-4e85-92d6-72ca9c25c974.PNG)
