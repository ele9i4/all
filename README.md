# all

All - общий репозиторий
- master - сборка списка страниц в репозитории
- gh-pages - собранный список
  - папки - submodules
- воркфлоу
  - при пуше в мастер
    - собрать список сабмодулей
    - запустить билд
    - обновить файлы в ветке gh-pages
  - при обновлении сабмодулей
    - обновить файлы в ветке gh-pages
    - отслеживать изменения в сабмодулях?

Репозитории страниц:
- master - сборка страницы\приложения
- gh-pages - собранная страница\приложение
- воркфлоу:
  - при пуше
    - запустить билд
    - скопировать билд в ветку gh-pages
    - обновить общий репозиторий?