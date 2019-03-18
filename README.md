# TriisaAndroid
Mobiilirakenduste arendamine (IFI6224.DT) Kodunetöö1


Seadistamine

	Projekti seadistamiseks kas:
	
	a)  Allalaadimine Githubist
		1) Laadige alla repo .zip failina
		2) pakkige alla laetud .zip fail lahti
		3) avage Android studio ning File->Open otsige lahti pakitud kaust
	
	b) Kloonimine Githubist
		1) Avage Android studio
		2) Kas ava menüüst valige "Check out project from Version Control -> Git" või kui teine projekt on juba lahti siis "File->New->Project From Version Control -> Git"
		3) Ning URL lahtrisse lisage selle repositooriumi link
		
Arvamus Juhendist

	Kasutasin projekti valmistamiseks kolme juhendit:
	https://www.androidhive.info/2015/09/android-material-design-working-with-tabs/
	https://www.android-examples.com/android-create-stopwatch-example-tutorial-in-android-studio/
	http://www.androidtutorialshub.com/android-count-down-timer-tutorial/
	
	Kuna kirjutasin android rakendust esimest korda, õppisin kõik androidiga seotud loogika juhenditest. Java ja xml teadmised olid eelnevalt.
	
	Juhend kaartide(ingl k. tabs) kasutamisele oli väga kasulik. Andis hea ja lihtsa näite kaartide kasutusele võtmisest kasutades fragmente. Probleeme juhendiga ei tekkinud.
	
	Juhend stopperile küll töötas, aga stopperi loogikas oli palju vigu. Samuti keskendus juhend stopperile kui activitile, kuid stopperi rakendus võiks pigem olla lahendatud kui foreground service, töötades ka ilma kasutaja mõjuta ning nähtaval ka teavitus ribal. Kuid juhendit jälgides sai stopperi funktsionaalsus teostatud. 
	
	Taimeri juhend oli kõige detailsem juhend, seletades lahti kõik osad koodist nii juhendis kui koodis endas, kasutades komentaare. Kood oli hästi kirjutatud ja jälgis häid programeerimis tavasid. 
	
Muudatused seoses SDK versiooniga

	Muutuseid seoses SDK versiooni muutustega ei täheldanud.
	
Muutatused rakenduse terviklikumaks muutmise nimel.

	Stopperi loogikas oli vaja parandusi teha. Mure kohtadeks olid nuppude mitme kordne vajutamine, mis lõhkus stopperi tööd, ning "Save lap" nupu funktsionaalsus, mis salvestas hetkese aja, mitte hetkese ringi aja.
	Veel sai stopperi ja taimer funktsionaalsus tõstetud fragmentide sisse, tahtes muudatusi mõnes koodi jupis, näiteks contexti pärimisel, kuna fragmendi sees käib see erinevalt activitist.
	Taimeri juures sai muudetud värvi valikuid, et need läheksid kokku ka eelnevalt valminud kujundustega.

![alt text](https://github.com/TTriisa/TriisaAndroid/blob/master/screenshot1.png)
![alt text](https://github.com/TTriisa/TriisaAndroid/blob/master/screenshot2.png)
