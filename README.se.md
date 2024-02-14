# Unity-ECS-Template

Beskrivning på svenska.

[Läs detta på engelska](./README.md)


## Om mallen

Unity ECS Mallen är framtagen för att ge en flygande start åt projekt som använder sig av Entity-Component-System arkitekturen i Unity. Den erbjuder en välordnad och heltäckande grund, idealisk för att skapa spelupplevelser som är både prestandaorienterade och datadrivna.

## Struktur för kodförrådet

- **.vscode**: I denna mapp finns konfigurationer för Visual Studio Code för att garantera en konsekvent kodningsmiljö.
- **Assets**: Uppdelade i olika kategorier som `Animations`, `Scripts`, `Sounds` med mera. Denna mapp innehåller tillgångar och deras motsvarande metafiler, vilket underlättar hanteringen.
- **ProjectSettings**: Här finner du viktiga inställningsfiler för Unity-projektet som styr projektets övergripande beteende.

## Konfigurering för 3D och andra typer av projekt

Även om den initialt är inställd för 2D-applikationer, kan mallen enkelt konfigureras om för 3D eller andra projekttyper genom att följa dessa steg:
1. Starta projektet i Unity.
2. Navigera till `Edit > Project Settings`.
3. Ändra `Graphics`-inställningarna för att passa 3D-kraven.
4. Anpassa ytterligare inställningar som `Physics`, `Quality` och `Layer` efter projektets specifika behov.

## Användningsinstruktioner

1. På kodförrådets sida, klicka på "Use this template"-knappen.
2. Skapa ett nytt kodförråd med hjälp av denna mall.
3. Klona det nya kodförrådet och öppna det i Unity för att starta ditt projekt.

## Dokumentation

För att fullt ut dra nytta av möjligheterna med denna Unity ECS-mall är det kritiskt att man förstår grunderna i Unitys Entity-Component-System (ECS)-arkitektur. Här följer noggrant utvalda resurser som fokuserar på ECS och Unitys entitetspaket:

- [Unitys ECS-Dokumentation](https://docs.unity3d.com/Manual/EntityComponentSystem.html): En genomgripande guide som djupdyker i detaljerna av Unitys ECS-arkitektur och tydliggör dess kärnkoncept.
- [ECS-Exempel](https://github.com/Unity-Technologies/EntityComponentSystemSamples): En samling exempel som demonstrerar olika mönster av ECS inom Unity.
- [Unity Entities-Paketet](https://docs.unity3d.com/Packages/com.unity.entities@0.17/manual/index.html): Detaljerad dokumentation om Unity Entities-paketet, absolut nödvändigt för effektiv användning av ECS.

## Licens

Detta projekt distribueras under Unlicense, vilket tillåter fri användning. Observera att bidrag och forkningar för närvarande inte stöds för denna mall.
