**Labs**
========

1. Створив репозиторій на github. На локальному ПК змінив README.md, та закомітив його до репозиторію.

misha@misha-VirtualBox:~/it22/Horishniy$ git add README.md
misha@misha-VirtualBox:~/it22/Horishniy$ git status
На гілці master
Зміни, що мають бути збережені в коміті
  (використовуйте "git reset HEAD <file>..." щоб прибрати з буфера)

	змінено:       README.md

misha@misha-VirtualBox:~/it22/Horishniy$ git commit -m "lab_1: my first commit"
[master 84bf408] lab_1: my first commit
 1 file changed, 4 insertions(+), 2 deletions(-)


2. Переглянув під яким хешем був створений попередній коміт.

misha@misha-VirtualBox:~/it22/Horishniy$ git log
commit 84bf40885b4ef2e36f62760e59b7bed716f23524 (HEAD -> master)
Author: Misha ENSMike <gorishniy98@gmail.com>
Date:   Mon Dec 2 23:13:32 2019 +0200

    lab_1: my first commit


3. За допомогою команди git checkout -b second_bransch створив нову гілку і переключився на неї.
4. Створив та виконав pull request на злиття (merge).
5. Зробив зміни в веб версії, та ввів команду git pull, щоб побачити зміни на ПК. 


