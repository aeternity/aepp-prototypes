# Proof of Æxistence example

The Proof of Æxistence æpp provides a easey to use interface to create hashes of files and store them on the aeternity blockchain inside of a smart contract as a undeniable proof a file existed at a certain time in the past.


You can find a click dummy of this app [here](https://aeternity.github.io/aepp-aexistence).

This is a standalone æpp. It hase to authorize against the base æpp at some point to be able to spend funds on creating the proofs. After the introduction, the æpp switches to the base app for this request.

This æpp should become a best practice example on how to create a rich user experience for æternity blockchain æpps.


## Intro

Using the same introduction mechanism as in the base app creates a unified UX for novice users. The key concepts of the æpp should be explained in 3 - 5 sentences.

In the end of the intro the user is asked authorize the æpp in the base æpps identity manager. This will lead to creating an identity or pick an identity that exists already. Most æpps need to be connected with an identity for a full experience.


![7.1 - PoE - Intro.jpg](screens/7.1-poe-intro.jpg)

---


![7.2 - PoE - Intro - Proofs.jpg](screens/7.2-poe-intro-proofs.jpg)


---


![7.3 - PoE - Intro - Open ID Manager.jpg](screens/7.3-poe-intro-open_id_manager.jpg)


## Authorize in Identity Manager

The base æpp opens up the authorization screen. The user will be directed back to the Æxistance æpp after she successfully authorized the æpp with one of her identities. 

[Jump to: Authorization](authorization.md)

## Authorized - Create a proof

The main functinallity of an æpp should be the default screen after successful authorization. 

In an authorised æpp, the connected identity is always shown in the bottom and displys relevant information such as balance.


![8.1 - PoE - Arrived Back - Authorised.jpg](screens/8.1-poe-arrived_back-authorised.jpg)


---


![9.1 - PoE - Onboarding - Create First.jpg](screens/9.1-poe-onboarding-create_first.jpg)

Forms are boring, so this conversational interface figures out the users intentions and information that are relevant, by asking simple questions.

The underlying complexity is hidden from the user. Whenever she doesn't understand the neccecity of an action or simply wants know more about the topic, she can retreive them with a simple question.


---


![9.2 - PoE - Onboarding - Camera.jpg](screens/9.2-poe-onboarding-camera.jpg)

Proofs can be created from different media source. Files or images from the gallery or directly form the camera. In the future even videos, messages and sensor data are possible.

---

![9.3 - PoE - Onboarding - Take Photo.jpg](screens/9.3-poe-onboarding-take_photo.jpg)

The camera has been chosen to create a proof.

---


![9.4 - PoE - Onboarding - Add Name.jpg](screens/9.4-poe-onboarding-add_name.jpg)

---

![9.5 - PoE - Onboarding - Name Added.jpg](screens/9.5-poe-onboarding-name_added.jpg)

---

![9.6 - PoE - Onboarding - Make Transaction.jpg](screens/9.6-poe-onboarding-make_transaction.jpg)

---

![9.7- PoE - Onboarding - Confirm Transaction.jpg](screens/9.7-_poe-onboarding-confirm_transaction.jpg)

Creating a proof costs æternity tokens. The transaction has to be confirmed by the user.

---


![10.1 - PoE - Sidemenu.jpg](screens/10.1-poe-sidemenu.jpg)

Sidemenu

---


![11.1 - PoE - My Proofs.jpg](screens/11.1-poe-my_proofs.jpg)

A list of all created proofs

---


![11.2 - PoE - Single Proof.jpg](screens/11.2-poe-single_proof.jpg)

A detailed view of a proof. Here the user can see more information and share it with others to get more confirmations.


## Next
[Jump to: Identity Management](identity-management.md)
