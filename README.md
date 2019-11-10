# Play-video-in-React-Native

Link youtube video: https://www.youtube.com/watch?v=swigQ10SL_w<br/>
Link live demo on Expo: https://snack.expo.io/By4scwYIm<br/>
********STEPS********
<pre>
ENGLISH VERSION:
- Step 1: Install module 'react-native-video'
npm install --save react-native-video
- Step 2: Link module 'react-native-videos' to project
react-native link react-native-video
=>>> Note: if we run project right now, we will have an error. So, we need edit file 
'./android/settings.graddle':
+ Change path '../node_modules/react-native-video/android-exoplayer' to '../node_modules/react-native-video/android'
- Step 3: Init video's attributes and events:
-- attributes --
+ rate
+ paused
+ volume
+ muted
+ resizeMode
+ repeat
+ duration // set on event onLoad
+ currentTime // set on event onProgress
-- events --
+ onLoad
+ onProgress
+ onEnd
- Step 4: Add functions: play (from anytime), pause, mute, repeat, speed

----------------------------------------------------------------

VIETNAMESE VERSION:
- Bước 1: Cài module 'react-native-video'
npm install --save react-native-video
- Bước 2: Liên kết module 'react-native-video' tới project
react-native link react-native-video
=>>> Lưu ý: lúc này nếu chạy project thì sẽ bị lỗi, do vậy cần vào file './android/settings.graddle'
chỉnh sửa 1 chút:
+ Chỉnh đường dẫn '../node_modules/react-native-video/android-exoplayer' thành '../node_modules/react-native-video/android'
- Bước 3: Khởi tạo các thuộc tính và sự kiện cần thiết cho video:
-- thuộc tính --
+ rate
+ paused
+ volume
+ muted
+ resizeMode
+ repeat
+ duration // thiết lập trên sự kiện onLoad
+ currentTime // thiết lập trên sự kiện onProgress
-- sự kiện --
+ onLoad
+ onProgress
+ onEnd
- Bước 4: Thêm các chức năng chơi, dừng, tắt tiếng, lặp lại, chỉnh tốc độ

---DONE :D---
---Quang Vi---
</pre>
