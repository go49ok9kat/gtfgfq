---
title: "3 Easy Ways to Disable Autorun in Windows - wikiHow"
date: 2030-10-09 10:17
author: Hannah Kim
---

# 3 Easy Ways to Disable Autorun in Windows - wikiHow

Skip to Content Quizzes PRO Courses Hot Guides  Tech Help Pro  Expert Videos  About wikiHow Pro  Upgrade  QUIZZES All Quizzes Hot Love Quizzes  Personality Quizzes  Trivia Quizzes  Taylor Swift Quizzes  EXPLORE

Tech Help ProAbout UsRandom ArticleQuizzes

Request a New ArticleCommunity DashboardTrendingForums

Arts and EntertainmentArtworkBooksMovies

Computers and ElectronicsComputersPhone SkillsTechnology Hacks

HealthMen's HealthMental HealthWomen's Health

[Colors that Go with Yellow: Combos for Home and Style](https://github.com/ispnvnhils/ipsplmw/blob/main/ev-charger-installation/2031-07-10-colors-that-go-with-yellow-combos-for-home-and-style.md)

RelationshipsDatingLoveRelationship Issues Hobbies and CraftsCraftsDrawingGames

Education & CommunicationCommunication SkillsPersonal DevelopmentStudying

Personal Care and StyleFashionHair CarePersonal Hygiene

QuizzesLove QuizzesPersonality QuizzesFun Games

Arts and EntertainmentFinance and BusinessHome and GardenRelationship Quizzes

Cars & Other VehiclesFood and EntertainingPersonal Care and StyleSports and Fitness

Computers and ElectronicsHealthPets and AnimalsTravel

Education & CommunicationHobbies and CraftsPhilosophy and ReligionWork World

Family LifeHolidays and TraditionsRelationshipsYouth LOG IN Log in

Social login does not work in incognito and private browsers. Please log in with your username or email to continue. Facebook Google wikiHow Account No account yet? Create an account RANDOM Home Random Browse Articles TrendingNew Quizzes & Games All QuizzesHot Love Quizzes Personality Quizzes Fun Games Dating Simulator Learn Something New Forums Courses Happiness Hub Explore More Support wikiHow About wikiHow Log in / Sign up Terms of Use

wikiHow is where trusted research and expert knowledge come together. Learn why people trust wikiHow Categories Computers and Electronics Operating Systems Windows How to Disable Autorun in Windows Written byTravis Boylls Last Updated: December 11, 2025 Using Windows Settings | Using Group Policy Editor | Using Registry Editor |Show more|Show less X

This article was co-authored by wikiHow staff writer, Travis Boylls. Travis has been a tech writer at wikiHow for more than 10 years. He has also worked in technical support for Dish Network and AT&T Wireless. He studied graphic design and web design at Pikes Peak Community College. He specializes in Windows, macOS, Linux, Android, iOS, and video game consoles. Travis has had a fascination with computers and technology that goes all the way back to childhood. He is proficient in all manner of software and computer operating systems. 

This article has been viewed 26,732 times.  Learn more...

Autorun is a feature of Windows in which a predetermined action is taken when certain types of media such as a CD, DVD, or USB flash drive is inserted in a computer. Most commonly, autorun will launch or install a new program on the media.[1]XResearch source Disabling Autorun in Windows will help prevent accidental installation of viruses and other malware. You can disable AutoPlay on Windows 10 Settings menu, the Group Policy editor, or using the Registry editor. This wikiHow teaches you how to disable autorun. Steps Method 1 Method 1 of 3: Using Windows Settings 1 Click the Windows Start menu

. It's the button with the Windows logo in the taskbar. By default, it's in the lower-left corner. 2

[in Windows wikiHow](https://in-windows-wikihow.themaplelane.com/in-windows-wikihow/202608260129.html)

Type AutoPlay Settings and press ↵ Enter. This opens the AutoPlay Settings menu for Windows. Advertisement 3 Click the toggle switch

below Autoplay. It's at the top of the menu. This disables Autoplay and Autorun for your Windows computer. When you insert a drive, you will need to open it manually in File Explorer and run any programs automatically. 4

[Easy Ways](https://easy-ways.northlist.xyz/easy-ways/20260826.html)

Select "Take No Action" in the menu below "Removable Drive." This ensures that Windows does not open a folder or automatically run any files when a removable drive, such as a CD-ROM or USB flash drive is inserted. 5

Select "Take No Action" in the menu below "Memory Card." This ensures that Windows will not automatically open a memory card or automatically run any files when a memory card is inserted. Advertisement Method 2 Method 2 of 3: Using Group Policy Editor 1 Click the Windows Start menu

. It's the button with the Windows logo in the taskbar. By default, it's in the lower-left corner.

Group Policy Editor is not available for Windows 10: Home Edition. 2

Type Run and press ↵ Enter. This launches a program called "Run." You can also click the Run icon in the Windows Start menu. 3

Type Gpedit.msc into Run and click Ok. Use the field in the center of Run to enter "Gpedit.msc." Then click Ok or press Enter. This launches the Group Policy Editor.

If asked to enter an administrative password, enter the admin password and click Allow. 4

[Windows wikiHow](https://windows-wikihow.northlist.shop/windows-wikihow/2026082670.html)

Double-click Administrative Templates under "User Configuration." "Administrative Templates" can be found under both "User Configuration" and "Computer Configuration" Click the one under "User Configuration" to expand the Administrative Templates menu. 5

Double-click Windows Components. This displays the administrative template folders listed under "Windows Components." 6

Double-click AutoPlay Policies. This opens the folder containing AutoPlay administrative templates. 7

Double-click Turn off AutoPlay. This opens the administrative template that allows you to disable AutoPlay and Autorun. 8

Click the radio option next to "Enabled." It's at the top of the template on the left-hand side of the Window. When this template is enabled, AutoPlay and Autorun will be disabled on all drives, including removable USB drives, disk drives. 9

Click Apply. It's in the lower-right corner of the window. This applies to the new settings. 10

Click Ok. This closes the Group Policy Editor. [2]XResearch source 11

Restart your computer. Once you apply the new setting, restart your computer to ensure the new settings take effect. Advertisement Method 3 Method 3 of 3: Using Registry Editor 1 Click the Windows Start menu

. It's the button with the Windows logo in the taskbar. By default, it's in the lower-left corner.

Warning: Making changes to the Windows registry can cause permanent damage to your computer. Continue at your own risk to do not alter anything if you don't know what it does. 2

Type Run and press ↵ Enter. This launches a program called "Run." You can also click the Run icon in the Windows Start menu. 3

Type Regedit.exe into Run and click Ok. Use the field in the center of Run to enter "Regedit.exe." Then click Ok or press Enter. This launches the Registry Editor.

If asked if you want to allow the Registry Editor to make changes to your system, click Yes. 4

Double-click HKEY_CURRENT_USER. It's in the menu to the left of Registry Editor. Double-click this option to expand it. 5

Double-click Software. It's below "HKEY_CURRENT_USER." This expands the Software folder. 6

Double-click Microsoft. It's in the Software folder. This expands the Microsoft folder. 7

Double-click Windows. It's in the Microsoft folder. This expands the Windows folder. 8

[to Disable Autorun](https://to-disable-autorun.northlist.shop/to-disable-autorun/2026082654.html)

Double-click CurrentVersion. It's in the Microsoft folder. This expands the CurrentVersion folder. 9

Double-click Poicies. It's in the CurrentVersion folder. This expands the Policies folder. 10

Double-click Explorer. It's in the Policies folder. This expands the Explorer folder.

The full path in the Registry Editor is "Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer" 11

Double-click NoDriveTypeAutoRun. It's the only option under "Explorer." This allows you to change the policy with regards to Autorun in Registry Editor. 12

[Ways to Disable](https://ways-to-disable.curblist.xyz/ways-to-disable/20260826.html)

Enter one of the follow values. Each of the following values affects Autorun in a different way. Enter one of the following values of your choice in the "Value data" field. The values are as follows:

"FF:" This disables Autorun on all drives.

"20:" This disables Autorun on the CD-ROM only.

"4:" This disables Autorun on all removable drives.

"8:" This disables Autorun on all fixed drives.

"10:" This disables Autorun on all network drives.

"40:" This disables Autorun on the RAM disk only.

"1:" This disables Autorun on all unknown drives.

"91:" This sets Autorun to function as normal. 13

Click Ok. This saves the new value and setting for Autorun.[3]XResearch source[4]XResearch source Advertisement Expert Q&A  Search Add New Question Ask a Question 200 characters left

Include your email address to get a message when this question is answered. Submit Advertisement Tips Submit a Tip 

All tip submissions are carefully reviewed before being published Name 

Please provide your name and last initial Submit Thanks for submitting a tip for review!  You Might Also Like How to

Enable AutoRun & AutoPlay in Windows 10/11 Block an .exe Running in Windows A Guide to Disabling Write Protection How to

Disable Automatic Updates in Windows 10: 5 Easy Ways How to

Remove Shortcut Virus from a Windows PC or Laptop

6 Easy Ways to Fix a USB Drive That is Stuck in Read-Only Mode

Simple Ways to Remove a Flash Drive from a Windows 10 Computer How to Change the Icon of Removable Drives How to

Eject the CD/DVD Tray on a Windows 10 PC How to Block Apps on PC or Mac How to

Play a CD on a Desktop Computer: Easy Steps How to

Remove Write Protection from a USB Pen Drive

Turn Off Microsoft Defender in Windows 10 & 11: Temporarily or Permanently How to Remove a Virus From a Flash Drive Advertisement References

↑https://searchwindowsserver.techtarget.com/definition/AutoRun

↑https://www.youtube.com/watch?v=hCzgImpmXvs

↑https://www.youtube.com/watch?v=BwMJ9j0j5yY

↑https://www.nucleustechnologies.com/blog/three-methods-to-disable-autorun-in-windows-10/ About This Article Written by:  Travis Boylls wikiHow Technology Writer

This article was co-authored by wikiHow staff writer, Travis Boylls. Travis has been a tech writer at wikiHow for more than 10 years. He has also worked in technical support for Dish Network and AT&T Wireless. He studied graphic design and web design at Pikes Peak Community College. He specializes in Windows, macOS, Linux, Android, iOS, and video game consoles. Travis has had a fascination with computers and technology that goes all the way back to childhood. He is proficient in all manner of software and computer operating systems. This article has been viewed 26,732 times.  How helpful is this? Co-authors: 3 Updated: December 11, 2025 Views: 26,732 Categories: Windows Article SummaryX 1. Click the Windows Start menu.

2. Type "AutoPlay Settings" and press Enter.

3. Click the toggle switch to turn AutoPlay off.

5. Select "Take No Action" in the menu below "Removable Drive."

6. Select "Take No Action" in the menu below "Memory Card." Did this summary help you?YesNo In other languages Japanese Spanish Dutch Print Send fan mail to authors

[Easy Ways](https://easy-ways.swapstreet.shop/easy-ways/2026082691.html)

[Autorun in](https://autorun-in.northlist.xyz/autorun-in/202608261317.html)

Thanks to all authors for creating a page that has been read 26,732 times. Is this article up to date? YesNo Advertisement

[Ways to](https://ways-to.themaplelane.com/ways-to/2026082653.html)

Cookies make wikiHow better. By continuing to use our site, you agree to our cookie policy. Written by:  Travis Boylls wikiHow Technology Writer Click a star to vote Co-authors: 3 Updated: December 11, 2025 Views: 26,732 Quizzes & Games Am I Chronically Online Quiz Take Quiz What Tarot Card Am I Quiz Take Quiz Am I Misogynistic? Get Answers Here Take Quiz

Do You Agree with These Music Hot Takes? Take Quiz You Might Also Like How to

Enable AutoRun & AutoPlay in Windows 10/11 Block an .exe Running in Windows A Guide to Disabling Write Protection How to

Disable Automatic Updates in Windows 10: 5 Easy Ways Trending Articles Am I Chopped Quiz Can We Guess How Tall You Are Quiz Kiss, Marry, Kill Quiz What’s the Name of My Crush? Trending Articles Finish the Lyrics TikTok Edition

[Ways to](https://ways-to.swapstreet.shop/ways-to/20260826367.html)

Design a Morning Routine and Learn Your Superpower

Pick a Door and We'll Reveal What You're Missing What Kind of Doomed Am I? Take the Quiz. Face the Truth. 🔥 Am I Gay Quiz Do I Have a Type? Am I Hard to Love? Am I a Spoiled Brat? 🤔 Are You More... 🤔 How Tuff Am I? What Kind of Wolf Is My Personality?

Am I More Golden Retriever or Black Cat? Villain or Hero Quiz Featured Videos

The Right Way to Refrigerate and Freeze Fresh Green Beans

A Complete Guide to Shaving Your Body (and Preventing Razor Burn) How to

Play "What Are the Odds?" (Also Known As "Odds Are")

4 Easy Ways to Draw Cute and Realistic Cats Hot Takes Only 🔥 Overrated or Underrated Game

Do You Agree With These Spicy Hot Takes?

Do You Agree with These Hygiene Hot Takes?

Weird Would You Rather: What Do You Choose? Your Daily Dose of Fun 🎉

Do You Agree with These Popular Hot Takes?

Let Us Guess Your Age Based On Video Game Nostalgia Rizz Game: Test Your Rizz

Can You Pull Off The Perfect Heist? Prove Yourself Categories Computers and Electronics Operating Systems Windows

© 2026 wikiHow, Inc. All rights reserved. Use of site content is subject to our Terms of Use. wikiHow Newsletter You're all set! Helpful how-tos delivered to your inbox every week! Sign me up!

By signing up you are agreeing to receive emails according to our privacy policy. Home About wikiHow Experts Jobs Contact Us Site Map Terms of Use Privacy Policy Do Not Sell or Share My Info Not Selling Info Contribute Follow Us × wikiHow Tech Help:

Tech troubles got you down? We've got the tips you need Subscribe You're all set! X - - 682
