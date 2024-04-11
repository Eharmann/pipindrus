1. Сначала склонируйте репозиторий на свой локальный компьютер:

Bash

git clone https://github.com/Eharmann/pipindrus.git

2. Перейдите в директорию, куда был склонирован репозиторий:

Bash

cd pipindrus

3. Создайте файл `Hello.txt` в данной директории. Можно сделать это следующей командой:

Bash

echo "Hello, World!" > Hello.txt

4. Добавьте файл `Hello.txt` в индекс Git:

Bash

git add Hello.txt

5. Зафиксируйте изменения с комментарием:

Bash

git commit -m "Добавлен файл Hello.txt"

6. Загрузите изменения в репозиторий:

Bash

git push origin master
