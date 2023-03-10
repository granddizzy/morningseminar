# Мой конспект по работе с git'ом.

* *git init* - команда, инициализирующая репозиторий в текущей директории;
* *git status* - команда, отображающая текущее состояние репозитория;
* *git add* -  команда добавляет содержимое рабочего каталога для последующего коммита;
* *git commit* - команда берёт все данные, подготовленные для коммита, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок;
* *git commit --amend* - команда для изменения последнего коммита (можно использовать для изменения коментария без изменения кода); 
* *git log* - команда используется для просмотра истории коммитов; 
* *git checkout* - команда позволяет перемещаться между ветками;
* *git checkout master* - команда переключает в ветку master;
* *git diff* - команда, показывающая изменения в репозитории по сравнению с последним коммитом;
* *git show* - команда, показывающая изменения зафиксированные в последнем коммите;
* *git branch* - показывает список веток;
* *git branch <имя ветки>* - команда создает новую ветку;
* *git checkout -b name* - команда создает новую ветку и переходит в нее;

# Этапы работы с репозиторием
* *Разработка. Работа с данными в редакторе кода.*
* *Сохранение данных.*
* *Актуализация. Добавление файлов для последующего коммита. Команда git add.*
* *Фиксация. Создание коммита. Команда git commit*