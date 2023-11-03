
 # Comparables Based Automated Valuation Models (AVMs)

[terug](model_list.md)

 ### Definitie

Een automated Valuation Model (AVM) is een softwarepakket gebaseerd op wiskundige methodes, welke gebruikt word door marktanalisten om een schatting te maken van marktwaarde op basis van locatie, marktcondities en vastgoedkarakteristieken op basis van informatie welke eerder op onafhankelijke wijze is verzameld.

De unieke eigenschap van AVMs is dat de waardeschatting gebaseerd is op een wiskundig model, en op basis hiervan een geautomatiseerd waardeoordeel maakt. Dit onderscheidt AVMs fundamenteel van Hedonische modellen, waarbij het waarderingsproces niet standaard op geautomatiseerde wijze gebeurt. De betrouwbaarheid van de AVM is afhankelijk van de gebruikte data, en van de vakkundigheid van de ontwikkelaar van de AVM.

 ### Berekening marktwaarde
In het geval van AVMs zijn er meerdere verschillende wiskundige achterliggende modellen mogelijk, waardoor het onmogelijk is om een algemene vorm van een vergelijking tussen de marktwaarde en de attributen te geven. 

Echter zijn er wel methodes die vaker gebruikt worden. Zo is een regelmatig voorkomend model het (nonlineaire) hybride model, waarbij de geschatte waarde *K* gegeven wordt door een vergelijking van de vorm
 $$
K=p^{algemeen}\cdot\left[\sum_t\left[\prod_x\left(p_x^{(t)}\right)\sum_y\left(k_y^{(t)}\right)\right]\right]
 $$
 waarbij de *p<sup>(t)* wegingsfactoren van de verschillende attribuutgroepen zijn, *p<sup>algemeen* een algemene normalisatiefactor is die corrigeert voor het geval dat de som van wegingen anders dan 1 is, en de *k<sup>(t)* de waardetoevoegingen zijn van de verscheidene attributen.