# _Pig Dice_

#### _A game of dice and probability, 01.29.2020_

#### By _**Tiffany Siu and Krista Rutz**_

## Description

_Pig Dice is a dice game where players take turns repeatedly rolling dice to compete in points. For each turn they can roll until they decide to "hold", increasing their total score by that amount. If a "1" is rolled, they score nothing for that turn and their turn ends. The first player to score 100 or more points wins!_

## Setup/Installation Requirements

To view this project:

* _Open the [GitHub pages](https://kristarutz.github.io/Pig-Dice/) link to view the deployed project_

## Specifications

<details>
  <summary>Expand specs for this project</summary>
 
* The user presses "Play" button
  * Example Input: click on "Play"
  * Example Output: create new Game with two Players, player 1 set to initial current player, and new Turn created
* When new Turn is created, "Roll" button appears
  * Example Input: new Game created or turn ends for other player and other player did not win
  * Example Output: "Roll" button appears
* Current player clicks "Roll"
  * Example Input: clicks on "Roll"
  * Example Output: new Dice created
* New Dice created and dice rolls a number
  * Example Input: new Dice created and rolls
  * Example Output: Number between 1-6 generated
* Current Player rolls a 1
  * Example Input: roll = 1
  * Example Output: Turn ends and running score = 0
* Current Player rolls > 1
  * Example Input: roll = 4
  * Example Output: running score += 4 and player given choice buttons "Roll again" and "Hold"
* Current Player clicks "Hold" after roll
  * Example Input: click on "Hold"
  * Example Output: total score += running score and turn ends
* Current Player clicks "Roll again" after roll
  * Example Input: click on "Roll again"
  * Example Output: new Dice created and dice rolls
* When turn ends, current Player total score evaluated if it is greater than winning score
  * Example Input: total score = 103
  * Example Output: total score > winning score, game ends and current player wins
  * Example Input: total score = 45
  * Example Output: total score < winning score, game continues, current player changes, and new Turn created
* When game ends, show player that won
  * Example Input: game ends
  * Example Output: "Player 1 wins!"

</details>


## Known Bugs

No known bugs. Some links are currently disabled while the website is in beta.

## Support and contact details

Please contact me if you run into any issues or have questions, ideas or concerns.  I can be contacted at <krista.rutz@pomona.edu>. _Contributions to the code are encouraged!_

## Technologies Used

* HTML, CSS, and JS (jQuery)
* Responsive design using Bootstrap framework

### License

*This software is licensed under the Attribution-NonCommercial 4.0 International [(CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/legalcode)*

Copyright (c) 2020 **_Krista Rutz and Tiffany Siu_**

##### You are free to:
**Share** — copy and redistribute the material in any medium or format
**Adapt** — remix, transform, and build upon the material
_The licensor cannot revoke these freedoms as long as you follow the license terms._
Under the following terms:
**Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

**NonCommercial** — You may not use the material for commercial purposes.

**No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
_Notices:
You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation.
No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material._
