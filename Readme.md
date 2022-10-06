# инструкиця по работе с Git

## Базовые команды при работе с Git

* git --version*  - **Версия системы Git**

* git config --global user.name «Ваше имя английскими буквами»* - **Ввод имени в систему**

* git config --global user.email ваша почта@example.com* - **Ввод электронной почты**

* git init* - **Инициализация локального репозитория**

* git status* - **Вывод состояния системы на данный момент**

* git add* - **Добавление версионности файлу**

* git commit -m <Some_message>* - **Добавление файлов к комиту(сохранению)**

* git diff* - **Команада для вывода разницы менжду последним коммитом и текущими изменениями**

* git log* - **Вывод списка в хронологическом порядке**

* git checkout <Хэш-номер коммита или master>* - **Переключение между различными коммитами (сохраниениями)**

* git log --graph - **Показать все ветки с коммитами**

* git branch <имя ветки>- **Создать ветку**

* git merge <имя ветки которую хотим добавить> - **соедениить ветки при чём соединяем из той в которую ходим добавить**

* git branch -d <имя ветки> - **удаление ненужной ветки**

* git push - **Отправка коммита в публику**

* git pull - **Вытянуть из гитхаба последнюю версию**

* git clone <ссылка с GitHub> - **Скачать репозиторий с гит хаба**

Загрузка выгрузка с GitHub

1. Создали аккаунтн на GutHub
2. Создать локальный репозиторий
3. Подружить локальный и удаленый репозиторий
4. Отправить (push)локальный репозиторий на удаленный 
5. Провести изменение я другого пк
6. Выкачать (pull) актуальное состояние из удаленного репозитория

Работа с fork

1. Делаем (fork) интересуещего нас репозитория
2. Мы делаем git clone для нашей версии этого репозитория
3. Мы создаем ветку с предлагаемыми изменениями
4. Производим все изменения только в этой ветке
5. Отправляем эти изменения на свой аккаунт (push)
6. Окне на GitHub появляется возможность отправлять pull request

# Соединение Git - GitHub
# …or create a new repository on the command line
* echo "# Conspect" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/Misha815/Conspect.git
* git push -u origin main


# …or push an existing repository from the command line
* git remote add origin https://github.com/Misha815/Conspect.git
* git branch -M main
* git push -u origin main