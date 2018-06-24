# Play-video-in-React-Native

Link youtube video: 

********STEPS********

----------------ENGLISH VERSION----------------
<pre>-</prev> Step 1: Install module 'react-native-video'
npm install --save react-native-video
<pre>-</prev> Step 2: Link module 'react-native-videos' to project
react-native link react-native-video
=>>> Note: if we run project right now, we will have an error. So, we need edit file 
'./android/settings.graddle':
<pre>+</prev> Change path '../node_modules/react-native-video/android-exoplayer' to '../node_modules/react-native-video/android'
<pre>-</prev> Step 3: Init video's attributes
<pre>-</prev> Step 4: Add functions: play, pause, mute, repeat, speed


----------------PHIÊN BẢN TIẾNG VIỆT----------------
<pre>-</prev> Bước 1: Cài module 'react-native-video'
npm install --save react-native-video
<pre>-</prev> Bước 2: Liên kết module 'react-native-video' tới project
react-native link react-native-video
=>>> Lưu ý: lúc này nếu chạy project thì sẽ bị lỗi, do vậy cần vào file './android/settings.graddle'
chỉnh sửa 1 chút:
<pre>+</prev> Chỉnh đường dẫn '../node_modules/react-native-video/android-exoplayer' thành '../node_modules/react-native-video/android'
<pre>-</prev> Bước 3: Khởi tạo các thuộc tính cần thiết cho video
<pre>-</prev> Bước 4: Thêm các chức năng chơi, dừng, tắt tiếng, lặp lại, chỉnh tốc độ
