# NodeRed Honeywell Lyric API
Access hoenywell lyric API with node red
# Integrating Node Red and Honeywell Lyric API
This will detail step by step how to gain access to the Honeywell Lyric API, create a Lyric App to access connect devices and integrate into Node Red
## 1)Node Red

* Create new tab  - give it a meaningful name (Honeywell Lyric Integration)
* Import from clipboard - [HoneywellLyricAPI_Flow](HoneywellLyricAPI_Flow)
* Deploy flow
## 2)Honeywell Developer Site
Here you will create an App that will allow access to your Honeywell Lyric devices through there API.

### 2.1)Create account
[Honeywell Developer](https://developer.honeywell.com/):
<img src='/images/signup.jpg'/>

### 2.2)Create App
<img src='/images/createApp.jpg'/>

### 2.3)Name App
<img src='/images/appName.jpg'/>

### 2.4)App created get Keys
<img src='/images/appCreated.jpg'/>

Copy Consumer Key and Consumer Secret to be used later

### 2.5)Save Keys in Node Red
In a local browser goto the base url for your node red application /lyric
and enter the required information and press "Save data"
<img src='/images/saveData.jpg'/>

### 2.6)Submit
Press the "Submit" button to be taken to the your Honeywell App login page
<img src='/images/submit.jpg'/>

### 2.7)Log On and Allow access
<img src='/images/logOn.jpg'/>
<img src='/images/allow.jpg'/>

### 2.8)Select devices and Connect
<img src='/images/connect.jpg'/>

