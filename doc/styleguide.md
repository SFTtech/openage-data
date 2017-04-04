# Styleguide - Do's and Don't's

Please adhere to this guide if you want to contribute any assets to the project.

## Why you should follow this guide

Game assets usually have a purpose beyond looking pretty. They are also visual aides to the player, helping them to achieve what they want. Players might admire your shiny graphic asset at first but in a tense multiplayer battle there will be no time for that. Therefore, your assets should not only be nicely drawn but also recognizable, functional and fitting for players' needs.

Don't worry, you still have a lot of creative freedom!

## Buildings

### Civ architecture

* Building sprites should use the architecture of their civilization.
* Keep in mind that every architecture requires building sprites for Feudal, Castle and Imperial Age for some buildings.

### Shape

* Most buildings have unique shape (Examples to be done) that is consistent throughout civilization architectures. Try to follow that shape, when you create a building from scratch.
* You don't have to follow the exact shape for every architecture. As a rule of thumb: The more a player frequents a building, the closer it should follow its unique shape. Examples are below.
  * High frequency: Town center, barracks, archery range, stable
  * Medium frequency: Market, mill, lumber/mining camp
  * Low frequency: University, house
* Monasteries and wonders have no fixed unique shape. Be creative with your models here.

### Size

* Building sprites should neither exceed their foundations nor be smaller than them. Otherwise players who use buildings to wall off their base will get confused whether there are holes in their defense.

### Colors

* Building sprites should have markings that can be used for the player colors. They shouldn't dominate the building but also shouldn't be too subtle.
* Make sure that all 8 supported player colors will be visible on the markings. None of them should blend in with the building.

## Units

### Models

* Unit models don't have to be historically accurate.
* Models should be recognizable and not be too similar to other unit models.
* Parts of the armor have to be reserved for the player colors. Make sure that all 8 supported colors work with your model.
* Also make sure that the above rules are guaranteed **for every direction** the unit can face.

### Animations

* Attack animations should be clearly visible **for every direction** the unit can face.
* You should provide the following animations for each unit:
  * idle
  * walking
  * attacking
  * dying
  * decaying
* Try to fit the length of an animation to the units attack speed.

## Sounds

* Sounds should not be longer than 3 seconds.
* Try to make sounds as short as possible, preferrably 1 second or shorter.
* Sounds that are used in combination with animations (e.g. attacking, dying, etc.) should not exceed the length of the animation.
* Sounds should be distinctive. Don't use similar sounds for completly different actions.
* Try to minimize repetition in a sound.

## Music

* We may prefer a soundtrack that is close to the original tunes (e.g. medieval themed songs) but you can do everything you want.
* If you would like to sing something, go for it! It might not end up as the ingame soundtrack but we will find a use for it.
* Please don't plagiarize other people's work.

## Interface

* Buttons should depict their function with an icon. Don't use text on buttons.
* Buttons that create a unit should always show the upper half of the actual unit model.
* When drawing an icon, make sure it doesn't blend in with other interface elements. Keep in mind, that different civilizations can have different backgrounds for their Interface
