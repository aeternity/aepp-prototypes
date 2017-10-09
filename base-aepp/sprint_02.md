# Sprint 02

Our goal of this sprint was to make the first æternity æpps available to mobile users. Therefore we developed an own authorization script, that can create new accounts via passphrase and PIN, as well as recover existing ones.

Multiple identities, containing a public address and a Token balance, can be created. The active ID can be selected.

We then designed a clean screen flow, that contains those features and leads the user in a self-explanatory way.

Æpps can be accessed and payments can be authorized through this interface. The active ID can be switched without leaving the æpp.


## Intro
The intro screens explain the core concepts of the æternity blockchain. 
<img src="screens/sprint_02/0.00-base-intro" width='375px'>

---
Users can login to an existing account through their secret passphrase and PIN. 
<img src="screens/sprint_02/0.01-base-login“ width='375px'>


## Identity Creation
Users have to create at least one identity to interact with the æternity blockchain. 

The `Account Creation` dialog provides an simple interface for setting up a new main account.

Here a security phrase is given, the user is prompted to write the phrase down, and confirm that he did so.

<img src="screens/sprint_02/0.10-onboarding-passphrase.png“ width='375px'>

To protect the main account and recover it from different devices a PIN needs to be set.

---

<img src="screens/sprint_02/0.11-onboarding-pin.png“ width='375px'>

---

## Identity Manager
As the public ID is created – users are able to use the æternity æpps. From a technical point of view a public ID is an address derived from an extended private key. As long as there is only one ID, a hint is shown underneath it.

<img src="screens/sprint_02/1.01-id_manager-manage.png“ width='375px'>

Multiple derived public IDs can be created – each with a own unique adress and Token balance. Only one can be active at a time – the grey card indicates an inactive ID.

<img src="screens/sprint_02/1.02-id_manager-new_ID.png“ width='375px'>

---

Through the sidemenu users can access the Æpp Browser.

<img src="screens/sprint_02/1.03-id_manager-sidemenu.png“ width='375px'>

---

The minified ID on the bottom of the screen indicates which is active.

<img src="screens/sprint_02/1.04-id_manager-browse.png“ width='375px'>

## Identity Switcher

Because the Identity Manager works as a wrapper, users will be able to easily switch between IDs at anytime or when prompted to authorize a payment through an overlay.

<img src="screens/sprint_02/2.01-overlay-active.png“ width='375px'>

<img src="screens/sprint_02/2.02-overlay-inactive.png“ width='375px'>