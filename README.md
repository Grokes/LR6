# Лабораторная работа №6. Система контроля версий
## 4217 Лаптев Кирилл
## Цель лабораторной работы:
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.
## Ход работы
### 1. Настройка клиента Git
![](/Screenshots/GitConfig1.png)
![](/Screenshots/GitConfig2.png)
Так как у меня уже был настроен git клиент, работа была сделана на старых настройках, но также приведён скриншот того, как выглядит настройка клиента
### 2. Клонирование репозитория
![](/Screenshots/clone.png)
### 3. Создание файла в Github и pull изменений в локальный репозиторий
![](/Screenshots/addFile(Github).png)
![](/Screenshots/PullChanges1.png)
![](/Screenshots/PullChanges2.png)
### 4. Просмотр истории коммитов
![](/Screenshots/git%20log.png)
### 5. Последние изменения
![](/Screenshots/LastChanges1(my).png)
Мои изменения
![](/Screenshots/LastChanges2(main).png)
Изменения в Main
![](/Screenshots/LastChanges3(branch1).png)
Изменения в branch1
### 6. Слияние веток и решение конфликта
![](/Screenshots/merge1.png)
![](/Screenshots/merge2.png)
### 7. Удаление побочной ветки
![](/Screenshots/DeleteBranch.png)
### 8. Изменения New file
![](/Screenshots/ChangeFile1.png)
![](/Screenshots/ChangeFile2.png)
### 9. Удаление последнего коммита
![](/Screenshots/ResetChangeFile.png)
### 10. Создание ветки для отчёта
![](/Screenshots/CreateReportBranch.png)
![](/Screenshots/PushReport.png)
### Лог команд
```
git config --global user.name "4217 Laptev Kirill"
git config --global user.email "default1one@gmail.com"
git clone
git pull
git log --graph --all
git show
git show
git show
git merge origin/branch1
git status
cat mergefile.txt
git add .
git status
git commit -m "Разрешён конфликт слияния"
git push origin -d branch1
notepad "New File"
git status
git add .
git commit -m "Внесены изменения в New file"
git reset --hard HEAD~
git checkout -b report
git push
git push --set-upstream origin report
```
