# Kas ir FFL?
- Futbols - tavs uzdevums ir izkārtot spēlētājus laukumā pirms spēles un baudīt futbolu.
- Turnīri - regulārais turnīrs ar sezonas beigās trofejas iegūšanu vai izkrišanu uz zemāku līgu, dažādi kausi ar labām naudas prēmijām, draudzības spēles vai pat piedalīšanās Pasaules čempionātā, vadot kādu no FFL izlasēm.
- Līgumi - pārslēgt līgumus, izpirkt spēlētājus un varbūt pat pārvilināt spēlētājus ar labāku algu uz savu komandu.
- Transfēri - izsolīt, mainīt un iegūt draftā jaunus spēlētājus.
- Nauda - sabalansēt komandas ienākumus un izdevumus.
- Treniņi - nodrošināt spēlētājiem treniņus.
- Partnerkomandas - kļūt par vadītāju papildus komandai.
- Statistikas - tabulas, gūtie vārti dažādos turnīros un finanšu reporti, FFL ir par cipariem.
- Discord - diskusijās par FFL, futbolu un dzīvi. Iespējams pat iegūt nepiekāpīgu sāncensi laukumā un preses konferences Discord kanālos.
- Patreon - FFL tehniskā risinājuma un attīstības atbalsts, dažādi papildus bonusi spēlē.

## Kā spēlēt?
- https://fflisback.lv/
- Iegūsti uzaicinājumu FFL is back Discord kanālā

## 1. Komanda
1. Komanda ir FFL sastāvdaļa. Komandai var būt ar vadītāju, kas nosaka komandas spēlētāju sastāvu, izkārtojumus spēlei un atbildīgs par komandas finansēm, rezultātiem un labo slavu. Komanda var būt bez vadītāja un tad to iespēju robežās vada FFL kods. 
2. Komandai ir nosaukums, logo, komandas saīsinājums (trīs burtu kombinācija) un pārstāvētā valsts.
3. Partnerkomanda ir komanda bez vadītāja, kuru vada kāda cita komanda.
4. Pamatkomanda ir vadītāja komanda, kurai piešķirta ir partnerkomanda. 
5. Partnerkomanda nevar piedalīties tieši vai netieši transfēros ar pamatkomandu. 
6. Partnerkomandu var iegūt jebkura komanda ar vadītāju, piesakoties pēc pirmās rokas principa uz komandu bez vadītāja un bez pamatkomandas. 
7. Partnerkomandu var zaudēt ar Valdes lēmumu par noteikumu pārkāpšanu vai citādiem pārkāpumiem.
8. Komandas vadītājs vienu reizi sezonā var mainīt nosaukumu, logo un pārstāvēto valsti, izmantojot 2 bumbas. Komandas nosaukumu var mainīt uz futbolā esošas komandas nosaukumu. Komandas saīsinājumu nevar mainīt. 

## 2. Kods
1. FFL spēles, spēlētāju attīstību un citus FFL notikumus pārvalda FFL kods.
2. FFL kods ir gadījuma skaitļa ģeneratora ietekmēts un FFL kodam vienmēr ir taisnība.
3. Izmaiņas FFL kodā tiek izziņotas “gm_mustknow” kanālā - https://discord.com/channels/794982283442126899/796328032658784298

## 3. Pārvalde
1. FFL pārvalda FFL vadītājs.
2. FFL vadītājs drīst vienpersoniski pieņemt lēmumus par FFL koda izmaiņām un attīstību.
3. FFL vadītāja pārziņā ir FFL kods.
4. FFL vadītājs pieņem lēmumus par transfēru apstiprināšanu.
5. FFL komandu vadītāji drīkst veidot citas pārvaldes struktūras un saskaņojot ar FFL vadītāju tās realizēt.

## 4. FFL pārvaldes struktūras
1. Disciplinārā komisija
	1. Veic papildus spēlētāju diskvalificēšanu pēc spēlētāju savainojumiem spēles laikā. Komisijas noteikumus skatīties Discord kanālā https://discord.com/channels/794982283442126899/1005101248309116928
2. FFL valde
	1. Veic atbalsta funkcijas FFL vadītājam strīdīgu lēmumu pieņemšanā.
3. Komandas
	1. Jebkurš komandas vadītājs var ieteikt izmaiņas FFL kodā, noteikumos un jebkurā citā jautājumā.

