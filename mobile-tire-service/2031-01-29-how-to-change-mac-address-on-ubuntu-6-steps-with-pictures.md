---
title: "How to Change MAC Address on Ubuntu: 6 Steps (with Pictures)"
date: 2031-01-29 19:58
author: Noah Fitzgerald
---

# How to Change MAC Address on Ubuntu: 6 Steps (with Pictures)

Skip to Content Quizzes PRO Courses Hot Guides  Tech Help Pro  Expert Videos  About wikiHow Pro  Upgrade  QUIZZES All Quizzes Hot Love Quizzes  Personality Quizzes  Trivia Quizzes  Taylor Swift Quizzes  EXPLORE

Tech Help ProAbout UsRandom ArticleQuizzes

Request a New ArticleCommunity DashboardTrendingForums

Arts and EntertainmentArtworkBooksMovies

Computers and ElectronicsComputersPhone SkillsTechnology Hacks

HealthMen's HealthMental HealthWomen's Health

RelationshipsDatingLoveRelationship Issues Hobbies and CraftsCraftsDrawingGames

Education & CommunicationCommunication SkillsPersonal DevelopmentStudying

Personal Care and StyleFashionHair CarePersonal Hygiene

QuizzesLove QuizzesPersonality QuizzesFun Games

Arts and EntertainmentFinance and BusinessHome and GardenRelationship Quizzes

Cars & Other VehiclesFood and EntertainingPersonal Care and StyleSports and Fitness

Computers and ElectronicsHealthPets and AnimalsTravel

