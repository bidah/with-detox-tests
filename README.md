# with-detox-tests

An updated fork of the oficial [expo/with-detox-tests](https://github.com/expo/with-detox-tests). Upgraded to the latest Expo SDK (v32) with [Jest](https://jestjs.io/) as the test runner.

This working version was made possible thanks to [Josh Justice](https://twitter.com/CodingItWrong) tutorial. <https://blog.expo.io/testing-expo-apps-with-detox-and-react-native-testing-library-7fbdbb82ac87>

Found a couple of bottlenecks following the tutorial setup so I ended up catching up from the oficial Expo Docs but their repo was outdated.

Anyway hope this repo helps you catch up if you found yourself with similar issues running Expo with Detox or following the tutorial.

---

Demonstrates integration of the Detox gray box end-to-end testing library with Expo. Uses [detox](https://github.com/wix/Detox) 12.1.1+, [detox-expo-helpers](https://github.com/expo/detox-expo-helpers) and [expo-detox-hooks](https://github.com/expo/detox-tools).

![](https://raw.githubusercontent.com/expo/with-detox-tests/master/example.gif)

### Try it out

1. [Install dependencies](https://github.com/wix/detox/blob/master/docs/Introduction.GettingStarted.md#step-1-install-dependencies) (only follow Step 1 from this guide for now, the rest is already done in this project)
2. Run `./setup.sh`. This should grab the latest [Expo app](https://expo.io/tools) and place it inside `bin/`
3. Start the packager: `expo start` (if you don't have `expo` installed, `yarn global add expo`).
4. `yarn e2e`
