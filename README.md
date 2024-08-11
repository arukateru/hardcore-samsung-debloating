# hardcore-samsung-debloating
Debloat scripts for UAD that I main

Tested on : Galaxy A23 5G. Currently, I main the "very high" in my daily driver phone. So if there is a problem, I may update the debloat lists.

Notable: Samsung clock is removed (it takes up 100MB) and notes as well. I recommend using the [AOSP clock](https://www.apkmirror.com/apk/lineageos/clock-2/clock-2-8-1-0-release/) and [tctnote](https://play.google.com/store/apps/details?id=com.tct.note). Of course you can add packages back in UAD if you choose.
Make sure to use the [updated UAD repository](https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation) since old repository is not maintained anymore.

You will need to put your device ID into the file manually for it to recognize the backup. Make a backup of your current device, then find the directory in C:\Users\yourusername\AppData\Local\uad\backups\yourdeviceid. You can open your backup's json file and replace the first line containing your device ID into the debloat list files, and place them in that directory.

**Medium:** Nothing is broken except "Samsung SmartThings" packages disabled. No problems if you don't use a Samsung SmartThings device.
*Total packages removed: 70*

**High:** Medium + Microsoft Exchange accounts (used as a g-suite alternative in some workplaces/schools) become randomly disappeared from the device. The randomness makes it very difficult to diagnose. If you know the responsible package, please contribute !
*Total packages removed: 161*

**Very high:**  High + Mostly no more problems but may crash webview on very rare occasions, in which case a restart is needed. So far, this has only happened twice.
*Total packages removed: 176*

More options may be coming soon ! Very high is not highest possible. for example, Hotspot 2.0 packages are left .
