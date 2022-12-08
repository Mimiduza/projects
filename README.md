## Краткое описание проектов, поставленных задач и требований, а также результаты работы


## 🟦 Яндекс Самокат `web` `mobile` `API`   
🔹 Веб-версия — клиентский сайт для заказа самоката и отслеживания статуса доставки   
[Требования](https://drive.google.com/file/d/1Jn2rDfqkXs0w5B7ZyrcIL3b1eKPcHZyr/view?usp=share_link) и [Макеты из Figma](https://drive.google.com/file/d/1wk71kVMGgPmcJ5BBN5cVcOWtwLVqevTt/view?usp=share_link)   

Задачи и ссылки на результаты:
- Составить [чек-лист](https://docs.google.com/spreadsheets/d/1YcTe600PxOcSBpIVFDUwUYAhfmjTTDLRD8CCuhJzULA/edit#gid=1840596572) функциональности отслеживания Статуса заказа
- Составить [чек-лист](https://docs.google.com/spreadsheets/d/1YcTe600PxOcSBpIVFDUwUYAhfmjTTDLRD8CCuhJzULA/edit#gid=964059876) проверок валидации Формы заказа, используя техники тест-дизайна
- Провести кроссбраузерное тестирование по чек-листам и оформить баг-репорты
- Провести [исследовательское тестирование](https://docs.google.com/spreadsheets/d/1YcTe600PxOcSBpIVFDUwUYAhfmjTTDLRD8CCuhJzULA/edit#gid=1543052816) всего приложения

🔹 Мобильное приложение — курьерское приложение для работы с заказами   
[Требования](https://drive.google.com/file/d/1yl4LHtjUHRwneBrEypQcGraGdepPVANU/view?usp=share_link) и [Макеты из Figma](https://drive.google.com/file/d/1AZTXOoqT4j0RQZdBhbPrelzF_AuhkGDs/view?usp=share_link)
   
Задачи и ссылки на результаты:   
- Составить [тест-кейсы](https://docs.google.com/spreadsheets/d/1YcTe600PxOcSBpIVFDUwUYAhfmjTTDLRD8CCuhJzULA/edit#gid=214056477) для проверки функциональности нотификаций: push и всплывающее окно
- Провести тестирование и оформить баг-репорты

🔹 API  
[Требования](https://drive.google.com/file/d/1MzV5OrQ9tBVEMuiNhERR_9N0wgGuRfmH/view?usp=share_link)
   
Задачи и ссылки на результаты:
- Составить [чек-лист](https://docs.google.com/spreadsheets/d/1YcTe600PxOcSBpIVFDUwUYAhfmjTTDLRD8CCuhJzULA/edit#gid=773922057) проверок для работы ручек по созданию курьера `POST`, удалению курьера `DELETE` и получению информации о заказе `GET`
- Провести тестирование и оформить баг-репорты   
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/9fa6661f28feb8db9fcb?action=collection%2Fimport)

#
## 🟦 Яндекс Маршруты `web` 
Сервис, строящий маршрут между указанными адресами, используя разные виды транспорта   
[Требования](https://drive.google.com/file/d/1cm6JQj74ux7GDXPk_CqBNRVFwufADi9s/view?usp=share_link) и [Макеты из Figma](https://drive.google.com/file/d/11jaP5IsPyKZO46Ttg7Luku30Pr8Tml00/view?usp=share_link)   
   
Задачи и ссылки на результаты:
- Составить [чек-лист](https://docs.google.com/spreadsheets/d/1Qrrt8lfdpUlz3aHIes4bNPmy-kFqcbQtXHBNAoUtax8/edit#gid=1234048560) для проверки вёрстки Формы бронирования каршеринга   
- Составить [тест-кейсы](https://docs.google.com/spreadsheets/d/1Qrrt8lfdpUlz3aHIes4bNPmy-kFqcbQtXHBNAoUtax8/edit#gid=1494251307) для работы кнопки Забронировать и логики бронирования каршеринга   
- Провести кроссбраузерное тестирование и оформить баг-репорты   

#
## 🟦 Яндекс Прилавок `API`   
Сервис для заказа продуктов курьерской доставкой с возможностью создания готовых наборов   
[Требования](https://drive.google.com/file/d/1cr_WKouDlIXLh-V3zt_r-ilGexAru0yg/view?usp=share_link)  

Задачи и ссылки на результаты:
- Составить [чек-лист](https://docs.google.com/spreadsheets/d/1-rwhRvFxJSndaErrqGWesvO99PlbD9Js_7XSq_NMyGQ/edit?usp=share_link) проверок для работы ручек c методами `GET`, `POST`, `PUT`, `DELETE`   
- Провести тестирование и оформить баг-репорты  

<details>
<summary>Список тестируемых функциональностей и ручек</summary>   
  Работа с наборами:   
  
  - возможность добавлять продукты в набор. Ручка POST /api/v1/kits/:id/products
  
  Работа с курьерами:   
  
  - возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит. Ручка POST /fast-delivery/v3.1.1/calculate-delivery.xml
  
  Работа с корзиной:   

- возможность получить список продуктов, которые добавили в корзину. Ручка GET /api/v1/orders/:id
- возможность добавлять продукты в корзину. Ручка PUT /api/v1/orders/:id
- возможность удалять корзину. Ручка DELETE /api/v1/orders/:id
  </details>   
 
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/db46c0f32c79bd512bcd?action=collection%2Fimport)

#
## 🟦 Яндекс Метро `mobile`   
Показывает схемы метро различных городов мира и позволяет строить маршруты между станциями   
[Требования](https://drive.google.com/file/d/1pEvYXQqOxzyNnJQICMgNNMyNyIUGnq8W/view?usp=share_link)
   
Задачи и ссылки на результаты:
- Составить [чек-лист](https://docs.google.com/spreadsheets/d/1JnFJQYdhml4qeo3sdvQJVCNFhTOKSzVw-CZcVRNhLCw/edit?usp=share_link) для проверки процесса обновления версии приложения
- Составить чек-лист проверок для ряда функциональностей, получивших изменения (выделены в требованиях жирным шрифтом)


