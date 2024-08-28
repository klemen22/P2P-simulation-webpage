(Koda je bila prilagojena tako da dela vse na local host)

Key notes:
	1. postavite "Flegar" folder znotraj "xampp/htdocs/"
	2. nalozite NodeJS in preverite ce najde vse module ki so vnaprej prilozeni (v nasprotnem primeru jih nalozite z "npm install")
	3. import-ite project.sql v MySQL (!! pred import-om poimenujte nov database v katerega nameravate import-ati: "project" !!)
	4. pozenite server_api.js z NodeJS
	(kodi server.js in scan.py nista potrebni za osnovno delovanje strani, saj je njun namen dinamicno posodabljanje MySQL)
	(v prilozenem database-u imate shranjene zajete naslove skozi razlicne dni ter 2 account-a)
	
Test account:
	email: test.test@gmail.com
	password: password
	
Video posnetek (quick tutorial): https://youtu.be/PMUvxiSWx5E

(Dodatno: Kodo server.js lahko pozenete preko NodeJS s ukazom "node server.js" ali "pm2 start server.js". Sledeca koda bere capture.json in vpisuje vrednosti v MySQL database. Ob zagonu bi morala koda takoj naredi vnos v database potem pa naredi vsak sledeci vnos na 12h.)
(capture.json se posodablja s python skripto scan.py)
