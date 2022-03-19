# ByteTrack-MOT-with-UI-YOLOX-
This repository is intended to focus on analyzing the instances movements in a scenario using multiple object tracking with ByteTrack and YOLOX approach.

Below you can see the ByteTrack algorithm in action with YOLOX as the detection backbone. 

You can see how it performs well in tracking instances with uniqe IDs even when occulsion is happening. 
![ezgif com-gif-maker](https://user-images.githubusercontent.com/70451970/159140169-5d301789-56f4-4616-8d1b-d7b8bd41bb0d.gif)

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/70451970/159140175-ff72f235-7684-4dc7-a6bf-2803310917f3.gif)

The model scored 80.3 on MOTA , 77.3 on IDF1 at MOTA17 dataset and performs at 30 FPS!

I am adding some analytical features with UI using streamlit.

The original repo is found [here](https://github.com/ifzhang/ByteTrack)

