# AppiumNotes
Appium install steps

##  1) Install Homebrew (The missing package manager for macOS)
```sh
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Test:
```sh
$ brew -v
```

##  2) Install npm (NodeJS & NPM via Homebrew)
```sh
$ brew install node
```

Test:
```sh
$ node -v
```

##  3) Install Carthage (Decentralized dependency manager for Cocoa)
```sh
$ brew install carthage
```

##  4) Install Appium (Tool for automating native, mobile web, and hybrid applications on iOS mobile, Android mobile, and Windows desktop platforms)
```sh
$ npm install -g appium
```

##  5) Install Appium doctor (To verify all of Appium's dependencies)
```sh
$ npm install -g appium-doctor
```

Test:
```sh
$ appium-doctor --ios
```
