iOS/macOS penetration testing cheatsheet

| Action | macOS | Linux | Win | iOS w/JB |
| --- | --- | --- | --- | --- |
| `MobSF` | [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | --- |
| `Plist view` | **plutil** or **Xcode** | `apt-get install libplist-utils` | [Plist Viewer](https://github.com/TingPing/plist-viewer) | **plutil** |
| `Frida` | [Frida](https://www.frida.re/docs/installation/) | [Frida](https://www.frida.re/docs/installation/) | [Frida](https://www.frida.re/docs/installation/) | --- |
| `Awesome Frida` | [Awesome Frida](https://github.com/dweinstein/awesome-frida) | --- | --- | [Awesome Frida](https://github.com/dweinstein/awesome-frida) |
| `Objection` | [Objection](https://github.com/sensepost/objection) | [Objection](https://github.com/sensepost/objection) | [Objection](https://github.com/sensepost/objection) | [Objection](https://github.com/sensepost/objection) |
| `Needle` | [Needle](https://github.com/mwrlabs/needle) | [Needle](https://github.com/mwrlabs/needle) | --- | --- |
| `Keychain dumper` | [Keychain dumper](https://github.com/ptoomey3/Keychain-Dumper) | --- | --- | [Keychain dumper](https://github.com/ptoomey3/Keychain-Dumper) |
| `iOS URL Schemes` | [iOS URL Schemes](https://github.com/phynet/iOS-URL-Schemes) | --- | --- | [iOS URL Schemes](https://github.com/phynet/iOS-URL-Schemes) |
| `Debug Hacks` | [Debug Hacks](https://github.com/aozhimin/iOS-Debug-Hacks) | --- | --- | --- |
| `SandBox Dumper` | [SandBox Dumper](https://github.com/dineshshetty/iOS-SandBox-Dumper) | --- | --- | --- |
| `PassionFruit` | [PassionFruit](https://github.com/chaitin/passionfruit) | [PassionFruit](https://github.com/chaitin/passionfruit) | --- | --- |
| `iPhoneTunnel` | [iPhoneTunnel](https://code.google.com/archive/p/iphonetunnel-mac/downloads) | --- | [iPhoneTunnel](https://code.google.com/archive/p/iphonetunnel-usbmuxconnectbyport/downloads) | --- |
| `iRET` | [iRET](https://github.com/S3Jensen/iRET) | --- | --- | --- |
| `idb` | [idb](https://github.com/dmayer/idb) | [idb](https://github.com/dmayer/idb) | --- | --- |


AppSign / Rebuild / Resign / Inject / Useful tools

| Tool | Description | Link |
| --- | --- | --- |
| `Node Resign` | Xcode Project | [Node Resign](https://github.com/nowsecure/node-applesign) |
| `Frida Gadget` | Framework | [Frida Gadget](https://www.frida.re/docs/ios/) |
| `Runtime Headers` | Xcode Project | [Runtime Headers](https://github.com/nst/iOS-Runtime-Headers) |
| `SSL Killswitch 2` | Jailbreak(+) | [SSL Killswitch 2](https://github.com/nabla-c0d3/ssl-kill-switch2) |
| `IPA Patch` | Xcode Project | [IPA Patch](https://github.com/Naituw/IPAPatch) |
| `Clutch` | Jailbreak(+) | [Clutch](https://github.com/KJCracks/Clutch) |
| `Theos` | Project | [Theos](https://github.com/theos/theos) |
| `iOS App Signer` | Xcode Project | [iOS App Signer](https://github.com/DanTheMan827/ios-app-signer) |
| `AppAddict` | App | [AppAddict](https://www.appaddict.org/tools.php) |
| `Dumpdecrypted` | Project | [Dumpdecrypted](https://github.com/stefanesser/dumpdecrypted) |
| `Rasticrac` | Jailbreak(+) | [Rasticrac](https://github.com/easonoutlook/Rasticrac) |
| `Resign` | Xcode Project | [Regisn](https://github.com/vtky/resign) |
| `Cycript` | Framework | [Frida+Cycript](https://github.com/nowsecure/frida-cycript) & [Site](http://www.cycript.org/) |
| `CydiaSubstrate` | Framework | [Site](http://www.cydiasubstrate.com/) & [.deb file](http://apt.saurik.com/debs/mobilesubstrate_0.9.6301_iphoneos-arm.deb) |
| `Reveal app` | Project | [Reveal app](http://revealapp.com/) |
| `Impactor` | App | [Cydia Impactor](http://www.cydiaimpactor.com/) |
| `iFunBox` | App | [iFunBox](http://www.i-funbox.com/) |
| `IPA installer` | Xcode Project | [IPA installer](http://github.com/autopear/ipainstaller) |
| `Download old version .ipa` | Manual how-to | [Lifehacker](https://lifehacker.com/download-old-versions-of-ios-apps-with-a-clever-workaro-1749950092) |
| `iTunes w/app tab` | iTunes 12.6.3.6 | [Apple Support](https://support.apple.com/en-us/HT208079) |
| `JSPatch` | Framework | [JSPatch](https://github.com/bang590/JSPatch) |
| `Appdb` | Download&resign .ipa | [Appdb](appdb.store) |
| `iphonecake` | Download&resign .ipa | [iphonecake](https://www.iphonecake.com/) |
| `4pda` | Download&resign .ipa | [4pda](https://4pda.ru/) |
| `BundleID` | Jailbreak(+) | [BundleID](https://www.reddit.com/r/iOSthemes/comments/34v57e/how_to_find_an_apps_bundle_id/) |
| `FRAPL` | Framework | [FRAPL](https://github.com/FriedAppleTeam/FRAPL) |
| `IPSW` | Download Firmware | [IPSW](https://ipsw.me/) |



Jailbreak
[Jailbreak Chart](https://www.reddit.com/r/jailbreak/wiki/escapeplan/guides/jailbreakcharts)
[Can I Jailbreak?](https://canijailbreak.com/)


Slides and articles and links

| Name | Link |
| --- | --- |
| `Malware wellbeing on iOS devices` | [Slides](https://dsec.ru/upload/medialibrary/29f/29f57cef406125e9169da733e1aaf83f.pdf) |
| `DVIA` | [Homepage](http://damnvulnerableiosapp.com/) |
| `Dynamic analysis of iOS apps w/o Jailbreak` | [Article](https://habrahabr.ru/company/dsec/blog/339952/) & [Slides](https://dsec.ru/upload/volgactf_dyn_ios_analysis_wo_jb.pdf) |
| `Ro(o)tten Apples Vulnerability Heaven in the iOS Sandbox` | [Slides](http://gsec.hitb.org/materials/sg2017/D2%20-%20Adam%20Donenfeld%20-%20Ro(o)tten%20Apples%20-%20Vulnerability%20Heaven%20in%20the%20iOS%20Sandbox.pdf) |
| `Light and Dark side of Code Instrumentation` | [Slides](http://www.data.proidea.org.pl/confidence/10edycja/materialy/prezentacje/DmitriyEvdokimov.pdf) |
| `Комбайны безопасности для iOS и Android` | [Slides](https://dsec.ru/upload/medialibrary/e76/e76656cd8b92aa5021cb1a0662d9859f.pdf) |



Author: [@ansjdnakjdnajkd](https://twitter.com/ansjdnakjdnajkd)

Do you want to add or fix? - Write to me or pull request!
