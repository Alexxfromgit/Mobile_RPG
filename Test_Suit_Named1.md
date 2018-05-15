## Test case: 00001

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

## Test case: 00002

**Summary:**
Checking the possibility of storing medication and boosts in the backpack

**Preconditions:**

1. The Backpack is contained the free slots
2. The Player is in the tactical operations
3. Medication and boosts items are available in the main storage

Step actions | Expected Results
------------ | -------------
1.Open the main storage | 1.The main storage is opened
2.Move the medication item into the backpack | 2.The medication item is moved into the backpack
3.Move the boost item into the backpack | 3.The boost item is moved into the backpack

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00003

**Summary:**
Check for falling items from enemy backpack when enemy is killed

**Preconditions:**

1. The Backpack is contained the free slots
2. The Player is in the tactical operations
3. The enemy backpack is contain items

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Kill the enemy | 2.Enemy is killed
3.Take a look at the fallen items | 3.The items from enemy backpack is fallen

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00004

**Summary:**
Checking the automation collection of fallen items

**Preconditions:**

1. The Backpack is contained the free slots
2. The Player is in the tactical operations
3. The enemy backpack is contain items

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Kill the enemy | 2.Enemy is killed
3.Take a look at the fallen items | 3.The items from enemy backpack is fallen
4.Automatically collect the items | 4.The items are collected automatically

**Importance:** High

**Requirements:** None


------------------------------------------------------------------------

## Test case: 00005

**Summary:**
Checking the possibility of collecting items in the main storage

**Preconditions:**

1. The Backpack is contained the items
2. The Player is returned from the tactical operation to the military base
3. The main storage is contained free slots

Step actions | Expected Results
------------ | -------------
1.Open the main storage | 1.The main storage is opened
2.Move medication items into the main storage | 2.The medication items are moved into the main storage
3.Move helmet item into the main storage | 3.The helmet item is moved into the main storage

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00006

**Summary:**
Checking the possibility of collecting items in the main storage

**Preconditions:**

1. The Backpack is contained the items
2. The Player is returned from the tactical operation to the military base
3. The main storage is contained free slots

Step actions | Expected Results
------------ | -------------
1.Open the main storage | 1.The main storage is opened
2.Move medication items into the main storage | 2.The medication items are moved into the main storage
3.Move helmet item into the main storage | 3.The helmet item is moved into the main storage

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00007

**Summary:**
Checking the access to the Backpack of first player level

**Preconditions:**

1. The Player is the first level

Step actions | Expected Results
------------ | -------------
1.Start the new game | 1.The new game is started
2.Open the backpack | 2.The backpack is opened

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00008

**Summary:**
Checking the access to the Backpack of last player level

**Preconditions:**

1. The Player is the last level

Step actions | Expected Results
------------ | -------------
1.Start the new game | 1.The new game is started
2.Open the backpack | 2.The backpack is opened

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00009

**Summary:**
Checking the empty slots in the backpack after the first opening of the backpack

**Preconditions:**

1. The Backpack is starting first time

Step actions | Expected Results
------------ | -------------
1.Start the new game | 1.The new game is started
2.Open the backpack | 2.The backpack is opened
3.Pay attention to the empty slots in the backpack | 3.The slots are empty in the backpack

**Importance:** High

**Requirements:** None


------------------------------------------------------------------------

## Test case: 00010

**Summary:**
Checking the possibility of moving equipment items into backpack from the main storage

**Preconditions:**

1. The Backpack is contained the free slots
2. The Player is in the tactical operations
3. Helmet item is available in the main storage

Step actions | Expected Results
------------ | -------------
1.Open the main storage | 1.The main storage is opened
2.Move the helmet item into the backpack | 2.The helmet item is not moved into the backpack

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00011

**Summary:**
Checking the ability to buy additional slots using in-game currency

**Preconditions:**

1. The Player has enough in-game currency for purchase

Step actions | Expected Results
------------ | -------------
1.Open the buying menu | 1.The buying menu is opened
2.Buy the additional slot to the backpack | 2.The additional slot is bought
3.Pay attention to the new added slot in the backpack | 3.The new slot is added to the backpack

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00012

**Summary:**
Checking the ability to collect item when backpack is full

**Preconditions:**

1. The Backpack does not have free slots
2. The Player is in the tactical operations

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Kill the enemy | 2.Enemy is killed
3.Take a look at the fallen items | 3.The items from enemy backpack is fallen
4.Collect the items | 4.The items are not collected

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00013

**Summary:**
Checking the ability to drop item when backpack is full

**Preconditions:**

1. The Backpack does not have free slots
2. The Player is in the tactical operations

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Open the backpack | 2.Backpack is opened
3.Drop item from the backpack | 3.The item is deleted from the backpack
4.Pay attention to the free slot in the backpack | 4.The new free slot is existed in the backpack

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00014

**Summary:**
Checking the ability to recollect droped item when backpack is full

**Preconditions:**

1. The Backpack does not have free slots
2. The Player is in the tactical operations

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Open the backpack | 2.Backpack is opened
3.Drop item from the backpack | 3.The item is deleted from the backpack
4.Collect the droped item into the backpack | 4.The item is collected into the backpack

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00015

**Summary:**
Checking the ability to use medication and boost items directly from the Backpack

**Preconditions:**

1. The Backpack is contain the medication and boost items
2. The Player is in the tactical operations

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Open the backpack | 2.Backpack is opened
3.Use the medication item from the backpack | 3.The medication item is used from the backpack
4.Use the boost item from the backpack | 4.The boost item is used from the backpack

**Importance:** High

**Requirements:** None

------------------------------------------------------------------------

## Test case: 00016

**Summary:**
Checking the ability to equip items during the tactical operation from the Backpack

**Preconditions:**

1. The Backpack is contain the equipment items
2. The Player is in the tactical operations

Step actions | Expected Results
------------ | -------------
1.Start the tactical operation | 1.The tactical operation is started
2.Open the backpack | 2.Backpack is opened
3.Use the boots item from the backpack | 3.The medication item is not used from the backpack
4.Use the helmet item from the backpack | 4.The helmet item is not used from the backpack

**Importance:** High

**Requirements:** None
