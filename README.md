# RCTWebRTCDemo
Demo for https://github.com/oney/react-native-webrtc
## Usage
- Clone the repository, run `npm install`.  
- For iOS, run the project on Xcode.  
- For Android, run `react-native run-android` in the directory.  

You can run the app in Device/Simulator, or open https://react-native-webrtc.herokuapp.com.   
Enter the same room ID(any word such as hello, yoyo, etc) in two or more devices or browers, the audio and video stream will be connected.

## NOTE
- Don't run it on iOS simulator, or change to `navigator.getUserMedia({"audio": true, "video": false})` to test audio only.
