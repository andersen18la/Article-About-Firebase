# Article-About-Firebase

## Lidt om Firebase:
Jeg har valgt at skrive om Firebase, da vi i vores eksamensprojekt benytter os af platformen. Firebase er en mobil og web udviklings platform, som man kan anvende til at lagre data i ”Skyen”. Bedre forklaret er det en dynamisk og skalerbar database som er No SQL, hvilket betyder at det er en database som er meget brugervenlig og nem at sætte sig ind i og bruge. No SQL betyder at man ikke skal være bekendt med SQL når man b.la. skal indsætte data eller hive data ud af databasen. I SQL-databaser skal man sætte sig ind i statements og vide hvordan en ”Query” skal lyde for at få den rigtige data ud som man vil have den.

Fordelen ved Firebase er at Google har lavet en grundstruktur eller rettere sagt et skelet som man kan bruge som fundament og heraf bygge sin egen database ovenpå. Dvs. ved at bruge Firebase har Google givet adgang til at man kan bruge en masse funktionalitet. En af de store fordele ved databasen er dens evne til at synkroniserer dataene så alle enheder hurtig kommer up-to-date. Firebase har som sagt en masse forskellige features som man benytter når man sætter sin backend op med Firebase. 

Attraktive features som gør at man kan holde øje med hvor mange brugere der har brugt databasen og forskellige meningsmålinger så man hele tiden kan optimere oplevelsen for brugerne at bruge ens app hvis det er det man har udviklet. 
Firebase er ejet af Google som har enorme og robuste serversystemer som sjældent har nedbrud, så det er en af de væsentlige ting du ikke bør bekymre dig om. Firebase er nem at bruge hvad enten du har én eller 100 bruger. Firebase bruges af et bredt antal udviklere, da det både understøttes af Android, IOS og Web. 

## Opsætning af Firebase i Android Studio:
 
Lav et projekt
 - Empty Activity. 
Når du er inde i Android Studio: 
- Tools
- Firebase 
- Realtime Database 
- Save and Retrieve Data. 


Når du har fået Firebase menuen frem følger du blot – step by step. 
Inden du følger guiden, skal du gå ind https://firebase.google.com/ 
Gå til konsol
Herefter skal du trykke ”Add project”. 
Efterfølgende har du oprettet en Realtime Database og er klar til at sætte data i den. 
Nu Vælger du ”Database” i dashboardet i højre side af skærmen, som vist på billedet. Så kommer du ind på en side hvor du vælger ”Get started” under Realtime Database. 
Efterfølgende følger du guiden til du er færdig, hvor du både kommer igennem at skrive til databasen og hive data ud af databasen.

## Min løsning:
Jeg har nu sat et projekt og vist hvordan det kan gøres. I vores eksamensprojekt har vi gjort det anderledes til at starte med. Vi har selv skrevet en ”Admin” og ”Customer” ind i Firebase så vi har noget data vi kunne teste med. Der er flere måder at gribe det an på, og det kommer selvfølgelig an på den enkelte situation hvordan det passer én. 

I denne løsning har jeg fulgt måden Android Studios guide går igennem opsætningen af Firebase. Personligt synes jeg selv det er hurtigere og nemmere lige at sætte noget data ind manuelt i Firebase, i stedet for at man skal ”kode” noget for at få data ind. Til andre ville jeg foreslå at sætte data manuelt ind i databasen, da det er hurtigere og man får opsætningen af data præcis som vil have det. 

Jeg kan godt lide at Android Studio har en indbygget knap til Firebase, så det er ekstremt nemt at opsætte en Database, og hvis man bare følger guiden, kan det ikke gå helt galt. Det der gør det nemt er at guiden er lavet i punktform, så det er lige ud af landevejen. Jeg kan godt li at Firebase er NoSQL, det gør det hele nemmere, og man støder ikke ind i alle de klassiske SQL-problemer som PrimaryKey, ForeignKey og Constraints. 

Jeg synes det er fedt at når man opretter Firebase og indsætter koden fra guiden i Android Studio, så kan man også ”add ValueEventListener” og den har 2 metoder indbygget, hvor den ene metode hedder ”onDataChange” så hele tiden holder øje med om der sker noget i Databasen. Det ville her være aktuelt at holde øje med aktivitet i Database, og opbygge DB så man får en besked når f.eks en bruger har oprettet et kæledyr hvis det er det ideen er. 


## Evaluering af min løsning:
Jeg startede godt ud med at få startet Android Studio op og oprettet et nyt projekt, men da jeg skulle sætte Firebase op fra Android Studio havde jeg et problem, jeg blev nægtet adgang, et problem som også opstod under processen da vi til eksamensprojektet skulle oprette Databasen i et nyt projekt. Jeg genstartede AS (Android Studio) og det virkede ikke. Jeg slettede projektet og lavede et nyt projekt og prøvede så at ”Connect to Firebase” og så fik jeg adgang. 

## Konklusion:
Jeg kan konkludere ud fra min løsning at jeg har lært hvordan man sætter Firebase Database op, da jeg ikke har gjort det før. Jeg kan også konkludere at Firebase er et nemt framework som er nemt at implementere i dit system, hvilket er hvad vi gør fordi vi vil prøve noget andet end SQL. 
Jeg vil klart anbefale andre at bruge samme løsning, da det er nemt at opsætte og det er forholdsvis ligetil at finde information omkring Firebase og hvis man går i stå, er det også muligt at opsøge dit problem. 
Med denne artikel kan jeg til sidst konkludere at Firebase er fantastisk framework som mange tusinde mennesker benytter sig af og det gør vi også nu. 


