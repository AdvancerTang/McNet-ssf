
 &nbsp; When people are talking, there may be some interfer such as video and music around them, which may lead to the decrease of ASR, the algorithm in this program can be used to enhance the voice of speaker based on their direction.
 &nbsp;The audio in this folder named with **before** is the original audio, which was collected using a 6-channel circular microphone array in office, while the audio named with **after** is the  enhanced audio by the neural network.<br>
 &nbsp;There is a man who is talking with video interfer and music interfer, the audio named with **video** stand for TV interfer, with **music** stand for music interfer, **50** means the speaker is 50° relative to the reference microphone.

  &nbsp; The spectrum of the collected audio with video interfer is shown in Fig.1, (a) is the raw wave spectrum, (b) is the spectrum of the speech processed by the neural network.
  
| ![Image A](before_video.png) | ![Image B](after_video.png) |
|:---:|:---:|
| (a) | (b) |

<p align="center">
Fig.1 video interfer
</p>

  &nbsp; The wave spectrum of  the collected audio with music interfer is shown in Fig.2, (a) is the raw wave spectrum, (b) is the spectrum of the clean speech processed by the neural network.
  
| ![Image A](before_music.png) | ![Image B](after_music.png) |
|:---:|:---:|
| (a) | (b) |


<p align="center">
Fig.2 music interfer
</p>
