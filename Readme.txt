https://practicum.yandex.ru/trainer/git-basics/lesson/c6b9607c-e8bc-4446-89f9-c74522c3492f/
изучение разметки для README файла

cd - переход по директориям 
ls - просмотр элементов находящихся в директории
pwd - директория в которой находимся в данный момент 
ls -a - просмотр скрытых файлов в директории
touch - создает файл внутри директории в которой находимся в данный момент (желательно указывать расширение файла)
mkdir - создает папку внутри директории в которой находимся 
cp - копирование файла из одной директории в другую. Пример(cp имя файла.расширение файла путь к директории/)
mv - перещение файлов из одной директории в другую. Пример(mv имя файла.расширение файла путь к директории/)
cat - чтение файлов только текстового формата
rm - удаление файлов 
rmdir - удаление директории в которой ничего не находится 
rm -r - удаление директории в которой находятся файлы или другие директории
С помощью && можно выполнить несколько команд сразу — одну за другой. Пример (mkdir second-project && cd second-project && touch index.html style.css)
Вывести содержимое файла конфигурации Git той же командой git config с флагом --list
git init - команда для создания гит в диретории в которой находимся в данный момент 
rm -rf .git - команда для удаления гит в директории
ключ -r - (от англ. recursive — «рекурсивно») позволяет удалять папки вместе с их содержимым
ключ -f - позволяет избавиться от лишних вопросов
git status - команда для проверки статуса или состояния репозитория
git add - команда которая позволяет подготовить файл к сохранению.
git add --all Ключ --all - позволяет подготовить все файлы сразу
ключ .(точка) - позволяет подготовить целиком папку со всеми файлами
git commit - создание коммита
git commit -m ключ -m - используется для добавления сообщения в данный коммит нужен для описания изменений в данной версии
git log - команда для просмотра историй коммитов
ls -a ~/.ssh - команда для проверки ключа SSH
ssh-keygen -t ed25519 -C "mail" - команда для генерации SSH ключа
ssh -T git@github.com - команда для проверки ключа SSH
git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git - команда для связывания локального и удаленного репозитория
git remote -v - команда для проверки связанности репозиториев
git push - команда для передачи файлов на удаленный сервер (Git-hub)
git push -u main (master)- команда используется когда файлы передаются в первый раз
