# Спасибо за интерес к моей ссылке!
## Postman_Traning_DummyAPI

Используя тренировочный [сайт](https://dummyapi.io) для тренировки написания api запросов, создал коллекцию которая состоит из:

* Проверки списка пользователей.
* Создания нового пользователя.
* Проверки нового пользователя.
* Обновления информации в профиле пользователя.
* Проверки профиля после обновления.
* Создание поста этого пользователя.
* Проверки этого поста.
* Обновления поста.
* Проверки поста после обновления.
* Проверки списка коментов.
* Создание коммента к созданному посту.
* Проверки комента по посту.
* Проверка коммента по пользователю.
* Удаление коммента.
* Проверка, поста, что коммент удален.
* Проверка пользователя, что коммент удален.
* Удаление Поста пользователя.
* Проверка, что пост удален.
* Удаление созданного пользователя.
* Проверка, что пользователь успешно удален.

Для автоматизации проверки были созданы и использованны переменные которые записываются в окружение DummiTestEvir. Таким образом, если в запросе требуется обращение к переменной, ее не нужно копировать и вставлять, тк при отправке запроса содержащего данную переменную, она добавляется в окружение и вызывается при необходимости.

+ userId - переменная для id пользователя.

     pm.environment.set("userId", JsonDate.id);

+ postId - переменная для id поста.

    pm.environment.set("postId", JsonDate.id);

+ commentId - переменная для id коммента.

    pm.environment.set("commentId", JsonDate.id);

