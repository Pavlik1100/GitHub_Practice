# HW_2-Practice_GitHub
GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
```sh
git branch Postman
git branch Jmeter
git branch CheckList
git branch Bag_Reports
git branch SQL
git branch Charles
git branch Mobile_Testing
```

2. Запушить все ветки на внешний репозиторий
```sh
git push origin -all
```
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
```sh
git checkout Bag_Reports
touch bag_1.txt
vim bag_1.txt
```
`press "i" for iinsert`  
```sh
id:

title:

steps:

AR:

ER:

severity:
```  
`press "esc", pres after ":wq", press "enter"`  
  
4. Запушить структуру багрепорта на внешний репозиторий
```sh
git add .
git commit -m "create bag_1.txt"
git push origin bag_reports
```
6. Вмержить ветку Bag Reports в Main
7. Запушить main на внешний репозиторий.
8. В ветке CheckLists набросать структуру чек листа.
9. Запушить структуру на внешний репозиторий
10. На внешнем репозитории сделать Pull Request ветки CheckLists в main
11. Синхронизировать Внешнюю и Локальную ветки Main
