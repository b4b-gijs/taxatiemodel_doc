
# Hedonische regressie

[terug](README.md)

 ### Definitie

Hedonische regressie is een methode om de waarde van een goed (woning) te bepalen, door het goed te omschrijven als een verzameling van losstaande attributen. Hierbij wordt ervanuit gegaan dat deze decompositie mogelijk is. De waardering wordt hiermee opgedeeld in de samengenomen waardering van de individuele bijdragen van deze attributen.

Deze modellen worden in de meeste gevallen gebruikt in de vorm van regressiemethoden, waarbij de afhankelijke variabele de prijs van het goed is, en de onafhankelijke variabelen gegeven worden door de attributen. Er wordt aangenomen dat alle attributen die een significante invloed hebben op de daadwerkelijke waarde worden meegenomen in het model, en dat binnen het genomen gebied en tijdsperiode dezelfde quantificeerbare verhouding geldt tussen een attribuut en de totale waarde.

De resulterende geschatte cöefficienten voor de onafhankelijke variabelen kunnen als statistische gewichten worden geïnterpreteerd. Deze gewichten zijn representatief voor de waarde is die kopers in de gegeven periode en het gegeven gebied plaatsen op de verschillende attributen. Binnen het genomen geografische gebied wordt aangenomen dat geen verdere de afhankelijkheid van locatie is.

De coëfficienten worden bepaald door prijsverschillen te analyseren tussen woningen die, op dat specifieke attribuut na, vrijwel dezelfde kenmerken hebben binnen een gegeven tijdsperiode en geografisch gebied. Hierdoor zijn deze modellen wel sterk afhankelijk van het gebied en tijdsframe die meegenomen worden.

 ### Berekening marktwaarde

Over het algemeen word de geschatte prijs *K* in Hedonische modellen gegeven door een functie van de toegevoegde waarde *k<sub>i* van attribuut *i* in de vorm
```math
K=\sum_ip_ik_i+\varepsilon,
```
waar gesommeerd wordt over het product van de waarde en de relatieve weging *p<sub>i* per attribuut. De fouten die niet verklaard worden, welke ontstaan door onder andere schattingsfouten, worden samengenomen in de 'error'-term (een fittingparameter van het model):
```math
\varepsilon.
```

Een andere vergelijking die ook wel wordt toegepast heeft de vorm
```math
\ln(K)=c_0+\sum_ip_ik_i
```
waarbij de afhankelijkheid exponentieel is. *c<sub>0* is de helling van deze functie op de intercept, een constante toevoeging welke een fittingparameter van het model is.
