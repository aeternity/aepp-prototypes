# Manage Identities

A user can have multiple Identities, each identitiy has a token balance. An æepp with access to a specific identitiy has full control of the balance and can use the æternity tokens of this identitiy. A user can authorise multiple æpps to use one identity.



Identities can be private or public, as explained in the [onboarding](onboarding.md), and are represented as cards.



## Dashboard
<img src="screens/3.1-id_manager-dashboard_total.jpg" width='375px'>

The Dashboard is an overview of the following items:
1.	**Identities**: The first card is a combined view of all identities, swiping to the right shows more cards, which represent the most frequently used identities.
1.	**Balance Summary of the last week**, this information depends on the selected card.
1.	**Recent transactions**, from the selected card.
1.	**Currency History** shows the changes in fiat value of AET.


<img src="screens/3.2-id_manager-dashboard_id.jpg" width='375px'>

When a specific identity is selected in the Dashboard, only transactions from it are shown.

---


<img src="screens/4.2-id_manager-my_identities-sidemenu.jpg" width='375px'>

A sidemenu provides access to additional functionality.

## My Identities

This is the area where the user can manage identities and access the detail view of a specific identity.


<img src="screens/4.1-id_manager-my_identities.jpg" width='375px'>

A list view of all identities. The most frequently used identities are shown at the top.


---


<img src="screens/4.3-id_manager-my_identities-scrolled.jpg" width='375px'>

All Identities, scrolled down.

---


<img src="screens/4.3-id_manager-my_identities-scrolled.jpg" width='375px'>

When the user taps the search field and enters an identity name, a matching results list is shown. This is handy when a user has a lot of identities.

---


<img src="screens/4.5-id_manager-identity_details.jpg" width='375px'>

The detail view of an identity is similar to the Dashboard, with the following additional items: Authorized æpps and a graph that shows the recent balance of this identity.

---


<img src="screens/4.6-id_manager-identity_details-authorised_aepp.jpg" width='375px'>

An authorised æpp has been selected. In this view the user sees the transactions, which were made by the authorized æpp. The user has the option to revoke æpp authorisation.

---


## Transfer Tokens between Identities
<img src="screens/5.2-id_manager-internal_transfer-sidemenu.jpg" width='375px'>



---

<img src="screens/5.1-id_manager-internal_transfer.jpg" width='375px'>

The user can make internal transactions here. In the upper area the user can add an amount of AE Tokens. ‘Transfer from’ shows the identity where the transfer is coming from. ‘Transfer to’ shows the identity which will receive the tokens transfer.

---





<img src="screens/5.3-id_manager-internal_tranfer-amount.jpg" width='375px'>


---

<img src="screens/5.4-id_manager-internal_transfer-transfer.jpg" width='375px'>



---


## Revoke authorization
If a user has a lot of different identities, they might lose track of which æpp has access to which identity. In this case they might search for a specific æpp to review the transactions and revoke its authorisation. 

<img src="screens/6.2-id_manager-authorised_aepps-sidemenu.jpg" width='375px'>

Sidemenu, when Authorised æpps is the current view.

---
<img src="screens/6.1-id_manager-authorised_aepps.jpg" width='375px'>

A list of all authorized æpps. Clicking on each identity shows its details.

---


<img src="screens/6.3-id_manager-authorised_aepps-details.jpg" width='375px'>

This view lists all the transactions, made by an authorized æpp (connected to a given identity). The user has the option to revoke authorization. This is the same view as 4.6.
