![Вставка текста](Хандэ.jpg)
## **Инструкция по Git и GitHub**

### **1. Что такое Git**
*Git - программа для контроля версий, создаваемых файлов, создаёт репозитории*
### **2. Как проверить установку программы**
*Для проверки установки программы Git необходимо открыть терминал и набрать команду git --version*
### **3. Подготовка репозитория**
*После установки автосохранения файла необходимо создать репозиторий командой git init*
### **4. Создание коммитов**
#### ***Git add**
*Для добавления изменений сначала нужно ввести команду git add file_name*
#### ***Просмотр репозитория**
*Чтобы посмотреть состояние репозитория, надо ввести команду git status*
#### ***Просмотр изменений**
*Чтобы посмотреть изменения, надо набрать команду git diff
#### ***Создание коммитов**
*Чтобы сохранить версию с последними изменениями, надо ввести команду git commit -m "Записать пояснение к тому, что сделано"*
#### ***Просмотр коммитов**
*Просмотреть все изменения (версии файла) можно при вводе команды git log*
#### ***Переключение между коммитами**
*Ввести git checkout, чтобы переключаться между сохранениями*
#### ***Переключение на ведущую ветку**
*Ввести команду git checkout master или git switch master*
### **5. Игнорирование файлов**
Для того, чтобы исключить из отслеживания в репозитории определённые файлы и папки, необходимо создать файл ***.gitignore*** и записать в него названия или шаблоны игнорируемых файлов.
### **5. Создание веток**
По умолчанию имя основной ветки в Git - master.
Создать ветку можно командами git branch name_branch или git branch -b name_branch
<<<<<<< HEAD
### **6. Короткие команды**
Командой git checkout -b NameBranch можно сразу создать новую ветку и перейти на неё.
Командой git log --oneline --graph можно посмотреть все коммиты на всех ветках, записанные кратко.
Командой git commit -am "Факт" можно сразу добавить отслеживание и сохранить коммит.
### **7. Исправление последнего коммита**
Если неправильно записали последний коммит, можно перезаписать его командой git commit --amend -am "Исправление"
### **8. Удаление веток после слияния**
После слияния ненужную  для работы ветку можно удалить командой git branch -d NameBranch
### **9. Слияние веток**
Необходимо сначала перейти на основную ветку master и затем командой git merge namebranch слить в неё нужную ветку
### **10. Репозиторий для pull request**
#### **10.1. Начало работы для создания клона чужого репозитория**
Сначала в своём аккаунте на GitHub создать копию репозитория **"AndreyBulgakov19/SCV_Git_PR"** с помощью кнопки **"Fork"**.
Затем клонировать копию репозитория на локальный компьютер и создать новую ветку (Создала ветку Edits).
После добавить файл с инструкцией в новую ветку и дополнить её разделами по работе с удалёнными репозиториями, pull request.
#### **10.2. Команды для использования**
* git clone - помогает клонировать проект из моего аккаунта GitHub в локальную программу VSC
* git push - подтягивает изменения, сделанные в локальной версии, на аккаунт в GitHub
* git pull - подтягивает версию из моего аккаунта GitHub в локальную версию на компьютере и сливает ветки
#### **10.3. Подготовка изменений к отправке**
* Зафиксировать изменения (коммиты)
* Отправить изменения на GitHub (вначале команда git push --set-upstream origin NewBranch, затем можно только git push)
#### **10.4. Выполнение **Pull request** на сайте GitHub**
*  выполнить .
---
