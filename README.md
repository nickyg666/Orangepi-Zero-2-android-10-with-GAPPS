# Orangepi-Zero-2-android-10-with-GAPPS

## Start with credits!

### Big thanks and shoutouts to:

Orangepi-xunlong, for android source and making the board!

huskydg, for magic_flash

Magisk team / wacko1805 for magiskgapps

Nanolx, for nanodroid patcher

thermatk, for fakegapps

termux team for termux 

google, for ADB

the mindTheGapps team, for making an ARM version of GAPPS for android 10, or else this would not be possible

Paul Rubin, David MacKenzie, and Stuart Kemp, for making DD way back when

lsposed team for lsp

I saw a lot of folks begging for the orangepi zero 2 to have gapps in my journey, and thought:
I should share my creation. Although it is a cobbling together of the work of others, I do give credit
where credit is due. 

##This is a ready-to-flash image that PhoenixCard is not needed for.

##A few tips for that software should you
choose to use it:

Always use latest version, only one I can find is russian PhoenixCard 4.2.8

If you are getting errors writing the official image, do try another reader. Mine would not work with internal microsd reader but fine with usb 2.0. If you break your android, you can restore and flash and all your apps still will be there miraculously.


I did install an incompatible version of gapps for regular android 10, and just installed the TV version of play store over it. You can do 

`dd if=opiandroidwGAPPS.img.gz of=dev/mmcblk0 status=progress`

to restore it or probably use Etcher or anything else. You only need PhoenixCard for the initial setup, not for my image.
dd friendly image, etcher should work too
