# 'Godot LikeCoin' CHANGELOG 

## v0.4 (2020-07-31)
* add: **Play sound** when "Player pickup Coin"
* add: Play sound when "Game Over"
* fix: Player can't move after "Game Over"
* fix: Coins stay on screen after "Game Over"
* fix: Rename "START" button -> "NEW GAME"
* fix: update Level on HUD

## v0.3 (2020-07-24)
* add: Counters: Level, Score, Time
* add: **HUD** (Level, Score, Time)
* add: **'Start'** button (restart game, after 'game over')
* add: **GameTimer**
* add: **'Game Over'** by Timeout
* add: HUD: "Game over" message

## v0.2 (2020-07-24)
* fix: reimported sprites without smooth (thanks to Yaroslav Gavrilov)
* add: **'Main'** scene (is primary, now)
* add: spown_coins() and new_game() - random level-generator
* add: **_G** - global autoload **Singleton**

## v0.1 (2020-07-23)
* add: **'Player'** scene
* add: Move Player by keys: Up, Down, Left, Right
* add: Player animations: idle, run, die
* add: Player collisions func
* add: **'Coin'** scene
* add: Player can pickup Coin
* add: **'Test-01'** scene - for testing Player and Coins
