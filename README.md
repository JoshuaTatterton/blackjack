# Blackjack - Makerthon!

As part or the Ronin group we participated in the Makerthon exercise which was to rapidly create an MVP (minimum viable product) for a project of our choice. We chose to make a game of blackjack, due to the short timespan of 2 days with half a third day to make final alterations and to deploy. Due to this time constraint our MVP consisted of playing a solo game where you can hit until you bust and start a new game. Also due to this constraint we were not able to apply a database to our website and instead it uses a cruder method for persisting state.

Please find the website on Heroku [here](https://pure-refuge-7844.herokuapp.com/)

#### Skills Used

- Woring on the back-end first I used ruby to help build the logic for the game of blackjack. Programming an ace to count as 1 or 11 took the most time.
- I helped apply the knowledge of jQuery get requests gained in [BattleshipsWeb](https://github.com/JoshuaTatterton/BattleshipsWeb) to help keep this a single page app.

#### Skills Gained/ Improved

- Learning how to deploy this rails app to Heroku was interesting because the locations or the assets changed when deployed so we had to find a way to call images and scripts which worked for both development and production.
- This was our first attempt at managing a larger group of people and used git branches for version control and we attempted to use Trello as a task manager.

#### Technologies Used

- Development: Ruby, Ruby on Rails, Javascript, Jquery, HTML, CSS
- Testing: Rspec

#### How To Use

- After cloning and running bundle to install the required gems there is no other set up required 
- You can use the "rails server" command to launch the app locally or deploy to a hosting service such as Heroku to use.

#### Basic rules

```
Player goes bust if over 21
Picture cards are worth 10 points
Ace is worth 1 or 11
Player is dealt minimum 2 cards
Player can continue to hit until he/she goes bust or reaches 21
```

#### Screenshot
 
![alt text](https://github.com/JoshuaTatterton/blackjack/blob/master/app/assets/images/blackjack_screenshot.png)

The Ronin team consisted of me, [Winnie](https://github.com/winnieau), [Parminder](https://github.com/ajitsy), [Richard](https://github.com/RichardCharman) and [Balint](https://github.com/squarebe).

