Cards Game API Based Testing. 

https://deckofcardsapi.com/ 

#### Rest Assured Framework with Java and Cucumber with BDD based scenarios would be a good fit for API Testing in my knowledge. There are many other ways to do in general.

## Test Cases for Cards Game:

### 1.	Navigate to the Card Game API Website:
•	Verify that the URL opens successfully.
•	Check if the website's API documentation loads without errors.

### 2.	Confirm Site Availability:
•	Verify that the API is responsive and available for requests.

### 3.	Get a New Deck:
•	Send a request to create a new deck.
•	Confirm that a new deck is generated.

### 4.	Shuffle the Deck:
•	Send a request to shuffle the deck.
•	Verify that the deck is shuffled effectively.

### Below 3 I couldn’t find the API endpoints from the api Document, I might have questions on these.

### 5.	Deal Cards to Players:
•	Send a request to deal three cards to each of two players.
•	Confirm that each player receives three cards.

### 6.	Check for Blackjack:
•	Check the cards dealt to each player to see if they have a blackjack hand (21 points).
•	Determine which player, if any, has a blackjack hand.

### 7.	Report Blackjack Winner:
•	If a player has a blackjack hand, report which player has it.
