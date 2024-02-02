## 🔒 42screensaver
 A simple aesthetic modification of Xscreensaver.

### Modifications
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="">

  Very few things were changed. If you want to make your own modifications to the files, know that you have to modify in ```/utils/images``` to access the logos (the logos I modified are the screen lock display logos) and also in ```/drive/XScreenSaver.ad``` to modify the texts. Apart from that, I believe it's much less aesthetic and more functional.

### About the Artwork
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="">

  One detail that was not specified, but to modify the ```.xpm``` image of the xcreensaver, with your modifications, you cannot let the im
age be too large; it should weigh around ```30kb``` It is also strongly recommended that you change the color scheme to indexed and reduce the number of colors; it will help in image compression. I used GIMP to make the modifications.

### Compilation
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="">

  Compilation is a bit tricky. I don't usually deal with compilation software; there are several dependencies I needed to download to compile the file. But for a cleaner compilation, I do not recommend cloning this repository and modifying it; I recommend getting the file from the most up-to-date version of the build and modifying it, as this way you will have fewer dependency problems.

### Easy Mode
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="">

  If you're not in the mood to go through this process, I strongly recommend that you go to the AUR repository and download the build and only modify the images in the file. Then run the famous ```makepkg --skipinteg``` to skip the hash verifications of the image files, and then just enjoy your modified xscreensaver to your liking.

42.
