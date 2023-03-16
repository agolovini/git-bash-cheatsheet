

# Git commands ⚓

At first introduce yourseld, **--global** meaning it is applied to an operating system user  
`$ git config --global user.email "alexey.golovin@gmail.com"`  
`$ git config --global user.name "Alexey Golovin" `  


Запуск и проброс ключей SSH через агента:
старт агента .ssh:
`eval "$(ssh-agent -s)"`

загрузка ключа в агента: (ключи уже созданы и загружены в репозиторий)
`ssh-add ~/.ssh/id_ed25519`   (id_ed25519 - название файла с ключом)

проверка соединения ssh:
`ssh -T git@github.com`
*Hi agolovini! You've successfully authenticated, but GitHub does not provide shell access.*  (сообщение если ок)


Работа с репозиторием:
Клонируем репозиторий
`git clone git@github.com:agolovini/airflow-dag.git`
Стягиваем все изменения из репозитория в локальную папку
`git pull`

создание ветки
`git branch alexey_golovin_09.09_al-golovin/project_variant2`

добавление файла и делаем коммит с комментарием
`git add .; git commit -m "Головин А, проект вариант 2, старт потока-09.09_версия 2,исправлен стиль pep8"`

пушим изменения в репозиторий
`git push origin alexey_golovin_09.09_al-golovin/project_variant2`


Дополнительные команды (просмотр папки, файлов с ключами):
просмотр файла с ключом:
`cat golovini.pub`   (предварительно переходим в папку .ssh - cd .ssh/)
 
просмотр содержимого папки текущей:
`ls -la`

смена директории
`cd /nameofdir/`
