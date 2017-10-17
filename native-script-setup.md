# Droid

## Install Java

``` bash
brew cask install java8
```

## RUBY
sudo gem install xcodeproj
sudo gem install cocoapods


## JENV

``` bash
brew install jenv
eval "$(jenv init -)"
jenv add /Library/Java/JavaVirtualMachines/jdk1.8.0_144.jdk//Contents/Home
jenv global 1.8
```

export JAVA_HOME=$(/usr/libexec/java_home)
brew cask install android-sdk

$ANDROID_HOME/tools/bin/sdkmanager "tools" "platform-tools" "platforms;android-25" "build-tools;25.0.2" "extras;android;m2repository" "extras;google;m2repository"

brew cask install android-studio

Run the instel haxm installer from the ~/Library/Android/sdk/extras/intel/Hardware_Accelerated_Execution_Manager folder


//brew cask install intel-haxm
npm i -g nativescript

create an emulator in the adv manager
start the emulator at least once

Everytime you open a terminal to work on native script, make sure to run
the load-ns-env
  load-ruby-env
  load-node-env
  load-java-env
    export JAVA_HOME=$(/usr/libexec/java_home)

  load-android-env
    export ANDROID_HOME=/usr/local/share/android-sdk
  

node:

I had to:
  
  xcode-select --reset if xcodebuild returns an error
  
I had EINTEGRITY issues when isntalling nativescript
  I did:
    npm uninstall -g nativescript
    npm cache clear --force
    npm install -g nativescript
    