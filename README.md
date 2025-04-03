Folder access url :  /Users/mp-tas-06/Desktop/ 
Issue  : Permission denied
Solution : sudo chmod -R 777 /Users/mp-tas-06/Desktop/toyflix_app
 issue : > Task :app:installDebug FAILED
Solution :  cd android
 ./gradlew clean
 cd ..

8288873576  for keystone command to check SHA certificate  keytool -list -v -keystore android/app/release-key.keystore
 keystore file : 9e7532f9be5c1ff4d4b5baa0d8a631f02c391f254a5b234302c405adecfec870 
61006e00640072006f0069006400  SHA1: 6F:C9:EE:73:67:79:9E:CB:A1:58:89:88:89:82:0E:3E:3D:9B:62:ED
SHA256: 44:92:63:8C:47:A8:58:9C:6F:97:CB:EC:82:2D:44:2B:5E:C8:35:54:00:E0:BF:69:BB:6D:83:35:F5:7D:7F:BE pass-android  SHA1: 6F:C9:EE:73:67:79:9E:CB:A1:58:89:88:89:82:0E:3E:3D:9B:62:ED
         SHA256: 44:92:63:8C:47:A8:58:9C:6F:97:CB:EC:82:2D:44:2B:5E:C8:35:54:00:E0:BF:69:BB:6D:83:35:F5:7D:7F:BE  --reset-cache   Build - name/org - was android   keytool -genkeypair -v -keystore my-release-key.keystore -alias my-key-alias -keyalg RSA -keysize 2048 -validity 10000
