## Test case: 00001

*a) Functionality*

**Summary:**
Checking the possibility of storing equipment in the backpack

**Preconditions:**

1. The Backpack is contained the free slots
2. The Player is in the tactical operations
3. Equipment items are available in the main storage

Step actions | Expected Results
------------ | -------------
1.Open the main storage | 1.The main storage is opened
2.Move the helmet item into the backpack | 2.The helmet item is moved into the backpack

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00102

*b) Effectiveness of UI*

**Summary:**
Checking the possibility of adding the same items into the same slot

**Preconditions:**

1. The Backpack is contained the medication item
2. The Player is in the tactical operations
3. The enemy backpack is contain medication item

Step actions | Expected Results
------------ | -------------
1.Kill the enemy | 1.Enemy is killed
2.Collect the fallen items from the enemy backpack | 2.The items are collected in the backpack
3.Move the collected medication item into the slot of player medication item | 3.The collected item is added into the existed slot of medication item

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00103

*c) Usability*

**Summary:**
Checking the possibility of using boost item with hotkeys

**Preconditions:**

1. The Backpack is contained the boost item
2. Player is able to use boost item

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Use the hotkeys for the boost item | 2.The boost item is used to the Player

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00104

*d) System resilience and recoverability*

**Summary:**
Checking the possibility of saving collected items after exeting the game

**Preconditions:**

1. The Backpack is contained the items
2. The Player is in the tactical operations

Step actions | Expected Results
------------ | -------------
1.Open the backpack | 1.The backpack is opened
2.Take a look at the items in the backpack | 2.The items are collected in the back pack
3.Exit the game | 3.The game is exited
4.Start the game | 4.The game is started
5.Open the backpack | 5.The backpack is opened
6.Pay attention to the items | 6.All items are saved in the backpack

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00105

*e) Performance*

**Summary:**
Checking the possibility of filling slots with maximun number of items

**Preconditions:**

1. The Backpack is full of free slots
2. The Player is in the tactical operations
3. Player has a sufficient number of droped medication items to fill

Step actions | Expected Results
------------ | -------------
1.Open the backpack | 1.The backpack is opened
2.Fill the each slot with maximun number of medication elements | 2.The slots are filled by the medication items

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00106

*f) Security*

**Summary:**
Checking the possibility of collecting the personal item

**Preconditions:**

1. The Backpack is contain personal item
2. The Player is in the tactical operations
3. Enemy is dropped the personal item

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Find the enemy with personal item | 2.The enemy with personal item is found
3.Collect the personal item into the backpack | 3.Item is not collected into the backpack

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00107

*g) Integration*

**Summary:**
Checking the possibility of exchanging players

**Preconditions:**

1. The Backpack is contain items
2. The Player is in the tactical operations
3. Ally backpack is contain items

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Find the ally | 2.The ally is found
3.Open the exchange window | 3.The exchange window is opened
4.Make an exchange with ally | 4.Exchange is made with ally

**Importance:** High

**Requirements:** None
