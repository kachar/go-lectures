Лекции към курса "Програмиране с Go"
======

Презентациите се пишат с [present](https://godoc.org/golang.org/x/tools/present) tool-а на Go.

Всяка презентация представлява един `xx-name_of_the_lecture.slide` файл, а кодът към нея се намира в собствена папка в `code/`.

Инсталация
-----

	go get -u golang.org/x/tools/present

Употреба
------

От текущата директория изпълнявате:

    present -base="assets"

http://127.0.0.1:3999/


Упътвания за принос
------

За да допринесете по някакъв начин към тези материали, е необходимо първо да си подкарате локално `present`. След като промените някоя лекция, трябва да я прегледате в браузър, за да се уверите, че промените изглеждат така, както сте очаквали.
Препоръчително е да правите pull request-и в съответен branch, например `08-fix-typos` (за поправка на правописни грешки в презентация 8).
