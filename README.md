# Aircraft-Company
БД авіабудівного підприємства

Структурно підприємство розбите на цеху, які в свою чергу діляться на ділянки. Вироби, що випускаються підприємства - літаки (цивільні, транспортні, військові), планери, вертольоти, дельтаплани, ракети (артилерійські, авіаційні, військово-морські), інші вироби. Кожна категорія виробів має специфічні, притаманні лише їй атрибути. Наприклад, для літаків це число двигунів, для ракети - потужність заряду тощо. По кожній категорії виробів може збиратися кілька видів виробів. Кожній категорії інженерно-технічного персоналу (інженери, технологи, техніки) і робочих (збирачі, токарі, слюсарі, зварювальники і т.д.) також притаманні характерні тільки для цієї групи атрибути. Робочі об'єднується в бригади, якими керують бригадири. Бригадири обираються з числа робітників, майстрів.
Кожен виріб збирається в своєму цеху (в цеху може збиратися кілька видів виробів) і в процесі виготовлення проходить певний цикл робіт, переміщаючись з однієї ділянки на іншу. Всі роботи по збірці конкретного виробу на певній ділянці виконує одна бригада робітників, при цьому на ділянці може працювати кілька бригад. Очолює роботу на ділянці начальник ділянки, в підпорядкуванні якого знаходиться кілька майстрів. Різні вироби можуть проходити одні й ті ж цикли робіт на одних і тих же ділянках цеху.
Зібране виріб проходить серію випробувань в випробувальних лабораторіях (полігонах). Випробувальні лабораторії можуть обслуговувати кілька цехів, в свою чергу цеху користуються, можливо, кількома випробувальними лабораторіями. Випробування проводяться випробувачами на обладнанні випробувальної лабораторії, при цьому при випробуванні конкретного виробу в лабораторії можуть бути задіяні різні види обладнання.
Ведеться облік руху кадрів і облік продукції, що випускається. 
Види запитів в інформаційній системі: 
1.	Отримати перелік видів виробів окремої категорії і в цілому, що збираються зазначеним цехом або підприємством. 
2.	Отримати число і перелік виробів окремої категорії і в цілому, зібраних зазначеним цехом, ділянкою, підприємством в цілому за певний відрізок часу. 
3.	Отримати дані про кадровий склад цеху, підприємства в цілому і по зазначеним категоріям інженерно-технічного персоналу і робітників. 
4.	Отримати число і перелік ділянок зазначеного цеху, підприємства в цілому і їх начальників. 
5.	Отримати перелік робіт, які проходить вказане виріб. 
6.	Отримати складу бригад вказаної ділянки, цеху. 
7.	Отримати список майстрів вказаної ділянки, цеху. 
8.	Отримати перелік виробів окремої категорії і в цілому, що збираються зараз зазначеною ділянкою, цехом, підприємством. 
9.	Отримати склад бригад, які беруть участь у створенні зазначеного вироби. 
10.	Отримати перелік випробувальних лабораторій, що беруть участь у випробуваннях деякого конкретного виробу. 
11.	Отримати перелік виробів окремої категорії і в цілому, що проходили випробування в зазначеній лабораторії за певний період. 
12.	Отримати список випробувачів, які беруть участь у випробуваннях зазначеного вироби, виробів окремої категорії і в цілому в деякій лабораторії за певний період. 
13.	Отримати склад обладнання, яке використовувалося при випробуванні зазначеного вироби, виробів окремої категорії і в цілому в деякій лабораторії за певний період. 
14.	Отримати число і перелік виробів окремої категорії і в цілому, які збираються зазначеним цехом, ділянкою, підприємством в цілому в даний час.
