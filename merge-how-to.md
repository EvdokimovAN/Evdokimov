Получить изменения с сервера, слить ветки, сделать ещё один комит

перейти в свой репозиторий
получить с сервера изменения во всех ветках: git fetch
посмотреть все ветки: git branch --all
переключиться в ветку друга, чтобы создать её локально: git checkout surname
посмотреть все ветки: git branch --all
переключиться в основную ветку: git checkout master
обьединить ветку друга с основной веткой: git merge surname
отправить изменения на сервер: git push
посмотреть историю репозиория: git log
добавить в репозиторий файл merge-how-to.md
описать на языке разметки markdown инструкции для себя:
как получить ветку с сервера
как слиять одну ветку с другой
что сделать после слияния веток
проверить статус репозитория: git status
подготовить новый файл для комита: git add .
проверить статус репозитория: git status
сделать комит: git commit -m “merge instruction”
отправить изменения на сервер: git push