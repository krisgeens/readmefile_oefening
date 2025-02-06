# DOM-objecten: asynchroon

In dit hoofdstuk zien we hoe we **asynchroon** kunnen programmeren in **JavaScript**. *Normaal* wacht de browser totdat een script volledig is uitgevoerd, met asynchroon scripts wacht de browser *niet* en gaat verder met het volgende script. Met een **callbackfunctie** laten we aan de browser weten als het asynchrone script volledig is afgewerkt.

> de gebruikerservaring verbeterd fors als we asynchrone script toepassen.

## Hier een voorbeeldje van 

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

## Volgende onderwerpen worden behandeld in deze cursus:

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

### installatieinstructies:

download de files en open ze in Visual Studio Code of in Sublime Text

### Gebruiksinstructies:

Alle files zijn vrij te gebruiken en mogen naar eigen inzicht worden aangepast.

## Licentie:

Op deze software hoeft geen li te worden betaald, het is freeware.

## Contactgegevens:

Voor meer info en voorstellen tot samenwerken kan je contact opnemen met de eigenaar van deze Git Repo.

Happy Coding! :-)

