This is a quick starter for react native with useful libraries. It includes templates for following libraries:

- Airbnb react-native-map
- react-native-router-flux
- react-redux
- rdux-thunk
- shoutem-ui toolkit
- vector icons
- node/express api server


The starter is mainly tested on Android, but it should work fine on ios also (please raise an  issue if you find any problem on ios).

## Installation

The pre requisite to make this template useful is setting up android / ios sdk with corresponding tools. You can use android-studio with sdk-manager to download required build tools.

The next thing you require is installing react-native-cli:
```
npm install -g react-native-cli
```

After that follow the steps below:
```
git clone https://tamalsen@codelab.eyezon.in/experimental/react-native-map-shoutem-boiler-plate.git
```
```
yarn install
```

Now your application is ready with required libraries. 
In order to use react-native-maps you have to add a valid google map API key in your AndroidManifest.xml file (location: [project-root]/android/app/src/). You should already see the following line in that file. 
`
<meta-data
      android:name="com.google.android.geo.API_KEY"
      android:value="YOUR_API_KEY"/>
`

What you need to do is replace 'YOUR_API_KEY' with a valid google maps API key.

Open a shell prompt and run the api server by entering the following command.

```
node server/server.js
```

Finally, build and run the project either on emujlator or on a physical device through USB debugging.

```
react-native run-android
```

After the build is finished, run the following command to setup dev server.

```
react-native start
```

![Image of Yaktocat](git-img/Screenshot_2017-04-28-21-22-01-323_com.fanlikeyou.png)
![Image of Yaktocat](git-img/Screenshot_2017-04-28-21-45-07-450_com.fanlikeyou.png)
![Image of Yaktocat](git-img/Screenshot_2017-04-28-21-23-34-359_com.fanlikeyou.png)