## 5. Spēlētājs
1. Spēlētājam ir fiziskie raksturlielumi - vecums, spēles skili, agresivitāte un abl daudzums, finanšu raksturlielumi - vērība, pašreizējā alga, mainīgā alga, līgums un līguma termiņš, vispārīgie raksturlielumi - vārds, nacionalitāte, dzimšanas diena.
2. Spēlētājs var būt noslēdzis līgumu ar komandu, atrasties nespēlējošo spēlētāju sarakstā (old) vai drīz spēlējošo spēlētāju sarakstā (ffl).
3. Ja spēlētājam ir līgums ar komandu, tad komanda var izmantot šo spēlētāju spēlēs, treniņos vai transfēros.
### Skili
1. Katram spēlētājam ir četri skili - vārtsarga (St), aizsarga (Tk), pussarga (Ps) un uzbrucēja (Sh).
2. Skilu lielums nosaka spēlētāja vēlamo pozīciju laukumā.
3. Skili ietekmē spēles notikumus un spēlētāja spējas tajos piedalīties.
4. Skilu un spēles taktiku algoritms - https://fflisback.lv/taktikas/
### Fitness
1. Fitnesa punkti (Fit) ir nepieciešami, lai piedalītos spēlē un treniņos. 
2. Spēlētājs ar fit<30 tiek uzskatīts par spēlētāju ar traumu.
3. Piedaloties spēlē tiek tērēti fitness punkti, atkarībā no spēlētā laika ilguma un treniņos no treniņa intensitātes.
4. Katru dienu spēlētājiem fitness tiecas uz 99:
	1. Traumētiem spēlētājiem (fit<30) retos gadījumos fitness var atjaunoties līdz pat 30 fitnesa punktiem, biežāk līdz 3 fitnesa punktiem. Piem: fit=10; reti ikdienā var notikt 10+(1->30), biežāk 10+(1->3).
	2. Pārējiem spēlētājiem atjaunojas no 2->6 fitnesa punktiem dienā.
### Morāle
1. Morāle (Mor) ir spēlētāja spēju palielinājums vai samazinājums.
2. Katru dienu veseliem spēlētājiem morāle tiecas uz 70. Traumētiem spēlētājiem uz traumas fitnesa lielumu.
3. Spēles laikā spēlētāja morāle modificē spēlētāja skilus. Attiecīgi morāle lielāka par 70 tos uzlabo un morāle mazāka pat 70 tos samazina.
### Agresivitāte
1. Katram spēlētājam ir agresivitātes lielums (Ag).
2. Agresivitātes lielums ietekmē spēlētāja aktivitāti laukumā un traumatisma risku.
### Dzimšanas diena
1. Vienu reizi gadā noteiktā dienā spēlētājam ir dzimšanas diena, kad mainās vecums un var notikt fitnesa, morāles un agresivitātes izmaiņas.

## 6. Spēle
## 7. Transfēri
## 8. Turnīri
## 9. Finanses
### Vispārējie noteikumi
1. Komandas vadītājs ir atbildīgs par komandas finansēm, konta atlikumu un finanšu noteikumu neievērošanu
2. Komansas finanses var apskatīt kopējā komandu sarakstā https://fflisback.lv/cms/lv/komandas, kā arī katras komandas lapā ar izvērstu pēdējā laika finanšu plūsmu.
3. Komandas finasnes veido:
	1. ienākumi: regulārie iknedēļas ienākumu sezonas laikā, kausu ienākumi un prēmijas, līgas maiņas ienākums, transfēru darījumi
	2. izdevumi: spēlētāju algas, transfēru izdevumi (izsoles, nodokļi, maksa par spēlētājiem)
### Ienākumi
1. Iknedēļas regulārais ienākums komandai ir atkarīgs no līgas kurā tā spēlē (augstākā līgā lielāki ienākumi) un konkrētā nedēļas panākumiem (officiālo spēļu). Komandai ar vienādu līgu un nedēļas rezultātu (piem. 2 uzvaras 2 spēlēs) ir vienāds ienākums, bet to katrā konkrētā nedēļā modificē ar +/-15%
2. Kausu ienākums veido dalība spēlē (0.5milj) un prēmija par izcīnīto punktu (0.25milj.). Piem. par uzvaru komanda nopelna 0.5milj+3*0.25milj.
3. Automātiski pārvarētās kārtas prēmijas tiek izmaksātas pirms tām, bet pārējais tiek izmaksāts pēc spēļu kārtas. Piem. grupu turnīra gadījumā, prēmijas tiek izmaksātas, kad grupu turnīrs noslēdzas.
4. Kausu finālos prēmijas tiek izmaksātas savādāk - uzvarētājs saņem 5milj, zaudētājs 2.5milj.
5. Sezonas beigās komandas kas paceļas līgu augstāk saņem papildus prēmiju - 1. vieta 5milj., 2. vieta 3milj., 3.vieta 2milj.
### Izdevumi
1. Iknedēļu sezonas laikā spēlētājiem tiek maksātas algas, kas ir spēlētāja līgumā notiktas. Sīkāk par spēlētāja algām sadaļā Spēlētājs
2. Transfēru darījumi (izsoles) tiek aplikti ar nodokli. Sīkāk par šiem nodokļiem sadaļā Transfēri
### Finanšu disciplīna
1. Komandai, kura atrodas mīnusos, kas ir lielāki par komandas spēlētāju kopējo algu, ilgāk par desmit dienām, tiek atņemtas tiesības uz spēlētāju ar lielāko algu. 
2. Šis spēlētājs bez kompensācijas komandai pamet komandu nonāk FFL izsolē. Līgas vadība patur tiesības noteikt šī spēlētāja līguma termiņu un algas izmēru atkarībā no situācijas FFL spēlētāju tirgū. 
3. Komandai tiek dotas vēl desmit dienas, finanšu situācijas sakārtošanai.

