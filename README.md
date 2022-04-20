# The Aviator 2

Updated version of Kaim Maaloul's The Aviator, see his [Article on Codrops](http://tympanus.net/codrops/?p=26501), demo [Demo](http://tympanus.net/Tutorials/TheAviator/) and [GitHub](https://github.com/yakudoo/TheAviator).

![The Aviator 2](https://tympanus.net/codrops/wp-content/uploads/2022/04/Aviator2_featured.jpg)

[Article on Codrops](https://tympanus.net/codrops/?p=63296)

[Demo](https://tympanus.net/Tutorials/TheAviator2/)

This repository is the archive of the source code for the Codrops article and will not get updated.

## Start

Clone repository, in the code directory run `php -S localhost:8123` and in your browser visit [http://localhost:8123/](http://localhost:8123/).


## License

Integrate or build upon it for free in your personal or commercial projects. Don't republish, redistribute or sell "as-is". 



## Credits

### Libraries

- [Three.js](http://threejs.org/)
- [TweenMax](http://greensock.com)


### Sounds

Sound effects obtained from https://www.zapsplat.com and https://freesound.org/.

From freesound:

 - Sound "Crash" by user "Previsionary" (https://freesound.org/people/Previsionary/sounds/593677) licensed under Creative Commons 0
 - Sound "Bubble Pop" by user "elmasmalo1" (https://freesound.org/people/elmasmalo1/sounds/376968) licensed under Attribution 3.0
 - Sound "Bullet_Impact_2" by user "toxicwafflezz" (https://freesound.org/people/toxicwafflezz/sounds/150838) licensed under Attribution 3.0
 - Sound "Pacific Ocean" by user "tim.kahn" (https://freesound.org/people/tim.kahn/sounds/174763) licensed under Attribution 3.0
 - Sound "Airship propeller engine" by user "ilm0player" (https://freesound.org/people/ilm0player/sounds/578181/) licensed under Creative Commons 0
 - Sound "Rock Smash" by user "NeoSpica" (https://freesound.org/people/NeoSpica/sounds/512243) licensed under Creative Commons 0
 - Sound "Gun shot/bullet hit" by user "coolguy244e" (https://freesound.org/people/coolguy244e/sounds/266916) licensed under Creative Commons 0
 - Sound "Pistol Shot" by user "LeMudCrab" (https://freesound.org/people/LeMudCrab/sounds/163456/) licensed under Creative Commons 0
 - Sound "Water Splash" by user "Yin_Yang_Jake007" (https://freesound.org/people/Yin_Yang_Jake007/sounds/406087/) licensed under Attribution 3.0
 - Sound "Coins - 01" by user "DWOBoyle" (https://freesound.org/people/DWOBoyle/sounds/140382/) licensed under Attribution 3.0


## Misc

Follow Michel: [Twitter](https://twitter.com/MichelOliverH)

Follow Karim: [Twitter](https://twitter.com/yakudoo), [Codepen](http://codepen.io/Yakudoo/)


## Updates over the original

**07 April 2022**
 - when replaying, remove all coins and enemies
 - fix bug about the state handling after dying
 - implement all audio
 - find audio files
      - propeller/airplane sound
      - shooting simple, double, better
      - background music
      - picking up collectible
      - collision with enemy
      - collecting a coin

**06 April 2022**
 - airplane recoil
 - make end screen after 5 levels
 - make collectibles logic
      - life: if life<3 and a small chance
      - simple gun: level 2
      - double gun: level 3
      - better gun: level 4

**05 April 2022**
 - fix bug that no more enemies are spawning
 - transfer to new three.js version
 - design collectibles
      - simple gun
      - better gun
      - double gun
      - life
 - complete simple gun, better gun and double gun

**04 April 2022**
 - design airplane's machine gun
 - redesign coins
 - each level has a different sea color
 - remove energy bar
 - show hearts as remaining hitpoints
 - show new level entry prominently
 - be able to shoot
 - copy initial game