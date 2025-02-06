Titel: Geef je project een pakkende titel.
Beschrijving: Beschrijf kort wat je project inhoudt en waar het voor dient.
Installatie-instructies: Indien van toepassing, geef instructies over hoe het project geïnstalleerd kan worden.
Gebruiksinstructies: Indien van toepassing, geef instructies over hoe het project gebruikt kan worden.
Bijdragen: Geef aan hoe anderen kunnen bijdragen aan je project - optioneel.
Licentie: Geef de licentie van je project weer (bijv. MIT, GPL) - optioneel.
Contactgegevens: Voeg contactgegevens toe voor mensen die meer informatie willen of vragen hebben.


# H1 DOM-objecten: asynchroon

In dit hoofdstuk zien we hoe we **asynchroon** kunnen programmeren in **JavaScript**. *Normaal* wacht de browser totdat een script volledig is uitgevoerd, met asynchroon scripts wacht de browser *niet* en gaat verder met het volgende script. Met een **callbackfunctie** laten we aan de browser weten als het asynchrone script volledig is afgewerkt.

> de gebruikerservaring verbeterd fors als we asynchrone script toepassen.

# H2 Hier een voorbeeldje van 

`function voerTaakUit(taak, callback) {
            alert("Start met " + taak + ".");
            alert("Ik heb gedaan met " + taak + ".");
            callback();
        }

        function tevredenZijn() {
            alert("Ik ben tevreden over mijn werk!");
        }

        voerTaakUit("JavaScript herhalen", tevredenZijn);`

Op Moodle staat de cursus:

[Moodle van CVO De Verdieping](https://moodle.eschool.be)

# H3 Volgende onderwerpen worden behandeld in deze cursus:

1. Inleiding
2. Editor: Visual Studio Code
3. Inleiding
- DOM
- Arrays
- Events en events handlers
4. Debugging
5. Objecten
- Object constructor
- Prototype
6.Client side storage

![afbeelding](https://moodle.eschool.be/moodle2/pluginfile.php/1665276/course/section/320428/Header_Moodle-vschool_w1200px.jpg)



