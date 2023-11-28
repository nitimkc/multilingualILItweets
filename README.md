This is the repository, which includes details on multilingual influenza infection related data extracted from Twitter API v2 (via academic access) between March to April 2023.

**Table. 4** : Interrater agreement as measured by Cohen's Kappa Score (in test set only)
|                     | EN    | FR    | ES    | IT    | DE    |
| ------------------- | ----- | ----- | ----- | ----- | ----- |
| Annotator 1-2       | 0.95  | 0.80  | 0.75  | 0.77  | 0.80  |
| Annotator 1-3       | 0.85  | 0.80  | 0.76  | 0.78  | 0.76  |
| Annotator 2-3       | 0.83  | 0.79  | 0.82  | 0.71  | 0.76  |
| Annotator 1-4       |       |       | 0.71  |       |       |
| Annotator 2-4       |       |       | 0.77  |       |       |
| Annotator 3-4       |       |       | 0.77  |       |	      |

**Table. 3** : Details of annotated sample tweets in each language used in the study                      | 
| ANNOTATION DETAILS                   | English (EN)                | French (FR)                 | Spanish (ES)                | Italian (IT)                | German (DE)                 |
| ------------------------------------ | --------------------------- | --------------------------- | --------------------------- | --------------------------- | --------------------------- |
| Time period of annotated sample      | 2018-09-15 to<br>2019-04-29 | 2011-01-01 to<br>2023-03-15 | 2018-09-15 to<br>2023-03-15 | 2018-09-15 to<br>2023-03-15 | 2018-09-15 to<br>2023-03-15 |
| No. of annotators                    | 3                           | 3                           | 4                           | 3                           | 3                           |
| No. of annotated sample (test set)   | 200                         | 400                         | 400                         | 400                         | 400                         |
| ILI vs non-ILI ratio (test set)      | -%                          | 39.5%                       | -%                          | 13.3%                       | 44.3%                       |
| No. of annotated sample (train set)  | 0                           | 400                         | 800                         | 600                         | 600                         |
| ILI vs non-ILI ratio (train set)     | -%                          | 43.0%                       | -%                          | 12.2%                       | 44.8%                       |
			
**Table. 2** : Description of data collected from Twitter in five European languages
<table>
    <tr>
        <td><b>DATA DESCRIPTION</b></td>
        <td><b>English (EN)</b></td>
        <td><b>French (FR)</b></td>
        <td><b>Spanish (ES)</b></td>
        <td><b>Italian (IT)</b></td>
        <td><b>German (DE)</b></td>
    </tr>
    <tr>
        <td>Time period of data collection</td>
        <td>2017-10-29 to<br>2019-04-29</td>
        <td>2011-01-01 to<br>2023-04-11</td>
        <td>2018-09-15 to<br>2023-03-23</td>
        <td>2018-09-15 to<br>2023-03-29</td>
        <td>2018-09-15 to<br>2023-04-11</td>
    </tr>
    <tr>
        <td>Common time period</td>
        <td align="center", colspan="5">2018-09-15 to 2019-04-29</td>
    </tr>
    <tr>
        <td>No. of tweets</td>
        <td>1,376,095</td>
        <td>1,529,838</td>
        <td>1,425,592</td>
        <td>471,692</td>
        <td>185,346</td>
    </tr>
    <tr>
        <td>Monthly avg no. of tweets</td>
        <td>114,675</td>
        <td>127,486</td>
        <td>118,799</td>
        <td>39,308</td>
        <td>15,445</td>
    </tr>
    <tr>
        <td>No. of tokens</td>
        <td>24,278,276</td>
        <td>316,93,212</td>
        <td>25,245,747</td>
        <td>10,777,503</td>
        <td>3,694,624</td>
    </tr>
    <tr>
        <td>No. of unique tokens</td>
        <td>1,292,732</td>
        <td>1,111,799</td>
        <td>1,079,905</td>
        <td>475,888</td>
        <td>238,004</td>
    </tr>
    <tr>
        <td>Lexical diversity</td>
        <td>18.78</td>
        <td>28.51</td>
        <td>23.38</td>
        <td>22.65</td>
        <td>15.52</td>
    </tr>
</table>

