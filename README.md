<p align="center">
    <img width="90" height="90" src="https://i.ibb.co/T1CdkGm/insta.jpg">
</p>

# InstagramClone

>A clone of the Instagram app (October 2019) made with React, React-native and Typescript.

##  Preview
![App-demo](./src/screenshots/Demo.gif "Preview")

##  Screen (Home)
![App-demo](./src/screenshots/Demo1.png "Home Screen")

##  Screen (Profile)
![App-demo](./src/screenshots/Demo2.png "Profile Screen")

##  Screen  (Gallery)
![App-demo](./src/screenshots/Demo3.png "Gallery Screen")

##  Screen  (Camera)
![App-demo](./src/screenshots/Demo4.png "Camera Screen")

##  Screen  (Story)
![App-demo](./src/screenshots/Demo8.png "Story Screen")

##  Screen  (Comments)
![App-demo](./src/screenshots/Demo5.png "Comments Screen")

##  Screen  (Search By Tag)
![App-demo](./src/screenshots/Demo7.png "Search By Tag Screen")

##  Screen  (-#-)
![App-demo](./src/screenshots/Demo6.png "-#- Screen")

### Dependencies

- React Native (With Typescript)
- Native Base
- React Navigation
- Others (See package.json at the root folder)

## Get Started

#### Running in Android

On the command prompt run the following commands

```bash
$ git clone https://github.com/MuckT/Instagram-clone.git

$ cd InstagramClone

$ npm install

$ npx react-native start
```

Wait for dep graph to load

In Android Studio start a device to emulate on.

After the emulator starts in Another command prompt run the following commands

```bash
$ cd InstagramClone

$ react-native run-android
```

#### Running in iOS (Untested)

```bash
$ git clone https://github.com/Doha26/InstagramClone.git

$ cd InstagramClone

$ npm install

$ grep -rl "s.dependency 'React/Core'" node_modules/ | xargs sed -i '' 's=React/Core=React-Core=g' // To replace React/Core with React-core for all dependencies that use it 

$ cd ios && pod install && cd..

$ react-native run-ios
```

## Author

*	[Pavel Foujeu](mailto:foujeupavel@gmail.com)  
 
  [![Twitter: Pavel_FFP](https://img.shields.io/twitter/follow/Pavel_FFP?style=social)](https://twitter.com/Pavel_FFP)
  [![Linkedin: pavel-foujeu-8a8992142](https://img.shields.io/badge/-Pavel%20Foujeu%20-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/pavel-foujeu-8a8992142/)](https://www.linkedin.com/in/pavel-foujeu-8a8992142/)
  [![GitHub Doha26](https://img.shields.io/github/followers/Doha26?label=follow&style=social)](https://github.com/Doha26)


## Done with React-native

*	[MetFlix ](https://github.com/Doha26/MetFlix)

*	[Facebook challenge ](https://github.com/Doha26/Facebook-React-native)
