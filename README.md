## Проект UI автотестов demoqa.com

<!-- Технологии -->

### Используемые технологии
<p  align="center">
  <code><img width="5%" title="Python" src="./resourses/icons/Python-logo-notext.svg"></code>
  <code><img width="5%" title="PyCharm" src="./resourses/icons/pycharm.svg"></code>
  <code><img width="6%" title="PyCharm" src="./resourses/icons/pytest.png"></code>
  <code><img width="6%" title="PyCharm" src="./resourses/icons/selene.png"></code>
  <code><img width="5%" title="Allure Report" src="./resourses/icons/allure-Report-logo.svg"></code>
  <code><img width="5%" title="Allure TestOps" src="./resourses/icons/allure-ee-logo.svg"></code>
  <code><img width="5%" title="Github" src="./resourses/icons/git-logo.svg"></code>
  <code><img width="5%" title="Jenkins" src="./resourses/icons/jenkins-logo.svg"></code>
  <code><img width="5%" title="Jira" src="./resourses/icons/jira-logo.svg"></code>
  <code><img width="5%" title="Selenoid" src="./resourses/icons/selenoid-logo.svg"></code>
  <code><img width="5%" title="Telegram" src="./resourses/icons/Telegram.svg"></code>
  <code><img width="5%" title="Appium" src="./resourses/icons/Appium-01.png"></code>

</p>


<!-- Тест кейсы -->

### Что проверяем
* Поиск без входа в аккаунт
* Поиск с параметрами со входом в аккаунт
* Посмотреть больше вакансий без поиска
* Вход в аккаунт с помощью пароля


<!-- Jenkins -->

### <img width="3%" title="Jenkins" src="./images/icons/jenkins-logo.svg"> Запуск проекта в Jenkins

### [Job](https://jenkins.autotests.cloud/job/003_python-edbeg1337-head-hunter-mobile/)

##### При нажатии на "Собрать сейчас" начнется сборка тестов и их прохождение, через виртуальную машину в Selenide.
![This is an image](images/screenshots/jenkins.png)


<!-- Allure report -->

### <img width="3%" title="Allure Report" src="images/logo_stacks/allure_report.png"> Allure report

##### После прохождения тестов, результаты можно посмотреть в Allure отчете, где так же содержится ссылка на Jenkins
![This is an image](images/screenshots/allure_dashboard.png)

##### Во вкладке Graphs можно посмотреть графики о прохождении тестов, по их приоритезации, по времени прохождения и др.
![This is an image](images/screenshots/allure_graphs.png)

##### Во вкладке Suites находятся собранные тест кейсы, у которых описаны шаги и приложены логи, скриншот и видео о прохождении теста
![This is an image](images/screenshots/allure_suites.png)

##### Видео прохождение теста
![This is an image](images/screenshots/tests_ui.gif)


<!-- Allure TestOps -->

### <img width="3%" title="Allure TestOps" src="images/logo_stacks/allure_testops.png"> Интеграция с Allure TestOps

### [Dashboard](https://allure.autotests.cloud/project/1720/dashboards)

##### Так же вся отчетность сохраняется в Allure TestOps, где строятся аналогичные графики.
![This is an image](images/screenshots/allure_testops_dashboard.png)

#### Во вкладке со сьютами, мы можем:
- Управлять всеми тест-кейсами или с каждым отдельно
- Перезапускать каждый тест отдельно от всех тестов
- Настроить интеграцию с Jira
- Добавлять ручные тесты и т.д

![This is an image](images/screenshots/allure_testops_suites.png)


<!-- Jira -->

### <img width="3%" title="Jira" src="images/logo_stacks/jira.png"> Интеграция с Jira
##### Настроив через Allure TestOps интеграцию с Jira, в тикет можно пробросить результат прохождение тестов и список тест-кейсов из Allure

![This is an image](images/screenshots/jira.png)


<!-- Telegram -->

### <img width="3%" title="Telegram" src="images/logo_stacks/tg.png"> Интеграция с Telegram
##### После прохождения тестов, в Telegram bot приходит сообщение с графиком и небольшой информацией о тестах.

![This is an image](images/screenshots/tg_bot.png)
