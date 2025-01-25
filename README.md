# News_Pushpam

The News Application is an iOS application designed to display the latest news headlines along with related information like article descriptions, images, likes, and comments. The app follows the Model-View-ViewModel (MVVM) design pattern to maintain a clean and scalable architecture.

Features:-

Fetch and display the latest news headlines from a news API. View article details, including title, description, and an image. Display likes and comments for each article fetched from a mock API. Open full articles in Safari using SFSafariViewController. Responsive UI with smooth data binding and table view updates.

Technologies Used:-
Language: Swift
UI Framework: UIKit
Architecture: MVVM
Networking: URLSession
Caching: Custom image caching
Concurrency: GCD (Grand Central Dispatch)

Clone the repository: git clone https://github.com/username/news_Pushpam.git

Open the project in Xcode: open NewsApp.xcodeproj
Install dependencies (if any) using CocoaPods or Swift Package Manager.
Build and run the project on a simulator or physical device.

API Details: https://newsapi.org/v2/top-headlines?country=us&apiKey=8edb2683cb784e1b97524f9a2a09f063
Response: List of news articles.
