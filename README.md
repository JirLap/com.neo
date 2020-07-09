SZ Neo Coolcam Z-Wave device APP for Homey
   
Donations will be used for charity. Every 25 euros collected will be send to a different charity organization every time. I make this app for fun and don’t tend to make profit for my own.
If you like the work. Please think of the people who you could please a bit by donating.
Want the next donation to go to your favorite charity ? Don’t hesitate and tell me what it is.
   
Supported devices with most common parameters:
NAS-PD01ZE, Motion Sensor  
NAS-PD02ZE, Motion Sensor V2 
NAS-WR01ZE, Power Switching Plug  
NAS-WR02ZE, Power Switching Plug V2  
NAS-SC01ZE, Touch Wall Switch Single  
NAS-SC02ZE, Touch Wall Switch Dual  
NAS-SC03ZE, Touch Wall Switch Triple  
NAS-CS03ZE, Curtain Controller     
NAS-AB01ZE, Siren / Doorbell speaker   
NAS-AB02ZE, Siren / Doorbell speaker V2   
NAS-RC01ZE, Remote KeyFob / Alarm Button   
NAS-RS01ZE, Remote Emergency Button   
NAS-DS01ZE, Door Sensor  
NAS-DS07ZE, Door Sensor V2 - Testing Fase     
NAS-WS01ZE, Flood Sensor   
    
Supported devices with some parameters:    
None until Neo releases new products    
   
Supported Languages:
English    
Dutch    
German   
   
Support notes:

Most reliable way to update battery powered devices   
1. Place the sensor near Homey (< 1 meter)   
2. Change the settings to the values you want   
3. Wake up the sensor (triple click the button)   
4. During the blinking of the LED (indicating connection to Homey) press "save settings"   
    
If problems persists:    
a. Temporarely disable other Z-wave apps   
b. change the setting to another value with above steps   
c. check if effective and retry to the desired value    
     
Change Log:  
     
2.1.3   
Made report parsers for V1 plug independend from the homey-mesh-driver.    
Finished ( i hope so :) ) the code for the curtain contoller.   
Setting changes for the Pir V1.   
           
2.1.2    
Fix for V2 plugs and negative value reported back - THX 2 nlrb.            
	 
2.1.1   
Corrected "includeSecure": false placement. No secure adds until Athom fixes the S2 and delays on secure devices.   
Added test code for curtain controller.    
Fixed some language errors.   
Added some more device ID's that users reported.    
Fixed settings for the v2 plugs     
     
2.1.0 - Initial Beta Release - Breaking Changes for Wall Switch !!         
Added support Homey Energy. 
Added support for Touch Wall Switch Triple    
Driver split the Power Switching Plug V1 and V2 version - Could need re-pair of the Power Switching Plug V2.  
Renamed wall switch driver names to the changed Coolcam naming - Will need re-pair of the Touch Wall Switch Dual.  
Change: All battery powered devices are forced unsecure to avoid the problems in the Homey z-wave core.  
         
2.0.21      
Added support for Doorsensor RU and NZ region / Added support for PIRv1 RU region.   	
	
2.0.20      
Added German Translation to the app.    
Minimum homey firmware 2.0.5 - Time for all to update and dump V1 series.	
	
2.0.19      
Update setting for PIRv2 detection led Enable/Disable      
	
2.0.18      
Extra setting added to the v2 PIR "Motion detection event report"   
	
2.0.17      
Again back to the old mesh driver. Now updates dont get pushed to Homey   
	
2.0.16      
Updated to latest mesh driver again after fixes being done by Athom 
	
2.0.15      
Added new EU device ID's to the app for PowerPlug   
    
2.0.14      
Switched back to the old mesh driver since the new one breaks reporting in the homey core     
  
2.0.13     
Fixed missing "signed": false in Doorbell/Siren
  
2.0.12     
Added some device ID's from the PIR      
        
2.0.11   
Added some device ID's from the PIR, Siren and Plug   
Update to latest Mesh-Driver   
  
