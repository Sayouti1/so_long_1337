# so_long_1337
## Description:
This goal of this project was to create a small 2D game, where you can collect "collectables" and exit the world. We used the MiniLibX graphics library.

## Usage:
**Linux only**

- `git clone https://github.com/Sayouti1/so_long_1337.git`
- run `make` in cloned repository
- To launch the game, execute `./so_long` with a map as argument: \
`./so_long maps/map.ber` \
`./so_long maps/subject1.ber`

## Bonus
- run `make bonus` in cloned repository
- To launch the game, execute `./so_long` with a map as argument: \
`./so_long maps/bonus.ber`

### HOW TO PLAY

The player’s goal is to collect all collectibles present on the map then escape with minimal movement.

|KEYBOARD|ACTION|
|---|---|
|`W`|Move up|
|`S`|Move down|
|`A`|Move left|
|`D`|Move right|
|`ESC ⎋`|Close the game window|

## Customize a map
- <h3>To create a customized game map, follow these rules:</h3>

<b>Components:</b>

- The map must consist of three main components: walls, collectibles, and free space.
Character Representation:

Use the following characters to represent different elements on the map:
<ul>
    <li> 0 for an empty space,</li>
    <li> 1 for a wall,</li>
    <li> C for a collectible,</li>
    <li> E for a map exit,</li>
    <li> P for the player’s starting position.</li>
</ul>
Required Elements:

Ensure that the map contains the following elements to be considered valid:
1 exit (E),
At least 1 collectible (C),
1 starting position for the player (P).

<h4 style="color:#15FF15">Here's an example of a valid map:</h4>
<p>

    11111
    1CE01
    1C0P1
    11111
</p>
## Result:

- Status: <b style="color:green">Completed</b>
- Result: <b style="color:green;">115%</b>

## Contact:
- Telegram: https://t.me/sayouti1
- email: aes-sayo@student.1337.ma


