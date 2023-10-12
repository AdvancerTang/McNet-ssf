# Spatially selective filter
&nbsp; The program is used to select the speaker in the target direction based on neural network,which can also be used for noise reduction and speech enhancement.The results of the algorithm in this program is shown in the folders, which contain the original audio and the processed audio, as well as their spectrogram,the original audio is collected through a 10cm circular microphone array.

&nbsp; The purposes of this project are as follows.<br>


* Speech separation


 &nbsp;When many people are talking at the same time, the program can be used to extract a single target speaker based on his or her direction. The folder named **Speaker setect** include the raw audio captured by microphone array
and the single channel audio processed by neural network, which is presented by this program.


* Noise suppression

  
&nbsp; When people are talking in a noisy environment, it can be used to suppress noise while obtain clean speech signal of the speaker. The folder named **ns** include the raw audio captured by microphone array and the single channel clean audio processed by this program.



* Speech enhancement

  
&nbsp; When people are talking, there may be multi kinds of interference such as video and music, which may lead to the decrease of ASR, the algorithm in this program can be used to enhance the voice of the target speaker. The folder named **SE** include the raw audio captured by microphone array and the single channel clean audio processed by the algorithm in this program.
