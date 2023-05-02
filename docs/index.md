# Документация

## Создание проекта 

1. Создать папку
2. Инициализировать проект

```bash
npm init
```

3. Установить cypress

```bash
npm install cypress
```

4. Инициализировать git. Создать файл .gitignore и добавить туда node_modules

```bash
git init
```

5. Создать новый проект в удаленном репозитории (гитлаб, гитхаб), следовать инструкциям по привязке локального репозитория к нему

```bash
git remote add origin https://gitlab.goodsteam.tech/arutyunova/merchant-test-e2e.git
```

6. Закоммитить изменения и запушить их

```bash
git add .
git commit -m "Сообщение коммита"
git push
```
(если были изменения на удаленке, то git pull)
## Шпора 
ctrl+c - остановить процесс
npm run test:open - запустить команду (cypress)
