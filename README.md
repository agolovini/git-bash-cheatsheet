

# Git commands ⚓

At first introduce yourseld, **--global** meaning it is applied to an operating system user  
`$ git config --global user.email "alexey.golovin@gmail.com"`  
`$ git config --global user.name "Alexey Golovin" `  


git clone git@git.lab.karpov.courses:lab/first_project.git
название репозитория
git pull
git branch alexey_golovin_09.09_al-golovin/project_variant2
создание ветки
git add .; git commit -m "Головин А, проект вариант 2, старт потока-09.09_версия 2,исправлен стиль pep8"
добавление файла и делаем коммит с комментарием
git push origin alexey_golovin_09.09_al-golovin/project_variant2
пушим изменения в репозиторий
Дополнительные команды (создание ключей, просмотр папки):
просмотр ключа:
cat golovini.pub   (предварительно переходим в папку .ssh - cd .ssh/)
просмотр содержимого папки текущей:
ls -la
старт агента .ssh:
$ eval "$(ssh-agent -s)"
загрузка ключа в агента:
$ ssh-add ~/.ssh/id_ed25519     (id_ed25519 - название файла с ключом)
проверка соединения ssh:
ssh -T git@github.com
Hi agolovini! You've successfully authenticated, but GitHub does not provide shell access.  (сообщение если ок)

## Create Instance

You can create an instance with the following code and use `getHtml()` and `getMarkdown()` of the [Editor](https://github.com/nhn/tui.editor).

```bash
const editor = new Editor(options);
```

> See the table below for default options
> More API information can be found in the document
