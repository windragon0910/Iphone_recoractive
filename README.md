### Retroactive is an app that lets you run Aperture, iPhoto, and iTunes on macOS Catalina. It also lets you run Final Cut Pro 7, Logic Pro 9, and fix Keynote ’09 on macOS Mojave and macOS High Sierra.

<p align="center">
  <a href="https://github.com/cormiertyshawn895/Retroactive/releases/download/1.5/Retroactive.1.5.zip" alt="Download Retroactive"><img width="282" height="68" src="screenshots/resources/download-button.png" alt="Download Retroactive"></a>
<p>
<p align="center">
  <a href="https://github.com/cormiertyshawn895/Retroactive/releases" alt="View Release Page"><img width="160" height="18" src="screenshots/resources/release-button.png" alt="View Release Page"></a>
</p>

---

### 💡 iTunes and macOS Catalina 10.15.4

If you have installed iTunes on macOS Catalina with Retroactive 1.4 or earlier, and have updated to macOS Catalina 10.15.4 or later, **you need to re-install iTunes with [the latest version of Retroactive](https://github.com/cormiertyshawn895/Retroactive/releases/download/1.5/Retroactive.1.5.zip).** 

Re-installing iTunes with [the latest version of Retroactive](https://github.com/cormiertyshawn895/Retroactive/releases/download/1.5/Retroactive.1.5.zip) resolves error -42408, -45076, and 11571, so that you can continue to use Apple Music, iTunes Store, and App Store in iTunes. It also resolves an issue where iTunes cannot read the contents of a connected iOS or iPadOS device.

---

### Opening Retroactive

After downloading Retroactive, double click to open it. macOS may prompt you “Retroactive cannot be opened because it is from an unidentified developer.” This is completely normal and expected.

![](screenshots/2.jpg)

To open Retroactive, [right-click](https://support.apple.com/HT207700) on the Retroactive app in Finder, and click “Open” as shown below.

![](screenshots/3.jpg)

If you right-clicked when opening Retroactive for the first time, you need to [right-click](https://support.apple.com/HT207700) for a second time. If Retroactive still can’t be opened, [check your GateKeeper settings](https://support.apple.com/en-us/HT202491) under the General tab in System Preferences > Security & Privacy. Click “Open Anyway” to open Retroactive.

Retroactive will not harm your Mac. This alert only shows up because Retroactive is not notarized. Retroactive is open source, so you can always examine its source code to make sure it’s safe.

---

### Picking an app

Pick the app you want to run. If you want to run multiple apps from here, pick any one of them. You will always be able to get back to this screen later.

![](screenshots/4.jpg)

On macOS Mojave and macOS High Sierra, Retroactive can also unlock Final Cut Pro 7, Logic Pro 9 (experimental), and fix Keynote ’09.

![](screenshots/4b.jpg)

I’ll use Aperture as the example, but the same process also works for iPhoto, iTunes, Final Cut Pro 7, Logic Pro 9, and Keynote ’09.

---

### Locating the app or choosing a version

Retroactive will automatically scan your Mac to locate an existing Aperture, iPhoto, iTunes, Final Cut Pro 7, Logic Pro 9, or Keynote ’09 install. If Retroactive has already located the app you would like to run, skip to the next section.

If Retroactive can’t locate an existing install of Aperture or iPhoto, you’ll either be asked to download it from the Purchased list in App Store, or re-install it from a DVD disc. You can also find the app on another Mac you own, then AirDrop it to this Mac, or restore the app from a Time Machine backup.

![](screenshots/5.jpg)

If you chose iTunes, Retroactive will ask you which version to install, then automatically download and install it for you.

- iTunes 12.9.5 supports Dark Mode and most DJ apps.
- iTunes 12.6.5 supports downloading and archiving iOS apps.
- iTunes 11.4 has a classic look.
- iTunes 10.7 supports CoverFlow.

If you don’t know which version to install, keep the default setting and click “Continue”.

---

### Authenticating Retroactive

To install or modify the app you chose, you need to authenticate with your login password first. Click “Authenticate”, and enter your login password.

![](screenshots/6.jpg)

Your password is never stored or sent anywhere. To verify this, you can view Retroactive’s source code.

---

### Modifying the app

Retroactive will install or modify the app you chose. Modifying the app should only take about 2 minutes.

![](screenshots/7.jpg)

If you chose to install iTunes, this process takes longer. Depending on the version you chose, it can take between 10 minutes to an hour. It is completely normal for the fans to spin up during the process.

If Retroactive asks for your login password again, enter it again. Otherwise, the iTunes installation may be damaged or incomplete. If iTunes 12.9.5 can’t be installed, try to install iTunes 12.6.5.

![](screenshots/8.jpg)

---

### Using the app

After successfully modifying or installing the app, you can play with it to your heart's content.

![](screenshots/9.jpg)

- All Aperture features should be available except for playing videos, exporting slideshows, Photo Stream, and iCloud Photo Sharing. If RAW photos can't be opened, [you need to reprocess them](https://github.com/cormiertyshawn895/Retroactive#reprocessing-raw-photos-in-aperture).

- All iPhoto features should be available except for playing videos, exporting slideshows, Photo Stream, and iCloud Photo Sharing.

- All features should work for iTunes 12.9.5.

- All features should work for iTunes 12.6.5 except for backing up an iOS device. Use iTunes 12.9.5 or Finder to back up your device instead. Thumbnails of download apps may appear distorted.

- Movies and TV Shows downloaded from the iTunes Store may be unable to play in iTunes. Download or play them in the TV app instead. 

- Some dialogs in iTunes may display a crossed-out iTunes icon. This is purely cosmetic and has no functional impact.

- All Final Cut Pro 7 features should work.

- Support for Logic Pro 9 is experimental. You may see frequent freezes and hangs.

- After fixing Keynote ’09 with Retroactive, you can normally play slideshows.

---

### Reprocessing RAW photos in Aperture

- In Aperture, if your RAW photos show up as “*Unsupported Image Format*”, open the “*Photos*” menu, click on “*Reprocess original…*”, and reprocess all photos. After reprocessing your RAW photos, you will be able to preview and adjust them as before.

![](screenshots/reprocess.jpg)

💡 Tip:

- If some RAW photos still show up as "*Unsupported Image Format*" after reprocessing, repeat the process above to reprocess all photos again. In other words, you may need to reprocess all photos twice. 

---

### Workaround to install Final Cut Pro 7 in VMware Fusion

If you don't have a Mac released before Late 2019, you can still install Final Cut Pro 7 in VMware Fusion to export existing Final Cut Pro 7 projects into XML files. This lets SendToX, DaVinci Resolve, Media Composer, and Premiere Pro open them. 

- [Install macOS Mojave virtual machine with VMware Fusion](https://www.huibdijkstra.nl/how-to-set-up-a-osx-mojave-vm-in-vmware-fusion/). Other virtual machine software, such as Parallels Desktop, is not supported and will not work.
- After mounting the Final Cut Studio installer in VMware Fusion, right click on Install Final Cut Studio.pkg > Show Original, then copy FinalCutStudio.mpkg and Packages to VMware Fusion's Desktop
- Right click on the copied FinalCutStudio.mpkg > Show Package Contents > Resources
- Right click on Requirements Checker.app > Show Package Contents > Contents > Resources
- Delete minsys.plist
- Double click on the modified FinalCutStudio.mpkg to start the install
- Use Retroactive as usual

To use editing features such as timeline and preview, install macOS Mojave on a real, older Mac released before Late 2019, then run Retroactive as usual.

---

### Last words
- If GateKeeper prevents you from running modified versions of your chosen app, [temporarily disable GateKeeper in Terminal](http://osxdaily.com/2015/05/04/disable-gatekeeper-command-line-mac-osx/) with `sudo spctl --master-disable`.

- To learn more about how Retroactive works, [take a technical deep dive](https://medium.com/@cormiertyshawn895/deep-dive-how-does-retroactive-work-95fe0e5ea49e).