2.0.10   
Small update for the PIRv2    
Update to latest Mesh-Driver 
   
2.0.9   
Small update for single wall switches  
   
2.0.8   
Added the new forum and issue links for the new appstore layout 
    
2.0.7   
First reports came in of a real PIR v2 so its added with lightspeed        
    
2.0.6   
Meter Reset in driver on WR01Z Plugs after support dropped in the Z-Wave Mesh driver after issues     
   
2.0.5   
Water Sensor not reporting in on leakage  
Motion Sensor sensitivity settings    
   
2.0.4     
Added fix from z-wave mesh driver that should fix some trouble with the dual switches and a specific firmware version       
	
2.0.3 - Stable Release from beta SDKv2 versions      
Added volume action cards for siren and doorbell mode NAS-AB01ZE    
	
2.0.2  
Fixed Siren Trigger card that did not fire correct    
Updated more device icons for better experience    
      
2.0.1    
Added support for the KeyFob/ Emergency Remote Control   
Added support for the SOS Remote button     
Updated device icons for better appstore experience    
Updated some device svg icons for better experience on Homey     
	
2.0.0    
Moved App to zwave-mesh driver and SDKv2   
Added all other know country/regio id's known in de z-wave alliance database in the app    
Added support for the NAS-SC01ZE Touch Wall Switch Single    
Added empty driver for PD02 so it shows in appstore as device icon/tile    
 
1.1.23    
 
NAS-SW01ZE - Support for V1 and V2 Touch Wall Switch Dual  

1.1.22    
all - Add productDocumentation and unlearnmode    
all - Updated NEO branded images    

1.1.21    
     
NAS-AB01ZE - Add action card for setting alarm or doorbell tune    
NAS-AB01ZE - Fixed alarm state action card    

1.1.20    
     
NAS-DS01ZE - Settings naming error corrected (basic_set_level)       

1.1.19
 
NAS-SW01ZE - updated driver, tested and working ok (re-pair of device required)   
NAS-SW01ZE - Add switch LED action card to enable / disable the LED's   
NAS-AB01ZE - Updated action card for alarm mode (Siren / Doorbel)   
NAS-AB01ZE - Updated action card for alarm state (Sound / Silence)  
Updated Z-wave driver (1.1.8)   

1.1.18
NAS-AB01ZE - Add Siren / Doorbel switch mode action card    
Updated Z-Wave driver (1.1.6)    

1.1.17
NAS-WR01ZE - Add Power Meter reset flow card    

1.1.16
All devices - update battery_alarm, code clean-up, minor fixes   

1.1.15
NAS-SW01ZE - Defined multinode 1, should be done by itself but made sure multinode 1 is also defined just i case this might ever change.    

1.1.14
NAS-AB01ZE - Updated mobile card to show battery alarm and toggle on icon     
Somehow battery reporting has stopped again with the Homey 1.1.4 firmware.  
In order to get it working again re-pair of device is required, for now this looks like the only solution.  

1.1.13
Support for GetOnWakeUp in Z-Wave driver enabled
Updated Z-Wave driver

1.1.12
(Only released in Developers Preview for testing)

1.1.11
NAS-AB01ZE - Updated driver for compatibility 1.1.3 firmware     
NAS-DS01ZE - Updated driver for compatibility 1.1.3 firmware     
NAS-PD01ZE - Updated driver for compatibility 1.1.3 firmware       
NAS-WS01ZE - Updated driver for compatibility 1.1.3 firmware     
NAS-WR01ZE - Updated driver for compatibility 1.1.3 firmware (standardized custom capabilities)     

1.1.10
NAS-AB01ZE - Add battery alarm and updated battery reporting + All settings added so the siren can also be used as doorbell speaker   
NAS-DS01ZE - Add battery alarm and updated battery reporting + All settings added     
NAS-PD01ZE - Add battery alarm and updated battery reporting   
NAS-WS01ZE - Add battery alarm and updated battery reporting    
NAS-WR01ZE - re-added custom capabilities due to delays on Homey v1.1.3   


Older changelog notes have been ereased from this timeline......