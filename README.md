# universe wars

> like [Digimon Frontier](https://en.wikipedia.org/wiki/Digimon_Frontier), sorta

Simon (9 year old) & I are making a game. We are currently using [RPG Maker MV](http://www.rpgmakerweb.com/products/programs/rpg-maker-mv) to edit the assets & logic, but eventtually I want to make a web-based asset-driven game-engine & editor with custom stuff.

There are a lot of unused assets from the the base-game & ideas we played with.

See also [omra](https://github.com/notnullgames/omra) a quick 3D start at some of the ideas.

## development

You can edit the game in [RPG Maker MV](http://www.rpgmakerweb.com/products/programs/rpg-maker-mv).

```
npm i            # install development tools
npm start        # start a local development-server
npm run deploy   # deploy to a public web-server
```


## game mechanics

### element stones

need an element stone - choose one, it makes you a more powerful form, with strengths and weaknesses
there's monsters

You can start as one of these:

* fire
* water
* electricity/lightning
* earth

These can be found in the field:

* creation - giant cat with yarnball
* destruction (infectected creation) - teddy bear, turns into more fierce alin looking
* light
* dark (infected light)
* life
* death (infected life)
* galaxy - little boy / warrior with a shield
* mind - little girl / pocessed looking (but stil little)
* ice
* silver
* gold
* platinum
* magic - higher form

### biomes

creation, destruction, life, death, mind, light, dark are everywhere

* forest - earth, fire, magic
* ocean (beaches) - water, earth
* holy (temples) - whatever the people worship is in greater amounts, mind, rare galaxy in towers
* desert - earth, fire
* mountains - earth, gold, platinum, silver, galaxy at peaks
* glaciers - water, ice

### fusions

combine any 2 types, you have 2 element jars, and each vanquished monster gives you some element-framents that optionally go in a jar. element-fragments stay on the field (so they can be collected later, when you have the jar space.)

some fusions add extra regular-game effects:

* water/water - walk on water

### game modes

* start screen - pick character/element-stone
* walk around map
* fight

### later

* crappy world - everythign looks like a bad drawing
* hell
* cute
* boats to cross oceans/rivers
