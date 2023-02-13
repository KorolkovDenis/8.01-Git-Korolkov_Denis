# Домашнее задание к занятию "`8.01-Git`" - `Корольков Денис`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`Это ссылка на первый коммит:`

1. [коммит к первому заданию](https://github.com/KorolkovDenis/8.01-Git-Korolkov_Denis/commit/0220beaea039b1063f8ec9a30a93b0d128dc0c55)

```

Последовательность выполнения:

Устанавливаем Git на пк:  
sudo apt install git  

Создал директорию для моего проекта и перешел в неё:   
mkdir git  
сd ./git  
Клонируем с Github наш репозиторий на локальный пк:  
git clone https://github.com/KorolkovDenis/8.01-Git-Korolkov_Denis.git  
Перейдем в каталог: 8.01-Git-Korolkov_Denis  
Произведем первоначальную настройку Git:  
git config --global user.name "Denis_Korolkov"  
git config --global user.email "dvkorolkov@mail.ru"  

Редактирую файл README.md  
# 8.01-Git-Korolkov_Denis  
# First commit, Git, introduction to the program  

git status  
git diff  
git status  
git diff --staged  
git add README.md  
git status  
git diff  
git status  
git diff --staged  
git status  
git commit -m "First commit, Git, introduction to the program"  
git push origin main  


```

---  

### Задание 2  

`Ссылка на коммит:`

1. [Коммит ко второму заданию](https://github.com/KorolkovDenis/8.01-Git-Korolkov_Denis/commit/f4d4417c4201038d3fb85aba90d486d8cdd92c68)


```

Последовательность выполнения:

Создаем файл .gitignore:  
sudo nano .gitignore  

Прописываем следующее:  
*.рус  
cache/*  

Добавляем изменения в ветку:

git status  
git add .gitignore  
git status  
git commit -m "Second commit, Added .gitignore"  
git push  

```

---

### Задание 3

`Ссылка на граф коммитов:`

1. [Третье задание](https://github.com/KorolkovDenis/8.01-Git-Korolkov_Denis/network)


---
## Дополнительные задания (со звездочкой*)

Эти задания дополнительные (не обязательные к выполнению) и никак не повлияют на получение вами зачета по этому домашнему заданию. Вы можете их выполнить, если хотите глубже и/или шире разобраться в материале.

`Ссылка на граф коммитов:`

1. [Дополнительное задание](https://github.com/KorolkovDenis/8.01-Git-Korolkov_Denis/network)

## Ссылка на мою работу в Google:

[Моя работа по Git](https://docs.google.com/document/d/11-J8s7wO5frhF2A-w2kR6wIzi2I-aM1O/edit?usp=share_link&ouid=104113173630640462528&rtpof=true&sd=true)
