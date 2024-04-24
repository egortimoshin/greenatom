# Тестовое задание JAVA для Greenatom
Требуется создать простейший движок форума/доски объявлений (только backend). Суть задачи: 
Есть топики (темы), в каждом топике может быть одно или более сообщений. Движок должен обеспечивать хранение в БД (IMDB) и CRUD операции с топиками (темами) и сообщениями в топиках. Топик должен содержать заголовок (название темы). Топик не может быть пустым, т.е. должен содержать как минимум одно сообщение. Сообщение должно содержать имя (ник) автора, текст сообщения, дату создания. Сообщение обязательно должно относиться к одному из топиков. Необходимо реализовать клиентский REST-API позволяющий пользователю:
- получать список топиков
- получать сообщения в указанном топике
- создать топик (с первым сообщением в нем)
- создать сообщение в указанном топике
- отредактировать свое сообщение
- удалить свое сообщение

# Требования
- Язык – Java (Spring или Spring Boot - по желанию)
- Автоматизация сборки – Maven (Gradle)
- Хранилище – in-memory DB (со скриптом по наполнению тестовыми данными) / PostgreSQL

# Выполненные задания на дополнительный бал
1. Реализовать аутентификацию пользователей (т.е. для доступа к сервису необходимо сперва залогиниться)
2. Реализовать REST-API администратора. Администратор может редактировать и удалять любые сообщения и топики.

# Документация для API доступна по ссылке 
http://localhost:8080/swagger-ui/index.html

<img width="1415" alt="image" src="https://github.com/egortimoshin/greenatom/assets/122122063/b232e991-930c-4340-a432-2f6be2d45f18">
