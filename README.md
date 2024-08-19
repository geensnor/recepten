De recepten zijn verhuisd naar De Digitale Tuin:
https://github.com/geensnor/DeDigitaleTuin/tree/main/src/content/recepten


# Metadata

Als je wil dat de metadata van de recepten goed staat, moet je je aan de volgende regels houden:

1. De H1 is de naam van het gerecht
2. Hij gebruikt de eerste afbeelding die hij tegen komt als afbeelding van het gerecht. De rest wordt genegeerd.
3. De lijst (ul) na het woord "Ingredienten" wordt beschouwd als de lijst van ingredienten.
4. De lijst (ol) na het woord "Bereiding" wordt beschouwd de stappen voor de bereiding.

## Extra velden

Extra metadata kun je in het recept meegeven via Frontmatter. Hieronder staat hoe, en welke velden je kan gebruiken. Alles is optioneel.

```YAML
---
prepTime: PT30M
cookTime: PT30M
totalTime: PT60M
recipeYield: 3
keywords: vegetarisch,groente
recipeCategory: hoofdgerecht
recipeCuisine: japans
calories: 400
author: Piet
---
```

Het [schema](https://schema.org/Recipe) bevat nog veel meer velden, maar daar doen we (nog?) niets mee.

De metadata wordt bovendien in een geinig tabelletje bovenin het recept weergegeven.

Meer info: [https://jsonld.com/recipe/](https://jsonld.com/recipe/)
