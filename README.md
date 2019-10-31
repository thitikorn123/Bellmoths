# Bellmoths


ionic3 login facebook android!!!!

1: ionic cordova plugin add cordova-plugin-facebook4 --variable APP_ID="123456789" --variable APP_NAME="myApplication" // แกี่ id และ appname ของตัวเอง

2: npm install --save @ionic-native/facebook@4

3:แก้ไฟ .xml

4: import { Facebook} from '@ionic-native/facebook'; //ลงใน app.module

// แล้วเพิ่มตรง: providers: [ Facebook, {provide: ErrorHandler, useClass: IonicErrorHandler} ]

5: import { Facebook, FacebookLoginResponse } from '@ionic-native/facebook'; // ในไฟล์ home.ts

6: ionic cordova add platform android

7: ionic cordova build android // จะได้ไฟล์ .apk มาตามเส้นทางด้านล่าง

\platforms\android\app\build\outputs\apk
