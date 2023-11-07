# __HR PRACTICUM CAREER__

Ваш самый удобный и современный агрегатор поиска кандидатов*

<sup>_\* по версии нашей команды, подтверждено [Яндексом](https://github.com/Hakaton14/.github/edit/main/profile/README.md#%D0%B4%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%D1%8B)_</sup>

___

### АЛЬФА-ВЕРСИЯ

https://hr-praktikum.webtm.ru/

___

### ВВЕДЕНИЕ

HR Prakticum Career - это веб-приложение, которое поможет HR специалистам быстро и эффективно находить кандидатов на вакансии, вести удобную статистику своей деятельности, в большей степени оптимизировать свою работу и тратить меньше времени на работу.
___

### ОПИСАНИЕ

Миссия HR Prakticum Career - подарить HR специалистам больше времени на личную жизнь. Для этого были реализованы:
- ⚡️возможность поиска кандидатов не только по фильрам, но сразу по целой вакансии
- 🕑 возможность создавать задачи и получать напоминания, связанные с текущими результатами поиска
- 🔄 возможность шаблонизирования, архивирования и повтороного открытия вакансий в пару кликов
- 🫶 интуитивно-понятный интерфейс

___

### ТЕХНОЛОГИИ

HR Prakticum Career разработан с использованием следующих технологий:

- [Python] (v.3.11) - целевой язык программирования backend
- [Django] (v.4.2) - высокоуровневый веб-фреймворк
- [Django REST framework] (v.3.14) - инструмент для создания Web API
- [PostgreSQL] (v.13.10) - объектно-реляционная база данных
- [Celery] (v.5.3) - распределенная очередь задач
- [Redis] (v.5.0) - резидентная система управления NoSQL базами данных, брокер сообщений Celery
- [PyJWT] (v.2.8) - плагин, предоставляющий JSON Web Token аутентификацию для Django REST Framework, разработанную в соответствии со стандартом RFC 7519
- [Gunicorn] (v.21.2) - Python WSGI HTTP-сервер для UNIX
- [Nginx] - HTTP-сервер и обратный прокси-сервер
- [Docker] (v.24.0) - инструмент для автоматизирования процессов разработки, доставки и запуска приложений в контейнерах

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Celery](https://a11ybadges.com/badge?logo=celery)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![PyJWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

- [JavaScript] (v.1.8) - целевой язык программирования frontend
- [TypeScript] (v.5.0) - расширение для JavaScript
- [React] (v.18.2) - библиотека JavaScript для разработки пользовательских интерфейсов (UI) веб-приложений
- [React Router] (v.6.15) - библиотека React для маршрутизации страниц
- [Vite] (v.4.0) - инструмент сборки JavaScript-приложений
- [Redux] (v.8.1) - библиотека  управления состоянием JavaScript приложений
- [Yup] (v.1.3) - библиотека для валидации объектов JavaScript

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)

___


### РАЗВЕРТКА

✅ Создать корневую папку с проектом (предлагается "hakaton") и перейти в неё

```
mkdir hakaton
cd hakaton
```

✅ Загрузить актуальные версии frontend и backend

```
git clone git@github.com:Hakaton14/frontend.git
git clone git@github.com:Hakaton14/backend.git
```

✅ Перейти в папку backend

```
cd backend/hakaton
```

✅ Создать файл переменных окружения из примера

```
cp .env.example .env
```

✅ Изменить переменные окружения (если необходимо) (!согласуйте DB_HOST с настройками в docker-compose сборке!)
```
(на примере редактора Nano)
nano .env
```

✅ Перейти в корневую папку backend
```
cd ..
```

✅ Запустить Docker (убедитесь, что `docker daemon` запущен в системе!)

```
docker-compose up --build
```

✅ Проверить доступность проекта на

```
http://localhost:8000/
```

✅ Документация доступна на

```
http://localhost:8000/api/v1/schema/swagger-ui/
```

___

### ЛИЦЕНЗИЯ

MIT

**Ура, халява!**

___

### Product Manager

🙋‍♀️ [Екатерина]

### КОМАНДА FRONTEND

🧙🏻‍♂️ [Виктор]

🦹‍♀️ [Максим]

### КОМАНДА BACKEND

🦸🏻‍♂️ [Кирилл]

### КОМАНДА UX/UI

🎨 [Анастасия]

👩🏻‍🏫 [Елизавета]

### ДИПЛОМЫ

