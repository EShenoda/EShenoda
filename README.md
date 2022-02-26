<h1 align="center">Hello, I'm Emil Shenoda</h1>
<h3 align="center">I'm currently working on a Bachelor's Degree in Mobile Development at Full Sail University.</h3>

<p align="center">
  <img src= "Images/FullSail.png" height=450>
</p>


## Table of contents

* [Status](#status)
* [iOS Examples](#ios-examples)
* [Android Examples](#android-examples)
* [Associate's Degree Courses](#associate-degree-program)
* [Bachelor's Degree Courses](#bachelor-degree-program)
* [Project Courses](#project-and-portfolio)
* [Copyright](#copyright)
* [Contact](#contact)


## Status


<h3 style="bold"> <font color="green"> Current GPA: 3.96  </font> </h4>


Current Course: Bachelor's Degree Final Project


![Github stats](https://github-readme-stats.vercel.app/api?username=EShenoda&count_private=true&show_icons=true&theme=tokyonight)


## iOS Examples

<h2 align="center">Card Matching Game</h3>

<p align="center"> <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"> <img src="https://developer.apple.com/design/human-interface-guidelines/macos/images/app-icon-realistic-materials_2x.png" alt="swift" width="40" height="40"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp; </a>  <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp; </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;</a>  <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" alt="swift" width="40" height="40"/> </a> </p>

__Main concepts__: 

* Core Data
* UITapGestureRecognizers
* Stack Views
* Button Collections
* Custom HeaderFooterViews
* Custom TableView Cells
* Size Classes for iPhone & iPad
* Swift Timers
* User Interface Idiom
* AVAudioPlayer
* Custom Animation


__Extra functionality to add to the user experience__:


AudioPlayer


```Swift
// Audio Player
func playSound(sound: String, type: String = "mp3") {
        if let path = Bundle.main.path(forResource: sound, ofType: type) {
            do {
                let url = URL(fileURLWithPath: path)
                audioPlayer = try AVAudioPlayer(contentsOf: url)
                audioPlayer?.play()
            } catch {
                print("ERROR")
            }
        }
    }
```


__Load Game Animation__

<p align="center">
  <img src= "Images/Loading.gif" height= 550>
</p>



___


__Animations for pulsating Start / Stop button__

__Flashing Colors__

<p align="center">
  <img src= "Images/Button.gif" height=550>
</p>

<p align="center">
  <img src= "Images/iPad.gif" height=550>
</p>


___



__Card Shake Animation__

<p align="center">
  <img src="Images/Shake.gif" height=550>
</p>


___


__Custom Segue Transition__

<p align="center">
  <img src="Images/Segue.gif" height=550>
</p>


___

__Layout Changes__

<p align="center">
  <img src="Images/Layout.gif" height=550>
</p>


___


__iPad: Add Progress Bar / 10 Extra Cards__


<p align="center">
  <img src= "Images/ProgressBar.gif" height=550>
</p>






## [Click Here to View More iOS Illustrations](https://github.com/EShenoda/iOS-Illustrations)



## Android Examples

<p align="center"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;<a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp; </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;</a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> </p>

### Advanced Layout Design

__Main concept__: Build a Google Play Store mockup.


Topics of research:

* Material Design
* Nested Layouts
* Parallax collapsing toolbar layout

<p align="center">
  <img src= "Images/Playstore-1.png" height=550>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp&nbsp;&nbsp;
<img src= "Images/Playstore-2.gif" height=350>
</p>


### Media Playback

__Main concept__: Build a media player app that plays songs in sequence. The application should be able to run while closed by using a foreground service. Some of the playback functionality will also be accessible through a notification. Notification allows the user to skip to previous or next song.


Topics of research:

* Media Player Class
* Finite State Machine
* Foreground Services 
* Expanded Style Notifications
* Audio Playback
* Seekbars & Runnables
* Raw Resources
* Retrieve meta-data from media file

<p align="center">
  <img src= "Images/Media-1.gif" height=350>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp&nbsp;&nbsp;
<img src= "Images/Media-2.gif" height=350>
</p>


<p align="center">
  <img src= "Images/Media-3.gif" height=350>
</p>


<p align="center">
  <img src= "Images/Media-5.gif" width=350>
</p>


<p align="center">
  <img src= "Images/Media-6.gif" height=350>
</p>


## [Click Here to View More Android Illustrations](https://github.com/EShenoda/Android-Illustrations)



<h4 align="center"> <font color="red"> **Links to Degree Program & Portfolio Courses require a GitHub account. Private repositories are available for collaborators. </font> </h4>



## Associate Degree Program

<h4> Visual Studios Platform </h4>

<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://devblogs.microsoft.com/visualstudio/wp-content/uploads/sites/4/2020/04/devblog-brand-visualstudiowin2019.png" alt="android" width="70" height="50"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp; </a> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;</a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp; </a> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="50" height="50"/> </p>

[Scalable Data Infrastructures](https://github.com/EShenoda/SDI)

[Advanced Scalable Data Infrastructures](https://github.com/EShenoda/ASD)

[Visual Frameworks](https://github.com/EShenoda/VFW)

___

## Bachelor Degree Program

<h4> iOS Platform </h4>

<p align="left"> <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"> <img src="https://developer.apple.com/design/human-interface-guidelines/macos/images/app-icon-realistic-materials_2x.png" alt="swift" width="40" height="40"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp; </a>  <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp; </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;</a>  <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" alt="swift" width="40" height="40"/> </a> </p>

[iOS](https://github.com/EShenoda/iOS)

[iOS Development I](https://github.com/EShenoda/iOS-Development-I)

[iOS Development II](https://github.com/EShenoda/iOS-Development-II)

[iOS Project](https://github.com/EShenoda/iOS-Project)

<h4> Android Platform </h4>

<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;<a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp; </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;</a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> </p>

[Google Programming Language](https://github.com/EShenoda/GPL)

[Advanced Interface Design](https://github.com/EShenoda/AID)

[Android Development I](https://github.com/EShenoda/Android-Development-I)

[Android Development II](https://github.com/EShenoda/Android-Development-II)

___

## Project and Portfolio

### [Project & Portfolio I](https://github.com/EShenoda/Portfolio-I)

<p align="left"> <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" /> <img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"</p>


### [Project & Portfolio II](https://github.com/EShenoda/Portfolio-II)

<p align="left"> <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/MAMP-005C84?style=for-the-badge&logo=mysql&logoColor=white" />  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" /> </p>


### [Project & Portfolio III](https://github.com/EShenoda/Portfolio-III)

<p align="left"> <img src="https://img.shields.io/badge/Windows%20Forms-0078D6?style=for-the-badge&logo=windows&logoColor=white"</p>

### [Project & Portfolio IV](https://github.com/EShenoda/Portfolio-IV)

<p align="left"> <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white" /> <img src="https://img.shields.io/badge/WatchOS-000000?style=for-the-badge&logo=ios&logoColor=white" /> <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white"/> <img src="https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white"/> <img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white"/> <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/> </p>


### [Project & Portfolio V](https://github.com/EShenoda/Portfolio-V)

<p align="left">  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white"/>  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white"/> </p>

##  Copyright
Private Repo for ESShenoda@student.fullsail.edu

All rights reserved: EmilShenoda@FullSailUniversity

## Contact
Created by [Emil Shenoda](mailto:eshenoda247@gmail.com) - feel free to contact me!

[Back to top](#Table-of-contents)