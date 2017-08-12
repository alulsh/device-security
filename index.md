# Laptop & Phone Security

## Digital Security Training

August 12th, 2017

Georgetown Law School

---

# Alexandra Ulsh

Information Security Engineer

Mapbox

@AlexUlsh

---

# Threat model

* Who's trying to hack you?
* Who and what are you worried about?
* You may need additional security measures than what this presentation covers.

---

# Laptops - Passwords

* Use a password
* Use a strong, complex password **that you can easily remember**
* Sleep after 5 minutes of inactivity and require a password on wake

---

# Phones - Passcodes

* A passcode is a type of password - use one!
* Use a long one - 12+ characters
* Alphanumeric > numbers only
* Strike a balance between usability and security
* Require a passcode immediately after sleep
* Android - don't use common lock patterns (e.g. letter M or S)
* iPhone - Enable erase data after 10 bad passcode attempts (take good backups!)

---

# Biometrics

* Touch ID? Depends on your threat model
* Probably safe for the "average" person
* If Touch ID allows you to use a stricter passcode, then may be worth it
* Similar logic for iris scanner unlock on Android devices

---

# Physical security

* Privacy screens for laptops when traveling or at coffee shops
* Don't leave your laptop or phone unattended
* Use a webcam cover or cover with tape
* Always lock your computer, even at work

---

# Device tracking

* Enable Find My Mac, Find My iPhone, or Android Device Manager
  * Extra important to have 2FA on iCloud and Google accounts
* These allow for remote device wiping in case lost or stolen
* Peace of mind - locate device if lost
* Enabling carries privacy trade offs though (threat model)

---

# Software updates

* Update your operating system frequently
  * Mac and iOS App Store = red numbers
  * Windows Update = yellow warnings
  * Android updates
* Update your apps frequently
  * Mac and iOS App Store
  * Google Play store
  * Automatically check for application updates

---

# Laptop User Accounts

* Disable Guest account (if enabled)
* Don't use Apple ID or Microsoft account to login, use a local user account
* Windows - depending on your threat model, Microsoft login _may_ be worth it for free device encryption and Find My Device features.
* Windows - Don't disable User Access Control (UAC) (enabled by default).

---

# Firewalls

* Prevent attackers from connecting to your computer or installing malware that exfiltrates data from your computer
* Mac - enable firewall and stealth mode in network settings
* Windows - enable firewall in Windows Defender

---

# Wifi security

* Ask to join wifi networks (both laptop and phone) - don't connect automatically to unknown networks
* Remove old wifi networks after using, e.g. `United_Wifi` and `Starbucks`
* Don't connect to open (password-less) wifi networks
* These are unencrypted and people can sniff traffic
* If you must, then use a reputable VPN service (including on `United_Wifi`)

---

# Other network security

* If you don't need Bluetooth, disable it
* Disable Airdrop, only enable briefly when you need it

---

# Laptop browser security

* Frequently update all of your browsers
* Browser vulnerabilities are a common way to get hacked
* Chrome and Firefox will automatically update by default
* Make sure to `command` + `Q` (fully quit) on a Mac to make sure they update
* Standard security extensions: HTTPS Everywhere, uBlock Origin, Privacy Badger (note: breaks websites)

---

# Secure mobile browsing

* Some people browse the internet on their phones more than on a traditional computer
* iPhone
  * [Firefox Focus](https://itunes.apple.com/us/app/firefox-focus-the-privacy-browser/id1055677337?mt=8) - best option for privacy
  * Install content blockers like [Ka-Block!](https://itunes.apple.com/us/app/ka-block-block-ads-tracking-scripts/id1037173557?mt=8) for mobile Safari
* Android
  * Installed [uBlock origin](https://addons.mozilla.org/en-US/android/addon/ublock-origin/) Firefox add-on
* Avoid using mobile Chrome on both iPhone and Android :( no content blockers

---

# Encryption

* Prevents reading files (including cookies for login sessions) of a stolen or lost device
* Mac = FileVault
  * Don't store recovery key with Apple or with iCloud account - **remember your computer login password instead**
* Windows = BitLocker
  * Requires paid Windows Pro and Trusted Platform Module (TPM) hardware
* iPhones encrypted by default :)
* You should enable encryption on your Android phone

---

# Backups

* Have multiple forms of backups (depends on threat model) for all of your devices
  * Cloud and local
  * Or multiple local
* Encrypt your backups, e.g. iTunes iPhone backups

---

# File extensions

* Laptops - Enable seeing file extensions on files (`.jpg`,`.docx`, `.html`)
* Disabled by default on both Mac and Windows :(
* Prevents phishing attacks and opening malicious downloads
* `cutepuppy.gif` could really be `cutepuppy.gif.exe`

--- 

# App security

* Only install applications or programs from trusted developers
* View the app developer website - do they seem reputable?
* Evaluate permissions the app requires - does a game really need access to your contacts?
* Mac Gatekeeper - keep default setting of apps from Mac App store and identified developers

---

# Malware protection

* Windows = Free Windows Defender from Microsoft
* Macs? Lower malware risk than Windows, but getting worse every year
* No anti-virus software I can confidentally recommend for Mac
* Check out free Mac anti-malware tools from [Objective-See](https://objective-see.com/products.html)
* Phones - only download reputable apps from App Store and Google Play store

---

# Resources

* This presentation!
  * https://github.com/alulsh/device-security
* Personal security checklist
  * https://github.com/alulsh/personal-security-checklist
* Intro to Security for Developers
  * https://github.com/alulsh/intro-to-security-for-developers

---

# Questions?

* Laptop and phone security workshop today
* @AlexUlsh on Twitter
* alexandra.ulsh@gmail.com