| RUS | ENG |
|:-------------------------:|:-------------------------:|
|<img width="700" alt="Пономаренко Екатирина (rus)" src="https://github.com/Hakaton14/.github/assets/36377190/7e280d06-cd9c-4459-9774-c73eedc18613">  |  <img width="700" alt="Пономаренко Екатирина (eng)" src="https://github.com/Hakaton14/.github/assets/36377190/658f2b26-413a-4b6f-a2fe-fa8eec9ac9c6">|
| ![Кикодзе Виктор (rus)](https://github.com/Hakaton14/.github/assets/36377190/fd6881f2-8a00-4f0c-907f-9039077e9a25) | ![Кикодзе Виктор (eng)](https://github.com/Hakaton14/.github/assets/36377190/84e0e4fa-f81c-4da4-a8f3-16d3dcaab187) |
| ![Таланов Максим (rus)](https://github.com/Hakaton14/.github/assets/36377190/cd5f8db0-1cb7-405b-9586-010bbdfa0591) | ![Таланов Максим (eng)](https://github.com/Hakaton14/.github/assets/36377190/615dd970-d2d3-4477-a7eb-0a238f9d6fca) |
| ![Кайгородцев Глеб (rus)](https://github.com/Hakaton14/.github/assets/36377190/3caa2a57-7d26-46c2-9196-9daf448c4c46) | ![Кайгородцев Глеб (eng)](https://github.com/Hakaton14/.github/assets/36377190/678ce919-3156-4d82-8d51-c9864cfb7ec5) |
| ![Свидунович Кирилл (rus)](https://github.com/Hakaton14/.github/assets/36377190/5dac64b3-7032-43fc-93b8-0a5764849c36) | ![Свидунович Кирилл (eng)](https://github.com/Hakaton14/.github/assets/36377190/415eedc5-e7f4-4133-abdd-82e4f34da6ee) |
| ![Свидунович Кирилл (rus) - номинация](https://github.com/Hakaton14/.github/assets/36377190/4ffbf77b-2112-4bc6-a6cb-22bc0201c984) | ![Свидунович Кирилл (eng) - номинация](https://github.com/Hakaton14/.github/assets/36377190/8106f4e2-8d83-43cf-8530-02b6e1245368) |
| ![Кременец Анастасия (rus)](https://github.com/Hakaton14/.github/assets/36377190/c47c1601-59c8-4e61-a964-e121c0a8405c) | ![Кременец Анастасия (eng)](https://github.com/Hakaton14/.github/assets/36377190/edc05e86-cb4a-4c66-bdb2-522b5e3fe8ac) |
| ![Рыбакина Елизавета (rus)](https://github.com/Hakaton14/.github/assets/36377190/b939acd5-9a5d-43d6-a7a0-5700a5a97174) | ![Рыбакина Елизавета (eng)](https://github.com/Hakaton14/.github/assets/36377190/30d87031-1cb0-46cc-9d74-0818a58b0dac) |
| ![Чигинцев Константин (rus)](https://github.com/Hakaton14/.github/assets/36377190/38d32e13-271f-48cb-8cdb-83dc59317889) | ![Чигинцев Константин (eng)](https://github.com/Hakaton14/.github/assets/36377190/7e829679-dd33-4b19-867c-1f2a0d7bfed5) |


[Екатерина]: <https://t.me/Katti_po/>
[Виктор]: <https://github.com/vitland/>
[Максим]: <https://github.com/maxtalanov/>
[Кирилл]: <https://github.com/TheSuncatcher222/>
[Анастасия]: <https://behance.net/Anastasia_Kremenets/>
[Елизавета]: <https://behance.net/lisadidntlie/>

[Python]: <https://www.python.org/>
[Django]: <https://www.djangoproject.com/>
[Django REST framework]: <https://www.django-rest-framework.org/>
[PostgreSQL]: <https://www.postgresql.org/>
[Celery]: <https://docs.celeryq.dev/en/stable/>
[Redis]: <https://redis.io/>
[PyJWT]: <https://pyjwt.readthedocs.io/en/latest/>
[Gunicorn]: <https://gunicorn.org/>
[Nginx]: <https://nginx.org/en/>
[Docker]: <https://www.docker.com/>

[JavaScript]: <https://www.javascript.com/>
[TypeScript]: <https://www.typescriptlang.org/>
[React]: <https://react.dev/>
[React Router]: <https://reactrouter.com/en/main/>
[Vite]: <https://vitejs.dev/>
[Redux]: <https://redux.js.org/>
[Yup]: <https://github.com/jquense/yup>
