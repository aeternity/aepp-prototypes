# Results Last Sprint (07)

## 1. We created a Blockchain Explorer for the Æternity Test Net
Which is a web tool that provides detailed information about blocks, addresses, and transactions made on the Æternity Test Net. It is mainly aimed at advanced users who already know what blocks are and what kind of information they contain. As our goal is to make the Blockchain more accessible for the mass, we designed a certain hierarchy in the visual representation of the different layers. (1) Blocks contain transactions, (2) transactions are interactions between addresses, (3) addresses contain user-specific information.

You can visit the working version [here](https://explorer.aepps.com/)

### The Dashboard
* Starts with a prominent placed introduction text and a universal search bar, so users can instantly search for that what they're looking for without goint through the page
* Displays the stats from the market, such as market cap and exchange rate, so users instantly get an understanding of the size and positioning of Æternity
* Displays detailed information about the last mined block, so users can quickly scan the latest update on the chain
* Displays the last tree blocks and most important information, so users have an understanding of the recent progress of the blockchain

<img src='/sprint-07-release/img/blockchain-explorer-home.png' width='750px' />

### Blocks overview
* Displays the last 10 blocks, with most important information
* Time since mined is always positioned in the upper right corner, so that the user has an idea of the current

<img src='/sprint-07-release/img/blockchain-explorer-blocks.png' width='750px' />

### Block Info
* The general information that about the block is displayed in the purple area
* Within this purple area the user can navigate back and forth in the chain of blocks
* The transactions are listed in the grey area below, with transaction information such as fee, total amount, addresses, and the kind of transaction displayed as a label.

<img src='/sprint-07-release/img/blockchain-explorer-transactions.png' width='750px' />

### Transaction Info
* The general information that about the block is still displayed in the purple area
* The transactions are listed in the grey area below, with information per transaction such as fee, total amount, addresses, and the kind of transaction displayed in a clear label.

<img src='/sprint-07-release/img/blockchain-explorer-transaction-info.png' width='750px' />


### Address Info
* Clicking on an address anywhere in the blockchain explorer leads to the detailed address information
* Here are the details of the address listed, such as amount, number of transactions, latets transactions.

<img src='/sprint-07-release/img/blockchain-explorer-address-info.png' width='750px' />


---


## 2. We started the concept/design of the decision maker æpp
The decision maker is an æpp that lets users create documents (decisions) based on a meeting that has been taken place. The author can create notes from this meeting and invite the people that took part of the meeting. When every attendee agreed to a note (quote, short text, ..), the note is closed and an agreement has took place and everyone should commit to that.  

**This is a first draft of the concept and will be updated in the following sprint**

### New Session
* A new session can be started with a big button, for starting the audio.
* After finishing the audio session, other attendees can be added directly.

<img src='/sprint-07-release/img/decision-maker-new-session.png' width='752px' />

### Session and single card
* A session can contain multiple cards (texts, that people need to accept), here the user sees which ones are closed and agreed upon and which ones are in need of attention.
* A single card can

<img src='/sprint-07-release/img/decision-maker-card.png' width='752px' />


---

## 3. We started the concept/design of the Æddress Book æpp
The Æddress Book aepp allows the user to create and save contacts—like the smartphone address book or contacs application does—in the local storage. The user can assign aliases/names to Æternity addresses and interact, e.g. send transactions, in a more user friendly and visual appealing way. The design was already put together in a click dummy and will be developed as aepp in the upcoming sprints.

### Æddress Book
* At first start, there are no saved contacts, yet

<img src='//sprint-07-release/img/aeddress-book-empty.png' width='375px' />

* Clicking/Tapping the prominent `+`-button leads the user to the next screen which shows a field for an alias/name, a field for an Æternity address and two buttons: `PASTE` an address you previously copied into your clipboard or `SCAN QR` to scan an identity which was given to you in shape of a QR code.

<img src='/sprint-07-release/img/aeddress-book-add-contact-empty.png' width='375px' />

* Once both input fields are filled, the `Save contact` button is clickable/tappable

<img src='/sprint-07-release/img/aeddress-book-add-contact-filled.png' width='375px' />

* Clicking/Tapping the `Save contact` button, leads the user back to the contact overview, now listing your first saved contact

<img src='/sprint-07-release/img/aeddress-book-one-contact.png' width='375px' />

* Next to the contacts’ alias/name, identicon—or later profile picture—and Æternity address the user finds a button to expand the action menu which when being clicked/tapped shows possible actions like sending a transaction to that contact, or sharing that contacts’ indentity with another contact

<img src='/sprint-07-release/img/aeddress-book-one-contact-action-menu.png' width='375px' />

* Clicking/Tapping the Transaction æpp’s button results in that contacts’ Æternity address being copied to the input field of the Transaction æpp where the user has to enter the amount of AE they’d like to send

<img src='/sprint-07-release/img/aeddress-book-transfer-empty.png' width='375px' />

* Entering the amount makes the `Make transaction` button clickable/tappable

<img src='/sprint-07-release/img/aeddress-book-transfer-filled.png' width='375px' />

* Clicking/Tapping the `Make transaction` button brings up a confirmation screen asking the user if they’d really like to make that transaction or not

<img src='/sprint-07-release/img/aeddress-book-transfer-confirmation.png' width='375px' />

* If willing to make the transaction, you’ll be returned to the Æddress Book and get a notification, that your AE tokens were sent

<img src='/sprint-07-release/img/aeddress-book-transferred-and-multiple-contacts.png' width='375px' />
