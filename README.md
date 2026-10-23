## Comandi Utili

npm init -y                 -> inizializza un progetto con node/npm

npm install nomelibreria    -> istalla una libreria

npm uninstall nomelibreria  -> disinstalla libreria del progetto


## File del Progetto

Dopo aver inizializzato il progetto,e installata una libreria 
verranno aggiunti/e una cartella chiamata 
        
        "node_modules" -> che conterrà le librerie del progetto
        
        un file chiamato "package.json" -> che sarà il file "ricetta"
        della nostra applicazione, dove saranno elencati/e 
        le librerie( o dipendenze ) del progetto


## Comandi da eseguire per fixare comportamenti anomali

npm install -> reinstalla tutte le librerie  
quindi, se volessi installare un progetto preso da github,prima o scarico,
poi lancero' il comando npm install per riscaricare tutte le librerie che servono al progetto per funzionare.


## Prima di pushare un progetto su Github

creare un file chiamato .gitignore che NON pusherà la cartela delle librerie locali installate sul pc NODE_MODULES, altrimenti la repo avrà dimensioni eccessive per github ( e anche per convenzione )

questo sia per NODE_MODULES ma soprattutto per il file che conterrà le vostre password

del file .env  ->>>> IMPORTANTISSIMO


## Eliminare npm da un progetto 

Per riportare il progetto allo stato iniziale,

si può cancellare la cartella NODE_MODULES, e il file package-lock.json 

