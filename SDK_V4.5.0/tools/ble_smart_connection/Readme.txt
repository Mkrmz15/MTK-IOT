ble_smart_connection APK

# Version 1.0.9: 2017-07-04
- Add new permission for BT Scan.
- Modify TargetSDKLevel from 23 to 21.


Release List
1. ble_smart_connection.prod.apk
2. SourceCode.rar
3. Readme.txt

mt7697lib provide API��
1.bleConnect(); // connect MT7697 by BLE 
2.bleDisconnect(); // disconnect MT7697 by BLE 

3.requestWifiConnect(String ssid, String password) 
	//get WIFI Auth/Encrypt Mode by ssid��pwd��then send ssid, password and Auth/Encrypt Mode to MT7697

4.wifiChange() 
	// return MT7697 current WIFI status��1.Disconnected   2.Connected:  SSID, IP value
	
Source Code Call Library API��
1.	com.mediatek.mt7697.activities.DeviceActivity:  
mDevice.bleConnect();

2.  com.mediatek.mt7697.fragments.SmartConnectionFragment
mDevice.requestWifiConnect(ssid, password)
mDevice.wifiChange()
