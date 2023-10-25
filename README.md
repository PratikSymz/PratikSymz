# Websites
## Polystore
Developed an online marketplace for 3D models. Creators upload models for customers to purchase. Hosts ~1000 3D rendered models.
- Creators upload a model file and scene file stored in [AWS S3](https://aws.amazon.com/s3/)
- [Sketchfab](https://sketchfab.com/) is used to display an editor with the existing scene to allow a creator to adjust the scene color, field of view (FOV), camera (X, Y, Z), and auto-rotate
- [Three.js](https://threejs.org/) used to load and run 3D model assets in a browser
- Used [React](https://react.dev/) for building the front end, [Redux](https://redux.js.org/) for state management, and [Axios API](https://axios-http.com/) for making HTTP calls from the browser.
- Used [Java Spring Boot](https://spring.io/projects/spring-boot) for building the back end and for performing user authentication.
- Used [MySQL](https://www.mysql.com/) for storing customer information, model information, cart information, and authentication tokens.

:link: [website](https://production--beamish-douhua-4abb1a.netlify.app/)

## Social Media Platform
Developed a social media platform that mimics the essential features of [twitter](https://twitter.com/), enabling users to sign up, share tweets, follow other users, and discover trending topics
- Used [React](https://react.dev/) for building the UI, [Redux](https://redux.js.org/) for state management, and [Axios API](https://axios-http.com/) for HTTP calls from the browser
- Used [MongoDB](https://www.mongodb.com/) for storing user and tweet data
- Built the back end using [Node.js](https://nodejs.org/en/about).
- Used [express.js](https://expressjs.com/) for creating HTTP requests and [mongoose.js](https://mongoosejs.com/) for querying MongoDB

:link: [website](https://a9--fabulous-dasik-7e58a1.netlify.app/tuiter/)

# Mobile Apps
## RMMB3R
Developed an Android notes application for users to create and save notes with custom colors and search and sort notes based on title, date, or color

- Used [Jetpack Compose](https://developer.android.com/jetpack/compose) to develop the UI, MVVM for layouts, [Dagger](https://dagger.dev/) and [Hilt](https://developer.android.com/training/dependency-injection/hilt-android) for dependency injection, [Kotlin coroutines](https://kotlinlang.org/docs/coroutines-overview.html) for asynchronous processing, and [SQLite](https://www.sqlite.org/index.html) for storage
- Implemented on-device storage for notes using [Room](https://developer.android.com/training/data-storage/room)

:link: [play store](https://play.google.com/store/apps/details?id=com.pratiksymz.note_app)

## TrailLines
Developed an Android mobile application for exploring hiking trails near the user. Search results can be sorted or filtered based on reviews, accessibility services, and things to do.

- Based on this project, the professor recommended a TA position for the course during Fall '22
- The messaging feature enables users to connect with other trail enthusiasts on the app. A friend request is used to allow users to connect with other hikers. The messaging system also provides a view of all users currently online.
- Used [Retrofit](https://square.github.io/retrofit/) for asynchronous network calls, [Firebase](https://firebase.google.com/) for notifications, messaging, authentication, and storage services, and [SQLite](https://www.sqlite.org/index.html) for storage

:link: [Github](https://github.com/PratikSymz/TrailLines)

# Desktop Applications
## Stock Market Simulator
A stock market simulator with real-time pricing using the [AlphaVantage API](https://www.alphavantage.co/documentation/).

Developed a stock market simulator with real-time pricing using the AlphaVantage API. This enabled my classmates to learn about and experiment with investing by creating portfolios, trading stocks, and applying automated investing strategies.

- Limited to stocks listed on the S&P 500, we used the [AlphaVantage API](https://www.alphavantage.co/documentation/) to fetch the closing value of a stock on a given day
- Implemented caching using [Redis](https://redis.io/) to limit calls to the AlphaVantage API
- Used Java for backend development
- Created a GUI using Swing and implemented an MVC architecture
- Stored the user's portfolio information in [MySQL](https://www.mysql.com/)
- Wrote tests using [JUnit](https://junit.org/junit5/) and [Mockito](https://site.mockito.org/)

:link: [Github](https://github.com/PratikSymz/Stock-Market_Simulator)

## Content Delivery Network Application
Developed a large-scale distributed system to serve Wiki query responses to clients via CDNs. Ranked amongst the top teams with the fastest response times

- Implemented query response caching and geographic DNS redirection, improving client response time by ∼ 15%.
- Implemented the CDN server in [Python](https://www.python.org/)
- Used [zlib](https://www.zlib.net/) for compressing responses before caching

:link: [Github](https://github.com/PratikSymz/CS5700_Project5)

## Raw Socket Application
Developed a wget FTP application to download files for input URLs

- Implemented TCP/IP headers and packet validation using checksum from scratch
- Implemented a three-way handshake and congestion control with the server to reduce packet loss by 10%

:link: [Github](https://github.com/PratikSymz/CS5700_Project4)

# Research Papers
## Performance Analysis of TCP Variants
Wrote a research paper presenting a study on the different variants of TCP that are used widely across multiple operating systems (Tahoe, Reno, NewReno, and Vegas) and analyzed their performance using various parameters (throughput, drop rate, and latency) under varying degrees of congestion, using NS-2 simulation

:link: [Paper](https://bit.ly/tcp-analysis)

# Resume
[Download](https://github.com/PratikSymz/PratikSymz/files/13151632/Pratik.Budhiraja.-.Resume.pdf)

