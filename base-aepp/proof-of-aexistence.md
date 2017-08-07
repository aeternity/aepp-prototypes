# Proof of æxistence example

The Proof of æxistence æpp provides a easy to use interface to create hashes of files and store them on the æternity blockchain, inside of a smart contract (as a undeniable proof a file existed at a certain time in the past).


You can find a click dummy of this app [here](https://aeternity.github.io/aepp-aexistence).

This is a standalone æpp. It has to be authorised by the Identity Manager æpp, to be able to spend funds on creating the proofs. After the introduction, the æpp switches to the Identity Manager æpp for authorisation.

This æpp should become a best practice example on how to create a rich user experience for æternity blockchain æpps.


## Intro

Using the same introduction mechanism as in the Identity Manager æpp creates a unified UX for novice users. The key concepts of the æpp are explained in 3 - 5 sentences.

In the end of the intro the user is asked to authorise the æpp in the Identity Manager æpp. This leads the user to creating an identity or picking an existing one. Most æpps need to be connected with an identity for a full user experience.


![7.1 - PoE - Intro.jpg](screens/7.1-poe-intro.jpg)

---


![7.2 - PoE - Intro - Proofs.jpg](screens/7.2-poe-intro-proofs.jpg)


---


![7.3 - PoE - Intro - Open ID Manager.jpg](screens/7.3-poe-intro-open_id_manager.jpg)


## Authorize in Identity Manager

The Identity Manager æpp opens up the authorisation screen. The user will be directed back to the Proof of æxistance æpp, after she successfully authorized the æpp with one of her identities. 

[Jump to: Authorization](authorization.md)

## Authorized - Create a proof

The main functinallity of an æpp is the default screen after successful authorisation. 

In an authorised æpp, the connected identity is always shown in the bottom and displays relevant information, such as balance.


![8.1 - PoE - Arrived Back - Authorised.jpg](screens/8.1-poe-arrived_back-authorised.jpg)


---


![9.1 - PoE - Onboarding - Create First.jpg](screens/9.1-poe-onboarding-create_first.jpg)

The conversational interface learns the users intentions and information by asking simple questions.

The underlying complexity is hidden from the user. Whenever she doesn't understand the necessity of an action or simply wants know more about the topic, she can ask a simple question.


---


![9.2 - PoE - Onboarding - Camera.jpg](screens/9.2-poe-onboarding-camera.jpg)

Proofs can be created from different media sources. Files, gallery images, or directly from the camera. In the future uploading videos, messages, and sensor data will be possible, too.

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

Sidemenu.

---


![11.1 - PoE - My Proofs.jpg](screens/11.1-poe-my_proofs.jpg)

A list of all proofs, which a user created.

---


![11.2 - PoE - Single Proof.jpg](screens/11.2-poe-single_proof.jpg)

A detail view of a proof. Here the user can see more information and share it with others to get additional confirmations.


## Next
[Jump to: Identity Management](identity-management.md)
