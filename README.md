# Online-Offline-Budget-Trackers

## Description
<p>The Online-Offline-Budget-Trackers application allows users to keep track of their revenues and costs dynamically even without internet access. The application applies PWA that enable an offline mode for the user.</p>

## User story
<p>As a travller, I would like to log my incomes and expenses along my trip even I do not have internet access in some developing cities which do not have reliable internet quality.</p>

## Core features

### Add funds/ Subtract 
 <p> When the app loded, the user will be presented with summary of total available funds in his/her "account" with each transaction logged in the database and a chart displaying daily transactions result.</br>The user can log transactions by assigning a name and the amount to each transaction and click the corresponding buttons. The transaction will be saved to the database and displayed on the detail transaction grid below. </p> 

### Offline mode
<p>This application can also be used under offline situations. All the transactions that the user logs will be saved to IndexedDB of the browser and all the transactions that are saved while offline will be pushed to the database once the user resume internet access. </p>