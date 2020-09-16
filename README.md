# Faehr_Trade
Vending Machine and Ticketing System for Passenger Ferry 

## Hardware
- Raspberry Pi 3B+
- RFID: RC522 RF IC Reader and S50 Key Cards
- 10.1 inch Touch Display 1280x800
- Receipt Printer
- Bill and Coin Exchanger
- GSM/ 3G Transmitter
- GPS Module

## Software
- Frontend based on LVGL

## Requirements
- on both shores of the river, one ticket vending machine should be placed
- both vending machines communicate with each other over the mobile data network
- the vending machine counts how many passengers bought a ticket
- if the number of bicycles or passenger reaches a certain number, no more passnegers can buy a ticket
- the ferry driver can reset the counter of a certain vending machine when the ferry departs
- optional:
	- if a certain number of tickets have been printed, a warning to replace the thermopaper in the receipt printer is broadcasted to the maintainers (e.g. via signal or sms)
	- at the end of a day, statistics are broadcasted to select recipients
