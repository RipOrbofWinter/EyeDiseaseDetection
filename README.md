# EyeDiseaseDetection
## Project Description
The goal of the project is to create a Machine Learning algorithm that can compare eye images and categorize if there are diseases present. 
Most of these use Fundus photography that are taken with a machine that is available in places other then hospitals https://en.wikipedia.org/wiki/Fundus_photography. 

If the research/prototype is successful I'd like to create a full on application that allows a user to import eye images and get a fast result based on the ML algorithm telling the user if any diseases have been found.

## Data links:
These are links that I found that could be interesting with different levels of difficulty/reliability and their real world impact.

### Dataset 1
- Dataset of eyes with and without Diabetische retinopathie: 
  - https://www.kaggle.com/donkeys/retinopathy-train-2015?select=trainLabels.csv
Op 3 plekken worden diabetes screeningen gedaan voor de ogen
1. ziekenhuis
2. kliniek (prive ziekenhuis)
3. optiek zaken (optimitrist voert het onderzoek voor de ogen uit)
    - maakt foto van netvlies
    - dan kijken hoe goed hij kan kijken

Altijd door een oog arts bekeken (1 of 2)

Grootste voordeel: Zou de foto's kunnen laten maken door niet gespecialiseerd personeel wat geld en tijd kan schelen voor de diabetes patienten en artsen.

### Dataset 2
- Smaller dataset with multiple eye disease: 
  - https://www.kaggle.com/andrewmvd/ocular-disease-recognition-odir5k

Meest interresante als hij zou werken omdat het een grote impact heeft op kwaliteit van zorg bespaart veel tijd voor artsen en patienten, denk aan doorverwezen worden juiste specialisme.
Leukste dataset maar verwachting is laag/slechte resultaten.
Weinig data.
Eventueel niet betrouwbaar.


### Dataset 3
- Dataset with images that are taken with a different more expensive machine that is not normally found outside of hospitals, but shows more interesting data:       
  - https://www.kaggle.com/paultimothymooney/kermany2018

Belangrijk bij deze foto's is dat het gebruikt wordt als progressie foto's van 1 patient bij een arts.
Een arts moet hierbij zelf precies gaan kijken wat voor medicatie toepasbaar is; dit is buiten de scope van het project en te moeilijk. 
Daarnaast is het risico en de schade als er iets fout gaat hoog.


### Dataset 4
- Dataset of images with and without Glaucoma. This dataset has images that are very similar and might be more consistent for a ML algorithm to categorize:       
  - https://www.kaggle.com/sshikamaru/glaucoma-detection

Te kleine dataset en normaal andere techniek voor gebruik.
Patient heeft deze ziekte vaak niet door en zou daarom veel voordeel uit het onderzoek halen omdat het vroeg gevonden zou kunnen worden.

### Choice
We besloten dat dataset 1 de meeste waarde voor de oogzorg in combinatie met de beste kans op slagen heeft.