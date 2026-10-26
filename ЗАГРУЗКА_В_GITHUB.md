# Как загрузить через браузер

1. Распакуйте zip. GitHub сам архивы не распаковывает.
2. Откройте репозиторий, нажмите Add file > Upload files.
3. Выделите ВСЁ содержимое папки vsem-mirom (папки Assets, Tests, docs и файлы README.md, CLAUDE.md и т.д.) и перетащите в окно. Саму папку vsem-mirom перетаскивать не нужно. Нажмите Commit changes.
4. Файлы gitignore.txt и gitattributes.txt нужно превратить в скрытые вручную, браузер их с точкой не примет:
   - Add file > Create new file
   - В поле имени введите .gitignore, вставьте содержимое из gitignore.txt, Commit.
   - Повторите для .gitattributes и gitattributes.txt.
5. Файлы gitignore.txt и gitattributes.txt из репозитория можно удалить.
