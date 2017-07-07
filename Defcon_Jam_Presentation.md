%title: STL2600 + DC314 Presents: DEFCON Jam
%author: Bob & Joe
%date: 2017-06-07



-> STL2600 + DC314 Presents: <-

-> # DEFCON JAM <-


-> A preparatory guide to DEFCON <-
-> for the practical paranoid. <-



---


-> ## What are the security risks of DEFCON? <-


---

# Risks
^

* Identity Theft
^
* Real Theft
^
* Fake Cell Towers
^
* Compromised ATMs
^
* "Wifi, Wifi, everwhere; But not a hotspot to link"
^
* Surrounded by hordes of Chaotic Neutral
^

---

-> # Cell Phone Recommendations <-

---
# Cell Phone Service > Recommended Hardware
^

* [M5 "Card Phone"](https://smile.amazon.com/s/ref=nb_sb_noss_1?url=search-alias%3Daps&field-keywords=m5+phone)
^
* [J8 "Beat the BOSS" Phone](https://smile.amazon.com/LONG-CZ-J8-Bluetooth-earphone-radiation/dp/B01MTVBXQJ/)


---




-> # The "Beat the BOSS" Challenge <-

---

# Cell Phone Service > Getting Service
^

* Personal Preference: Ting.com
^
    - They don't ask a lot of question.
    ^
    - Easy to cancel.
    ^

* Any pre-paid or pay-as-you go will work.


---

# Cell Phone Service > Additional Recommendations
^

* Purchased with pre-paid debit card
^
* Shipped to a UPS Mailbox

---

-> # Laptop Recommendations <-

---

# Laptop > Chromebook
^

* Low-cost, web-based laptops targeted at casual users and education
^

---

# Laptop > Chromebook Setup
^

* Setup a clean Google account, not tied to your primary.
^
* Powerwash the chromebook to remove all traces of your primary identity.
^
* Log in to the burner account on the crombook.
^

---

# Laptop > Chromebook Teardown
^

* Powerwash the chromebook to remove all traces of your burner identity.
^
* Use google data takeout to export all the data from the burner account.
^

---

# Laptop > The Pi-Top
^

* Raspberry Pi based laptop designed for education.
^
* Low cost ($265) makes it semi-disposable.
^
(Sucks less than losing a Macbook)
^
* Lack of BIOS or other firmware makes it ideal.
^

---

# Laptop > Overview of Pi-Top Setup
^

* Arch Linux for minimalism.
^
* Encrypted SD Card (Not trivial on a Pi)
^
* Somewhat limited by the platform ( No hardened kernel/grsecurity )
^
* Heavily referenced [Arch Wiki](https://wiki.archlinux.org/index.php/Security)
^

---

# Laptop > Overview of Pi-Top Setup
^

* Strict password policies in PAM
^
    - prompt 2 times for password in case of an error
    - 10 characters minimum length (minlen option)
    - at least 6 characters should be different from old password when entering a new one.
    - at least 1 digit (dcredit option)
    - at least 1 uppercase (ucredit option)
    - at least 1 other character (ocredit option)
    - at least 1 lowercase (lcredit option)
    ^

---

# Laptop > Overview of Pi-Top Setup

* Use *systemd* to setup ACL's

---

# Laptop > Overview of Pi-Top Setup

* Kernal Parameters:
^
    * Restrict access to kernel logs
    ^
    * Turn on execsheild
    ^
    * IP Spoofing Protection
    ^
    * Log Spoofed Packets
    ^
    * Disable IP Source Routing
    ^
    * Ignore Broadcast Request
    ^
    * Restrict access to proc
    ^
    * Limit Processes per user

 
---

# Laptop > Overview of Pi-Top Setup
^

* *Firejail* for sandboxing apps.
^
* Setup *DNSCrypt*
^
* Used *iptables* managed by Uncomplicated Firewall frontend (*UFW*)
^
* *Disabled root* login from console _and over serial_
^
* *HidePID* to hide processes from other users
^
* Pi-top Specific Apps for Power management, battery, etc.
^

---

# Laptop > Overview of Pi-Top Setup
^

(This is the really clever bit)

* Make a backup image of the final SD card.
^
* Make several copies onto several different cards.
^
* Swap SD Cards out regularly.  At least once a day.
^
* Every day is like having a fresh new system!


---

# Internet Access > Guidelines 
^

* 1st Rule of DEFCON Internet: Never without VPN!
^
* 2nd Rule of DEFCON Internet: Never without VPN!
^
* Stay Off The Open Network!
^
* Secured Wi-Fi requires sideloading a Certificate
^
* Recommend bringing a Mobile Hotspot
^
* Portable Firewall
^

---

# Internet Access > Mobile Hotspot
^

* Again: Ting.com
^
* Same process as the SIM card.
^
* Doesn't mean you can forget your VPN!

---

# Internet Access > Portable Firewall

* Tiny Hardware Firewall
* OpenWRT on TP-Link TL-MR3040

---

# Android devices (Because I don't use an iPhone)
^

* Powered off or Airplane mode when not using
^
* When using, keep Wi-Fi off.
    - Wi-Fi easier to intercept.
    - Though cell service isn't perfect...
^

* If you haven't figured it out yet, USE A VPN!
^
* Turn off all syncing before reaching Vegas
^
* Remove unecessary apps.
^
* Setup a second account on your phone
    - This should sandbox your apps for you.
^

* The Official DEFCON app is safe and useful for scheduling
^
* Should only be using it for reading the schedule checking Signal.
^

---

-> # Navigating DEFCON Itself <-

---

# Navigating DEFCON > Before you get there
^

* Recommend Reading the [Unofficial DEFCON FAQ](http://defcon.stotan.org/faq/)
^

---

# Navigating DEFCON > Before you get there > Moneies

* Bring cash.
    - At least enough for DEFCON Ticket.
    - Withdraw before you board your flight.
    - Don't use ATM's while in Vegas

---

# Navigating DEFCON > Before you get there > Moneies

* If cash makes you nervous, Use pre-paid debit cards.
* If your employer insists on using a card: Most vendors and or restaurants are okay.
* There's always Traveller's Checks.

---

# Navigating DEFCON > Before you get there > Additional Equipment

* Notebook and Pen
^
* Good insoles for your shoes
^
* Talcum Powder (Keep your bits dry)
^
* Bring an Extra Suitcase for swag. 
    (Especially if you are also going to Black Hat.)
^

---

# Navigating DEFCON > Before you get there > Additional Equipment

* Handheld HAM Radio
    - Only if your licensed ;-)
    - Bring an earpiece. It's noisy.
    - 147.495 MHz

---

# Navigating DEFCON > Bonus Crack-pottery

* Door Alarm
^
* Room-Rushing Countermeasures (Door Stop Wedge)
^
* [Bug Sweeper](https://smile.amazon.com/s/ref=nb_sb_noss_1?url=search-alias%3Daps&field-keywords=bug+sweeper)
^

---

# Navigating DEFCON > When you arrive
^

* LineCON - Go 1:30 to 2:00 hours early for your ticket.
^
* Swag on Day One
^
* Don't Pressure Yourself to goto talks
    - No talks. Not even once.
    - Will be on Youtube in 6 months. (Don't tell your boss that.)
^
* Focus on the Villages and Workshops.
^

---

# Navigating Vegas
^

* If you can afford it, Hotel at the Conference
^
    - Shit comfortably.
    ^
    - Crowded talks are broadcast on the hotel's cable.
    ^
    - Drop off your swag.
    ^

---

# Navigating Vegas
^

* Skim through the "Five Hundy by Midnight" Podcast.
^
* "$20 Sandwich" during check-in
^
* Unless you are gambling, Slushes are the cheapest booze for the dollar.
^
* Secret Pizza
^
* Hamburger Bar
^

---



-> *~fin~* <-
