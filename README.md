# Git-commands

### Клонування репозиторію:
```bash
# клонировать удаленный репозиторий в одноименную директорию
git clone https://github.com/cyberspacedk/Git-commands.git    

#клонировать удаленный репозиторий в директорию «FolderName»
git clone https://github.com/cyberspacedk/Git-commands.git FolderName 

#клонировать репозиторий в текущую директорию
git clone https://github.com:nicothin/web-design.git.
```


```bash
git branch "branchName"         #створює гілку з назвою "branchName"
git checkout "branchName"       #переходить на гілку з назвою "branchName"
git checkout -b "branchName"    #створюємо гілку з назвою "branchName" і переходимо на неї
git add .                       #зберігаємо зміни в файлах
git commit -m "commit message"  #підписуємо збереженні зміни в файлах
git commit -am "commit message" #підписуємо збереженні зміни в файлах та зберігаємо зміни в файлах
git push                        #відправляємо зміни на сайт github
git pull                        #отримуємо останні зміни з сайту github
git status                      #показуємо статус проекту
git branch                      #показуємо список гілок в проекті
git branch -r                   #показуємо список гілок на сайті github
git branch -a                   #показуємо список гілок на компютері та на сайті github
git fetch                       #отримуємо зміни з сайту github
git stash                       #зберігаємо не збережені зміни в файлах і кладемо їх в буфер обміну
git stash apply                 #вставляємо збережені зміни з буфера обміну
git merge "banchName"           #зливаємо гілку з назвою "branchName" в поточну гілку
git merge --abort               #відміняємо зливання гілок
git branch -d branchName        #видаляє гілку локально з проекту
git push origin --delete name   #видаляє гілку з сайту github
git diff                        #показує відрізки рядків між двома версіями файлу (між двома комітами)
git log                         #показує історію комітів

#Для того щоб вийти з режиму перегляду комітів (git log) використовуйте клавішу q
```
