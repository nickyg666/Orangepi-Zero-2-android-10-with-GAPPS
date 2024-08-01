# Orangepi-Zero-2-android-10-with-GAPPS
# You will need a 128GB card to restore to! Github does not like files over 2gb, so it is splitted. comes out to 9.4gb extracted. should be able write with etcher. I prefer DD, but it is up to personal taste. If your choice does not support img.gz you can gunzip the img.gz but be warned, it is SD sized (128GB)
## Start with credits!

### Big thanks and shoutouts to:

Orangepi-xunlong, for android source and making the board!

huskydg, for magic_flash

Magisk team

Nanolx, for nanodroid patcher

termux team for termux 

google, for ADB

the mindTheGapps team, for making an ARM version of GAPPS for android 10, or else this would not be possible

LiteGapps Team

Paul Rubin, David MacKenzie, and Stuart Kemp, for making DD way back when

lsposed team for lsp

I saw a lot of folks begging for the orangepi zero 2 to have gapps in my journey, and thought:
I should share my creation. Although it is a cobbling together of the work of others, I do give credit
where credit is due. 

## This is a ready-to-flash image that PhoenixCard is not needed for.
# You will need a 128GB card to restore to!
## A few tips for that software should you choose to use it:

Always use latest version, only one I can find is russian PhoenixCard 4.2.8

If you are getting errors writing the official image, do try another reader. Mine would not work with internal microsd reader but fine with usb 2.0. If you break your android, you can restore and flash and all your apps still will be there miraculously. for some very strange reason you can wipe and rewipe the drive, put other data on it, and when you use phoenixcard again it will bring all your apps, settings, etc back. you have to reset in android or recovery to do a wipe.


You can do 

`dd if=opiandroidwGAPPS.img.gz of=dev/mmcblk0 status=progress`

to restore it or probably use Etcher or anything else. You only need PhoenixCard for the initial setup, not for my image.
this is a dd friendly image, etcher or any other solution should work.
I used 7z on the gzipped img to be more bandwidth friendly.
# You will need a 128GB card to restore to (They are pretty cheap on amazon, I got a SiliconPower 2-pack for like 25$)
