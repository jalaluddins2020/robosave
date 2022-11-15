
# Welcome to robosave
```
A school financial technology project to "disrupt the bank". Invest as your spend.
```
>**Tech Stack**
	1. HTML
	2. CSS - Chakra UI (Component Library)
	3. React 
	4. Flask (Python)
	5. Docker (Container)

# Backend

**WAMP / MySQL**

Start WAMP
From `robosave\backend\services`, import into the database:
```
1. customer\docker-entrypoint-initdb.d\init.sql
2. roundup\docker-entrypoint-initdb.d\init.sql
3. transaction\docker-entrypoint-initdb.d\init.sql
```
**Docker**

Start Docker Desktop
```
cd backend
docker-compose build
docker-compose up
```
**Services Built and Run**
![image](https://user-images.githubusercontent.com/93022626/201923381-de2e2a4a-3734-4499-8da7-28ee232bfd5e.png)

# Frontend
```
cd frontend/robosave
npm install # if first time installation
npm start
```
**Landing Page**
![image](https://user-images.githubusercontent.com/93022626/201923564-79bf2a5f-11d4-4b5f-b5ff-b4dd83ed5a5d.png)

**Dashboard**
![image](https://user-images.githubusercontent.com/93022626/201924024-05c12642-dad7-4906-ac49-84bd7fffb4db.png)

**Payment**
![image](https://user-images.githubusercontent.com/93022626/201924308-35f934f0-e09f-4595-afc9-f345031801e7.png)

**Invest**
![image](https://user-images.githubusercontent.com/93022626/201924093-dae104c2-8555-4685-aab2-d7224dbcc868.png)

**Financial News**
![image](https://user-images.githubusercontent.com/93022626/201924182-c47a82c4-964b-4a79-b97a-ffabc5778a08.png)


### Project By
> G2T4
> - JALALUDDIN BIN SELAMAT
> - MUHAMMAD SYAFIQ BIN SHARIFFUDIN
> - NICKSON NG JIA RONG
> - TAY HUILIN
> - YEO JING YI
