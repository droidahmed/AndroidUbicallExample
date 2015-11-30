# AndroidUbicallExample
android example for UbiCall SDK

Install the SDK

add the following 

    repositories {
       maven {
          url  "http://dl.bintray.com/ubicall/maven"
      }
    }

    compile 'com.ubicall.sand:ubicall.lite:1.0.1'


Initialization of SDK

     UbiCall_InitSdk sdk = UbiCall_InitSdk.getInstance();
     sdk.setLicenseKey("your license key");
     sdk.invoke(MyActivity.this);
    
   Example
    
     UbiCall_InitSdk sdk = UbiCall_InitSdk.getInstance();
           sdk.setLicenseKey("your license key");
                sdk.invoke(MyActivity.this);
                
                
  Notes:

  Disable landscape orientation, since this release doesn't support landscape orientation. 
