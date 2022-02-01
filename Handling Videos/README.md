
## 1. compress Video:

* Clone This repo/ use compress.py file
* Through terminal:

      python compress.py video_path num
      
  Where num is an int between 0 and 100, The lower, the lower the outpt size and resolution.  50 is a good default
  
---

## 2. trim vodeo:

      from moviepy.video.io.ffmpeg_tools import ffmpeg_extract_subclip
      ffmpeg_extract_subclip(video_path, 800, 950, targetname="test1.mp4")



**Another Method:**

      # Import everything needed to edit video clips 
      from moviepy.editor import *

      # loading video dsa gfg intro video 
      clip = VideoFileClip("/content/drive/MyDrive/UPwork/andrew/Hogs/GH044882.MP4") 

      # getting only first 5 seconds 
      clip = clip.subclip(100, 250) 

      # # cutting out some part from the clip
      # clip = clip.cutout(3, 10)

      # showing  clip 
      clip.ipython_display(width = 360)

---