[ MYAPP_UPLOAD_STORE_FILE=my-upload-key.keystore
MYAPP_UPLOAD_KEY_ALIAS=my-key-alias
MYAPP_UPLOAD_STORE_PASSWORD=***
MYAPP_UPLOAD_KEY_PASSWORD=***
  
signingConfigs {
        release {
            if (project.hasProperty('MYAPP_RELEASE_STORE_FILE')) {
                storeFile file(MYAPP_RELEASE_STORE_FILE)
                storePassword MYAPP_RELEASE_STORE_PASSWORD
                keyAlias MYAPP_RELEASE_KEY_ALIAS
                keyPassword MYAPP_RELEASE_KEY_PASSWORD
            }
        }
    } 
cd android
./gradlew assembleRelease  form abb file  cd android
./gradlew bundleRelease
  npx jetify   SHA1: 6F:C9:EE:73:67:79:9E:CB:A1:58:89:88:89:82:0E:3E:3D:9B:62:ED
         SHA256: 44:92:63:8C:47:A8:58:9C:6F:97:CB:EC:82:2D:44:2B:5E:C8:35:54:00:E0:BF:69:BB:6D:83:35:F5:7D:7F:BE   npx react-native-clean-project npx pod-install npx react-native run-ios   // for to many files mp-tas-06@MP-TAS-06s-MacBook-Pro cem % rm -rf node_modules
npm install // Xcode open TOYFLIX.xcworkspace  for google map integration in android  add       <meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="AIzaSyBSmR_4NGj67Q7Mv0-MeSOcytuc2RuUMIc"/>
File below application in android manifest  for pod error first step to do rm -rf node_modules
npm install
cd ios
pod install --repo-update
cd ..




PUSH NOTIFICATION
https://github.com/sheikhadnan387/Push-Notification-IOS/blob/main/App.tsx
Step1:
yarn add @react-native-firebase/app
yarn add @react-native-firebase/messaging
cd ios/ && pod install

Step2:
Configure firebase in IOS side.
Download the GoogleService-Info.plist file
Right click on the project name and "Add files" to the project.
Configure Firebase with iOS credentials

Step3:
Add firebase.json file
and add these lines of code 
{
  "react-native": {
    "analytics_auto_collection_enabled": false,
    "messaging_auto_init_enabled": false,
    "messaging_ios_auto_register_for_remote_messages": true
  }
}

Step4:
Add Developer account

//Add two Capability 
Step5:

Add Background Modes and check
1.Background fetch
2.Remote Notification

Step6:
Add notification capability

Step7:
Add APNs Auth key
key Id --------
Team Id --------
Upload file  .p8 

Step8:

//Install these packages
yarn add @react-native-firebase/messaging
yarn add @notifee/react-native
yarn add react-native-permissions

Step9:
Make fcm Method helper ClassStep1:
yarn add @react-native-firebase/app
yarn add @react-native-firebase/messaging
cd ios/ && pod install

Step2:
Configure firebase in IOS side.
Download the GoogleService-Info.plist file
Right click on the project name and "Add files" to the project.
Configure Firebase with iOS credentials

Step3:
Add firebase.json file
and add these lines of code 
{
  "react-native": {
    "analytics_auto_collection_enabled": false,
    "messaging_auto_init_enabled": false,
    "messaging_ios_auto_register_for_remote_messages": true
  }
}

Step4:
Add Developer account

//Add two Capability 
Step5:

Add Background Modes and check
1.Background fetch
2.Remote Notification

Step6:
Add notification capability

Step7:
Add APNs Auth key
key Id --------
Team Id --------
Upload file  .p8 

Step8:

//Install these packages
yarn add @react-native-firebase/messaging
yarn add @notifee/react-native
yarn add react-native-permissions

Step9:
Make fcm Method helper Class
YT-https://www.youtube.com/watch?v=TsGwqkqsK-M
  


Websocket const WebSocket = require('ws');
const wss = new WebSocket.Server({ port: 8080 });

wss.on('connection', (ws) => {
  console.log('A new client connected!');
  
  ws.on('message', (message) => {
    console.log('received: %s', message);
  });
  
  ws.send('Hello from server!');
});

console.log('WebSocket server running on ws://localhost:8080');

pm2 start npx --name client29 -- serve -s build -l 3001  mongosh mongodb+srv://cumulus545:techarch12@cumulus2024.ibscb.mongodb.net/?retryWrites=true&w=majority&appName=Cumulus2024    for forntenmd live npm install -g serve pm2 start npx --name client -- serve -s build -l 3001
pm2 stop client
 and for backend live npm install -g pm2 pm2 save pm2 list
pm2 startup pm2 start server.js --name backend
      const handleKeyboardShow = () => {
    Animated.timing(translateY, {
      toValue: -80,
      duration: 300,
      easing: Easing.ease,
      useNativeDriver: true,
    }).start();
  };
  const handleKeyboardHide = () => {
    Animated.timing(translateY, {
      toValue: 0,
      duration: 300,
      easing: Easing.ease,
      useNativeDriver: true,
    }).start();
  };
  for azure ssh -i mykey.pem azureuser@52.140.65.161   



this is for stripe webhok check through stripe and local console  stripe listen --forward-to https://www.cumulus.rip/api/payment/webhook  stripe listen --forward-to https://www.cumulus.rip/api/payment/webhook
 stripe trigger checkout.session.completed


   curl command for stripe testing  curl https://api.stripe.com/v1/checkout/sessions \
-u sk_test_51QygE8J7Fy59EZyjwviXS519H89vUeNK7lQpuMqX4NSmii685UrJWyF54Eselqwj5fezXHje7hqr2JfntK7eFO8800fVZ3uoqk: \
-d "payment_method_types[0]=card" \
-d "line_items[0][price]=price_1R1LqpJ7Fy59EZyjdOgMSCD0" \
-d "line_items[0][quantity]=1" \
-d "mode=subscription" \
-d "success_url=http://localhost:3001/enterdashboard" \
-d "cancel_url=http://localhost:3001/login" \
-d "metadata[user_id]=676403f8493a5b89a32c543e" \
-d "metadata[planType]=legacyPremium" \
-d "metadata[duration]=yearly" \
-d "metadata[startDate]=2025-03-11" \
-d "metadata[endDate]=2026-03-11"
      curl https://api.stripe.com/v1/checkout/sessions \
-u sk_test_51QygE8J7Fy59EZyjwviXS519H89vUeNK7lQpuMqX4NSmii685UrJWyF54Eselqwj5fezXHje7hqr2JfntK7eFO8800fVZ3uoqk: \
-d "payment_method_types[0]=card" \
-d "line_items[0][price]=price_1R1LqpJ7Fy59EZyjdOgMSCD0" \
-d "line_items[0][quantity]=1" \
-d "mode=subscription" \
-d "success_url=http://localhost:3001/enterdashboard" \
-d "cancel_url=http://localhost:3001/login" \
-d "metadata[user_id]=676403f8493a5b89a32c543e" \
-d "metadata[planType]=legacyPremium" \
-d "metadata[duration]=yearly" \
-d "metadata[startDate]=2025-03-11" \
-d "metadata[endDate]=2026-03-11"      

 for app ipload test 

https://www.diawi.com/  and for firebase

 https://www.youtube.com/watch?v=ma0UYQ_VpMw&t=1200s https://rnfirebase.io/
