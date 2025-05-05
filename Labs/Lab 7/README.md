# Lab 7 ThingSpeak and Google Sheets

*I pledge my honor I have abided by the Stevens Honor System - Nicholas Scirocco*

## ThingSpeak

I first logged into the Mathworks account and created new channels called cpu_loop with fields for cpu_pc and mem_avail_mb.

## Copy Files `thingspeak_cpu_loop.py` and `thingspeak_feed.py`

![image](https://github.com/user-attachments/assets/71c64266-8517-4338-b501-5214468fdcf7)

## `cat thingspeak_cpu_loop.py` and `cat thingspeak_feed.py`

![image](https://github.com/user-attachments/assets/16c2b6b3-7dbb-46f1-b2f9-6aa54995b5c0)

## Run `thingspeak_feed.py`

![image](https://github.com/user-attachments/assets/ec4b8846-470a-4809-b965-acc9647f2299)

![image](https://github.com/user-attachments/assets/9bd24ce5-ccd4-4673-9b5e-10e651d4d51e)

![image](https://github.com/user-attachments/assets/0453508b-12c6-4e8d-a034-15714b9399c3)


## Google Sheets

I first created a new project called cpudata on the Google Cloud Platform IAM. 

I then enabled the Google Drive and Google Sheets API for this project. 

Finally, I created a service account key and saved the .json file containing this information.

## Install Packages

![image](https://github.com/user-attachments/assets/e0179286-9ce3-44b2-aead-dbf630e6d90b)

## Copy Files `system_info.py` and `cpu_spreadsheet.py`

![image](https://github.com/user-attachments/assets/1c651f62-3660-41e1-b808-d99ec7a94b0b)

## Run `cpu_spreadsheet.py`

![image](https://github.com/user-attachments/assets/0daca2e7-b254-4dca-9293-67d2a123e18e)

## Resulting Data

![image](https://github.com/user-attachments/assets/6ef94232-afca-4f8e-9d3a-63392cd5181b)
