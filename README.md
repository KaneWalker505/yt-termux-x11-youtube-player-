# yt-termux-x11-youtube-player-
Android termux (terminal) YouTube Video Player for armv8 / aarch64


yt (termux x11 youtube player)

#Requirments:
(X11 Android App)

termux-x11  - Allows sending to x11 server

openbox  - GUI programs to open in x11

python3  - Core code framework 

yt-dlp  - System/Library for YouTube

vlc-qt  -  GUI QT VLC player for playing

__________

These will auto install/upgrade when installing yt (termux x11 youtube player)


#install 

pkg install wget

wget https://github.com/KaneWalker505/yt-termux-x11-youtube-player-/releases/download/Release/yt_1.0_aarch64.deb

pkg install ./yt_1.0_aarch64.deb



#Usage

yt  - watch a youtube video

video  - watch last watched video


Program will ask or request a youtube URL, Upon entering URL to youtube video the program will download the video to a temporary file. The program then works its magic with x11 to cast and play the downloaded youtube video instantly to x11 app. This way we can play and watch any youtube video we want without any annoying ads. No Ads when watching youtube this way also the video app itself for playing the youtube videos are way less demanding both for networking data and memory. So watching youtube this way will also save on mobile data / wifi bandwidth and overall system memory space. As there is no video cache or ads.


"Does support pause/stop/skip and more ** must double finger screen hold and release ***


After installing the yt_1.0_aarch64.deb

Just type

 yt 


You can also type 

 video

At anytime in termux after watching a video via yt to rewatch it again. ONLY valid for last video watched.