[Ubuntu Steps with](https://ubuntu-steps-with.themaplelane.com/ubuntu-steps-with/20260826.html)

Education & CommunicationHobbies and CraftsPhilosophy and ReligionWork World

Family LifeHolidays and TraditionsRelationshipsYouth LOG IN Log in

Social login does not work in incognito and private browsers. Please log in with your username or email to continue. Facebook Google wikiHow Account No account yet? Create an account RANDOM Home Random Browse Articles TrendingNew Quizzes & Games All QuizzesHot Love Quizzes Personality Quizzes Fun Games Dating Simulator Learn Something New Forums Courses Happiness Hub Explore More Support wikiHow About wikiHow Log in / Sign up Terms of Use

wikiHow is where trusted research and expert knowledge come together. Learn why people trust wikiHow Categories Computers and Electronics Operating Systems Linux Ubuntu How to Change MAC Address on Ubuntu Download Article

Easily view and set a new MAC address on your computer Explore this Article Steps Steps   Other Sections Questions & Answers   Video   Tips and Warnings   Related Articles   Author Info Last Updated: April 14, 2026 Download Article X

wikiHow is a “wiki,” similar to Wikipedia, which means that many of our articles are co-written by multiple authors. To create this article, volunteer authors worked to edit and improve it over time. 

This article has been viewed 133,668 times.  Learn more...

This article will help you to change MAC address on Ubuntu using Terminal. It is very easy and simple!

Changing an Ubuntu MAC Address: Quick Steps Open Terminal.

Enter sudo -i followed by your password.

Type ip link set dev [device] down and hit Enter.

[How to Change](https://how-to-change.themaplelane.com/how-to-change/2026082622.html)

[Ubuntu Steps with](https://ubuntu-steps-with.northlist.xyz/ubuntu-steps-with/20260826.html)

Type in ip link set dev [device] address [new MAC address].

Enter ip link set dev [device] up to turn the device back on. Steps Download Article 1 Open Terminal. 2

Log in as root so type: sudo -i and then write your password. Advertisement 3

View your current address by typing: ip link show 4

Set the device down to avoid problems. Type: "ip link set dev xxxx down" where xxxx is the name of device you want to set down, so for example: ip link set dev wlan0 down 5

Change your MAC address. Write into terminal this: ip link set dev xxxx address xx:xx:xx:xx:xx:xx where xxxx is the device and xx:xx:xx:xx:xx:xx is your new MAC address. MAC addresses need hexadecimal digits (0-9 and a-f) which you can pick randomly. The command will look like: ip link set dev wlan0 address 74:d0:3b:9f:d8:48 6

Set up your device so type: ip link set dev xxxx up, where xxxx is the name of your device Advertisement Community Q&A  Search Add New Question Question

Is this a permanent change or just spoofing? Somone Community Answer

This will remain unchanged until you change it again.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 19Helpful 12 Question

If I dual boot, will the MAC address remain unchanged after I switch to Windows through restart? Community Answer

[How to Change](https://how-to-change.curblist.xyz/how-to-change/20260826.html)

Not necessarily. Every hardware network device (e.g., WiFi card) has its own MAC address. However, sometimes the OS (Windows or Linux) changes the MAC address. It differs from system to system and from configuration to configuration.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 5Helpful 6 Ask a Question 200 characters left

Include your email address to get a message when this question is answered. Submit Advertisement Video Tips

[Address on](https://address-on.swapstreet.shop/address-on/20260826.html)

Changing MAC address will help you for example when admin of your network block your MAC so you can bypass it. Thanks Helpful 0 Not Helpful 0 Submit a Tip 

All tip submissions are carefully reviewed before being published Name 

Please provide your name and last initial Submit Thanks for submitting a tip for review!  Advertisement You Might Also Like

3 Ways to Change a Computer's MAC Address in Windows How to Change a Mac Address on an Android How to Find the MAC Address of Your Computer

A Step-By-Step Guide to Aquire a New IP Address How to Change Your Mac's IP Address How to

Add or Change the Default Gateway in Linux

4 Quick Ways to Find the MAC Address on Your Windows 11 PC How to Find Your Mac Address on Samsung Galaxy 8 Easy Ways to Change Your IP Address

[How to Change Guitar Strings (Acoustic or Electric Guitars)](https://github.com/t4e8vauwlk/hllcdgr/blob/main/mobile-tire-service/2031-06-26-how-to-change-guitar-strings-acoustic-or-electric-guitars.md)

Easy Ways to Find a MAC Address on Your Network or Computer How to

Set Up MAC Address Filtering on Any Wireless Router How to Turn Off MAC Filtering Advertisement About This Article

wikiHow is a “wiki,” similar to Wikipedia, which means that many of our articles are co-written by multiple authors. To create this article, volunteer authors worked to edit and improve it over time. This article has been viewed 133,668 times.  How helpful is this? Co-authors: 5 Updated: April 14, 2026 Views: 133,668

Categories: Ubuntu | Computer Networking In other languages Spanish Japanese Print Send fan mail to authors

Thanks to all authors for creating a page that has been read 133,668 times. Is this article up to date? YesNo Advertisement

Cookies make wikiHow better. By continuing to use our site, you agree to our cookie policy. About This Article Click a star to vote Co-authors: 5 Updated: April 14, 2026 Views: 133,668 Quizzes & Games Discord Username Idea Generator Generate Names Leetspeak Translator & Generator Generate Roblox Name Generator Generate Names Gamertag Generator Generate Names You Might Also Like

3 Ways to Change a Computer's MAC Address in Windows How to Change a Mac Address on an Android How to Find the MAC Address of Your Computer

A Step-By-Step Guide to Aquire a New IP Address Trending Articles Am I Chopped Quiz Can We Guess How Tall You Are Quiz Kiss, Marry, Kill Quiz What’s the Name of My Crush? Trending Articles Finish the Lyrics TikTok Edition

Design a Morning Routine and Learn Your Superpower

Pick a Door and We'll Reveal What You're Missing What Kind of Doomed Am I? Take the Quiz. Face the Truth. 🔥 Am I Gay Quiz Do I Have a Type? Am I Hard to Love? Am I a Spoiled Brat? 🤔 Are You More... 🤔 How Tuff Am I? What Kind of Wolf Is My Personality?

Am I More Golden Retriever or Black Cat? Villain or Hero Quiz Featured Videos

The Right Way to Refrigerate and Freeze Fresh Green Beans

A Complete Guide to Shaving Your Body (and Preventing Razor Burn) How to

Play "What Are the Odds?" (Also Known As "Odds Are")

4 Easy Ways to Draw Cute and Realistic Cats Hot Takes Only 🔥 Overrated or Underrated Game

[MAC Address](https://mac-address.northlist.xyz/mac-address/20260826.html)

Do You Agree With These Spicy Hot Takes?

Do You Agree with These Hygiene Hot Takes?

Weird Would You Rather: What Do You Choose? Your Daily Dose of Fun 🎉

Do You Agree with These Popular Hot Takes?

Let Us Guess Your Age Based On Video Game Nostalgia Rizz Game: Test Your Rizz

Can You Pull Off The Perfect Heist? Prove Yourself Categories Computers and Electronics Operating Systems Linux Ubuntu

© 2026 wikiHow, Inc. All rights reserved. Use of site content is subject to our Terms of Use. wikiHow Newsletter You're all set! Helpful how-tos delivered to your inbox every week! Sign me up!

By signing up you are agreeing to receive emails according to our privacy policy. Home About wikiHow Experts Jobs Contact Us Site Map Terms of Use Privacy Policy Do Not Sell or Share My Info Not Selling Info Contribute Follow Us ×

Keep up with tech in just 5 minutes a week! Subscribe You're all set! X - - 609