**Table. 1** : Keywords used to extract influenza related tweets in five European languages
| Language | Main | Verbs to express being sick | Related to Influenza-Like-Illnesses |
| -------- | ---- | --------------------------- | ----------------------------------- |
| English (EN) | Flu, Influenza | With,  Got,  Have,  Has,  Caught, "Down With",  Bunged,  "Under The Weather",  Man,  Gastro,  Stomach,  Lurgy,  Snotty | Fever, Feverish, Malaise, Chills, Shivering, Fatigue, Unwell, Sick, Ill, Headache, Body Ache, Stomach Flu, Cough, Coughing, Sore Throat, Shortness of Breath, Upper Respiratory, Cold, Congested, Stuffy Nose", "Runny Nose", Sneeze |
| French (FR) | Grippee, Grippes, Grippees, "Avec Grippe", "Avec la grippe", Grippette, "La grippe m'a", "La grippe me", "La grippe est" | Ai, As, A, Avons, Avez, Ont, Avais, Avait, Suis, Es, Est, Sommes, Etes, Sont, Ete, Etais, Etait, Attrape, Choper, Chopper, Choppe, Chope | Fièvre, Fiévreux, Fiévreuse, Malaise, Frissons, Frissonne, Frissonnes, Frissonnons, Frissonnez, Frissonnent, "Sueur froide", Fatigue, Fatiguee, Fatigues, Malade, Malades, "Pas bien", "Mal de tête", Courbatures, Toux, Tousser, Tousse, Tousses, Tousse, Toussons, Toussez, Toussent, "Mal de gorge", Essoufflement, Essouffle, Essouffles, Essoufflons, Essoufflez, Essoufflent, Respiration Courte, Respire, Respires, Respirons, Respirez, Respirent, Froid, "Nez bouché", Rhume, "Nez qui coule", Éternue, Éternues, Éternue, Éternuons, Éternuez, Éternuent |
| Spanish (ES) | Griposo, Griposa, Gripazo, Gripaza, Trancazo, Trancaza, \#Tengolagripe, "Pillado gripe", "Pillado la gripe", "Con gripe", "Con la gripe", "La gripe me", "La gripe es" | Tengo, Tienes, Tiene, Tenemos, Tenéis, Tienen, Estoy, Estás, Está, Estamos, Estáis, Están, Teniendo, Tenido, Siendo, Sido | Fiebre, Febril, Malestar, Escalofríos, Fatiga, "No me sentía bien", "Sentía mal", Enfermo, Enferma, Dolor,  Cansado, Cansada, Estomacal, Tos, Tosee, Garganta, Irritada, "Falta de aire", "Falta de aliento", "Tracto respiratorio superior", Resfriada, Resfriado, Resfrió, "La nariz tapada", "Goteo nasal", Estornudo |
| Italian (IT) | "Presa l'influenza", "Preso l'influenza", "Con l'influenza",  "Presa influenza", "Preso influenza", "Con influenza" | Ho, Hai, Ha, Abbiamo, Avete, Hanno, Sono, Sei, È, Siamo, Siete, Avendo, Avevo, Essendo, Stato, Avere, Avutoy | Febbre, Febbrile, Malessere, Brividi, Fatica, Stanchezza, "Non mi sento bene", Malato, Ammalato, Ammalando, "Mal di testa", "Male la testa", "Mal di corpo", "Male al corpo", "Intestinale", "Mal di pancia", "Male la pancia", Tosse, Tossire, Tossisco, Tossite, Tossito, "Mal di gola", "Male la gola", "Fiato corto", "Respiratorie superiori", Raffreddato, Raffreddata, Congestionato, Congestionato, "Naso chiuso", "Cola il naso", Congestionati, Intasati, Raffreddore, "Goccia al naso", "Naso che cola", Starnutito, Starnutiva, Starnutì, Starnuto, Starnutisco | 
| German (DE) | Erkältet, "Mit grippe", "Bekam die grippe", "Mit der grippe", "Die grippewelle", "Erhat die grippe | Habe, Hast, Hat, Haben, Habt, Bin, Bist, Ist, Sind, Seid | Fieber, Fiebrig, Fieberhaft, Unwohlsein, Schüttelfrost, Zittern, Schlapp, "Fix und fertig", Unwohl, Krank, Kopfschmerzen, Körperschmerzen, Magen-darm-grippe, Husten, Halsschmerzen, Kurzatmigkeit, Atemnot, "Obere atemwege", Erkältung, Verstopft, "Verstopfte nase", "Laufende nase", Niesen | 
