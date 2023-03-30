# Приложение для учителя

Веб-приложение разработано для учителя и является инструментом по тестированию учеников. Приложение позволяет создавать упражнения с вопросами и сохранять их в ДБ Firebase. В админской части приложения учитель может составить тест для ученика, выбрав нужные вопросы из различных разделов. Тест будет сохранён в ДБ Firebase. На основании хэш-суммы теста будет сформирована ссылка, которую учитель может отправить ученику. При прохождении по ссылке у ученика в веб-приложении откроется данный тест. Ученик сможет пройти его и учителю будет отправлен результат теста на почту. Всё взаимодействие происходит без регистрации ученика, что сильно упрощает взаимодействие с веб-приложением.

## Схема работы приложения

Для работы в админке нужно пройти [сюда](https://teplospbru.github.io/fefilova/#/admin/)

![Иллюстрация к проекту](https://github.com/teplospbru/teacher-app/blob/release/test-steps.png/)


## ТЕСТИРОВАНИЕ ПРИЛОЖЕНИЯ

Приложение тестируется при помощи [React Testing Library](https://testing-library.com/), [Jest](https://testing-library.com/), [Cypress](https://testing-library.com/)

### Запуск unit- и интеграционных тестов 

Тесты запускаются скриптом`npm run test` из консоли.

### Запуск e2e-тестов 

Тесты запускаются скриптом`npm run cypress:open` из консоли.


## Запуск приложения 

Приложение запускается скриптом`npm run start` из консоли. Приложение откроется в браузере по адресу [http://localhost:8080](http://localhost:8080) 


## Развёрнутое приложение

Увидеть работу приложения можно [здесь](https://teplospbru.github.io/fefilova/).