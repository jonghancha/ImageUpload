# ImageUpload

Manifests : 
            
            <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
            <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
            <uses-permission android:name="android.permission.INTERNET" />
    3가지 생성.

Gradle(Module):
             
              dependencies {
                  implementation 'com.squareup.okhttp3:okhttp:4.10.0-RC1'
               } 

XML :
ImageView, Button 생성

MainActivity :   본인 IP로 바꾸기 .

****
App install후 에뮬레이터의 setting으로 들어가서 -> 앱 설정 -> 이 앱의 이름으로 들어간 후 
-> 권한(Permissions)으로 들어 간후 -> Media Allowed로 설정. 

JSP:
    /usr/local/apache-tomcat-8.5.46/webapps/ROOT 로 들어가서 
    폴더 생성.
