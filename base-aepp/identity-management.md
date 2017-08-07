# Manage Identities

A user can have multiple Identities, each identitiy has a token balance. An æepp with access to a specific identitiy has full control of the balance and can use the æternity tokens of this identitiy. A user can authorise multiple æpps to use one identity.



Identities can be private or public, as explained in the [onboarding](onboarding.md), and are represented as cards.



## Dashboard
![3.1 - ID Manager - Dashboard Total.jpg](screens/3.1-id_manager-dashboard_total.jpg)

The Dashboard is an overview of the following items:
1.	**Identities**: The first card is a combined view of all identities, swiping to the right shows more cards, which represent the most frequently used identities.
1.	**Balance Summary of the last week**, this information depends on the selected card.
1.	**Recent transactions**, from the selected card.
1.	**Currency History** shows the changes in fiat value of AET.


![3.2 - ID Manager - Dashboard ID.jpg](screens/3.2-id_manager-dashboard_id.jpg)

When a specific identity is selected in the Dashboard, only transactions from it are shown.

---


![4.2 - ID Manager - My Identities - Sidemen.jpg](screens/4.2-id_manager-my_identities-sidemenu.jpg)

A sidemenu provides access to additional functionality.

## My Identities

This is the area where the user can manage identities and access the detail view of a specific identity.


![4.1 - ID Manager - My Identities.jpg](screens/4.1-id_manager-my_identities.jpg)

A list view of all identities. The most frequently used identities are shown at the top.


---


![4.3 - ID Manager - My Identities - Scrolled.jpg](screens/4.3-id_manager-my_identities-scrolled.jpg)

All Identities, scrolled down.

---


![4.4 - ID Manager - My Identities - Search.jpg](screens/4.3-id_manager-my_identities-scrolled.jpg)

When the user taps the search field and enters an identity name, a matching results list is shown. This is handy when a user has a lot of identities.

---


![4.5 - ID Manager - Identity Details.jpg](screens/4.5-id_manager-identity_details.jpg)

The detail view of an identity is similar to the Dashboard, with the following additional items: Authorized æpps and a graph that shows the recent balance of this identity.

---


![4.6 - ID Manager - Identity Details - Authorised Æpp.jpg](screens/4.6-id_manager-identity_details-authorised_aepp.jpg)

An authorised æpp has been selected. In this view the user sees the transactions, which were made by the authorized æpp. The user has the option to revoke æpp authorisation.

---


## Transfer Tokens between Identities
![5.2 - ID Manager - Internal Transfer - Sidemenu.jpg](screens/5.2-id_manager-internal_transfer-sidemenu.jpg)



---

![5.1 - ID Manager - Internal Transfer.jpg](screens/5.1-id_manager-internal_transfer.jpg)

The user can make internal transactions here. In the upper area the user can add an amount of AE Tokens. ‘Transfer from’ shows the identity where the transfer is coming from. ‘Transfer to’ shows the identity which will receive the tokens transfer.

---





![5.3 - ID Manager - Internal Tranfer - Amount.jpg](screens/5.3-id_manager-internal_tranfer-amount.jpg)


---

![5.4 - ID Manager - Internal Transfer - Transfer.jpg](screens/5.4-id_manager-internal_transfer-transfer.jpg)



---


## Revoke authorization
If a user has a lot of different identities, they might lose track of which æpp has access to which identity. In this case they might search for a specific æpp to review the transactions and revoke its authorisation. 

![6.2 - ID Manager - Authorised Æpps - Sidemen.jpg](screens/6.2-id_manager-authorised_aepps-sidemenu.jpg)

Sidemenu, when Authorised æpps is the current view.

---
![6.1 - ID Manager - Authorised Æpps.jpg](screens/6.1-id_manager-authorised_aepps.jpg)

A list of all authorized æpps. Clicking on each identity shows its details.

---


![6.3 - ID Manager - Authorised Æpps - Details.jpg](screens/6.3-id_manager-authorised_aepps-details.jpg)

This view lists all the transactions, made by an authorized æpp (connected to a given identity). The user has the option to revoke authorization. This is the same view as 4.6.
