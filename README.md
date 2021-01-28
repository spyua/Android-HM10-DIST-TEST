# Android-HM10-TEST<br/>

This project about connecting Android, Bluetooth LE/4.0. It's designed for use with BLE/BT 4.0 modules based upon TI's CC2540. You can use the module to get the rssi value and distance betwwen cell phone and the module. 

Pls check your HM-10 module is genuine
http://fab.cba.mit.edu/classes/863.15/doc/tutorials/programming/bluetooth/bluetooth40_en.pdf



## You have to set you HM10 mode as below<br/>
Step1:AT+RENEW<br/>
Step2:AT+RESET<br/>
Step3:AT+IBEA1<br/>
Step4:AT+ROLE0<br/>
Step5:AT+IMME1<br/>
Step6:AT+MODE2<br/>
Step7:AT+RESET<br/>

## Using this app to connect HM10 and get data<br/>

1.Click Button<br/>
  Char Transfer Test<br/><br/>
2.HM10 transfer "GET" <br/>
RSSI<br/>
Distance<br/><br/>

## The arduino circuit:
 * RX is digital pin 12 (connect to TX of other device)
 * TX is digital pin 13 (connect to RX of other device)
 <br/>Console Display Set:No End Line

If you use my app to connect HM10 module(Slave mode), and use HM10 sent "GET" to cell phone.
The cell phone will feedback the RSSI and DIST to HM10. The photo as below
 
![001](https://cloud.githubusercontent.com/assets/20264622/20243272/0459fcd2-a98c-11e6-948b-7d5665f71ef2.png)
![001](https://cloud.githubusercontent.com/assets/20264622/20243184/8d724b6e-a987-11e6-92c9-d0141fe753d1.png)




