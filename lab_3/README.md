# Отчёт по проекту: Исследование Cloud Storage
> **University:** [ITMO University](https://itmo.ru)
> 
> **Faculty:** [FTMI] (https://ftmi.itmo.ru/)
> 
> **Course:** [Cloud platforms as the basis of technology entrepreneurship]
> 
> **Year:** 2025/2026
> 
> **Group:** U4225
> 
> **Author:** Seregin Artem Aleksandrovich
> 
> **Lab:** Lab3
> 
> **Date of create:** -
> 
> **Date of finished:** -

---
### Шаг 1. Создание бакета (Cloud Storage Bucket)
* В разделе `Cloud Storage` создал новый бакет с уникальным именем `aseregin-bucket-lab3`.
* В настройках безопасности отключил блокировку публичного доступа (`Enforce public access prevention on this bucket`), чтобы иметь возможность делиться файлами.
* В качестве модели управления доступом выбрал индивидуальный режим `Fine-grained` (ACL) для детальной настройки прав отдельных объектов.


<img width="1910" height="744" alt="image" src="https://github.com/user-attachments/assets/ab6ffed8-fb3e-4e59-83ab-d69201fa36db" />

### Шаг 2. Организация структуры данных
* Загрузил в корень бакета несколько графических файлов (включая `11.jfif`).
* Создал логическую папку для упорядочивания структуры хранения.
* Переместил загруженные изображения внутрь созданной директории.


<img width="1888" height="686" alt="image" src="https://github.com/user-attachments/assets/9cc17758-5a5e-4608-a3c2-4bdacfe3562b" />

<img width="1876" height="623" alt="image" src="https://github.com/user-attachments/assets/86e42c99-2576-45fa-b328-937b5c970779" />

### Шаг 3. Настройка публичного доступа к файлу
* Открыл меню редактирования прав объекта `Edit access` для файла `11.jfif`.
* Настроил права доступа для всех пользователей интернета, выбрав в поле `Entity` тип `Public` (сущность `allUsers`) со скромными правами на чтение `Reader`.
* После сохранения настроек безопасности для объекта сгенерировалась уникальная публичная ссылка в столбце `Public URL`.
* Перешел по ссылке в новой вкладке браузера без авторизации в Google-аккаунте и успешно открыл изображение.


<img width="715" height="616" alt="image" src="https://github.com/user-attachments/assets/f10d8078-d4bc-46ba-96b6-67ec052f62c5" />

