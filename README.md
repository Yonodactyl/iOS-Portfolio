<p align="center">
  <img src="https://user-images.githubusercontent.com/18172931/73115609-6ecc9680-3ef6-11ea-87be-ece3579bb556.png" width="200" height="200">
</p>
<h2 align="center">Yon Montoto</h2>
<p align="center">I am a self-driven, experienced and detail centric iOS Developer with a passion for simplistic and functional software.</p>
<p align="center">
  <a href="https://www.linkedin.com/in/yonmontoto/"><img src="https://img.shields.io/static/v1?label=LinkedIn&message=yonmontoto&color=blue&style=for-the-badge&logo=linkedin&logoColor=white"></a>&nbsp;&nbsp;
  <a href="https://github.com/Yonodactyl/iOS-Portfolio/files/5539754/YonMontotoResumeFall2020-Redacted.pdf"><img src="https://img.shields.io/static/v1?label=Resume&message=Download%20CV&color=green&style=for-the-badge"></a>&nbsp;&nbsp;
  <a href="https://apps.apple.com/vg/developer/yon-montoto/id1461254488"><img src="https://img.shields.io/static/v1?label=AppStore&message=Yon%20Montoto&color=red&style=for-the-badge&logo=apple&logoColor=white"></a>
</p><br>

## [Drinksly](https://apps.apple.com/us/app/drinksly/id1524569359)

While working at Starbucks I came across some very unique and delicious drinks. Often I never had time to remember the recipes and would just forget about them. Then came along TikTok and the drink creations went through the roof! At a certain point I thought: "Maybe we can reduce the friction from all the incorrect ordering and have a streamlined way to order these drinks?" This was the inception of Drinksly: A secret menu companion. Drinksly was my first SwiftUI and Core Data backed project. There were many challenges I faced like duplicate data and managing the Core Data stack to make sure that things are stored and replaced appropriately. Eventually the hardest part of the project was making sure that it followed the MVVM paradigm. Now the app is available for download on the AppStore above.

![DrinkslyGroup](https://user-images.githubusercontent.com/18172931/106216902-17fd3b00-61a2-11eb-9cdc-a6e9067c705e.png)

#### Technologies used
* Written with SwiftUI.
* Used Core Data to persist the data from CloudKit.
* CloudKit was the framework used to request and digest the data.
* Created my own SPM to use within the app.
* Followed the MVVM design paradigm.

## [Knight Spots](https://apps.apple.com/vg/app/knight-spots/id1461254489)

Knight Spots was a passion project of mine that I had when I started at the University of Central Florida. Noticing the plethora of students (and the limitation on all the parking spots) I decided to try and help my fellow Knights on campus by making finding a parking spot a little easier. Since the school already manages sensors at the garages I was able to recieve this data and parse it and create a ready to digest application for iOS. The biggest challenge that I faced when creating the app was understanding the use of delegates for passing data back and forth. I wanted the UI to change based on selected options and by adopting this pattern for data management I reduced the load on the view controllers.

![knightspots](https://user-images.githubusercontent.com/18172931/106217653-b1791c80-61a3-11eb-88b7-a1da1c7f66b2.png)

#### Technologies used
* Written entirely with UIKit.
* Used Firebase realtime database for the backend.
* Data is populated using a Python script that intercepts and delivers the data to the database.
* App follows the MVC paradigm.
* Protocols and delegates play a big role in the functionality.

