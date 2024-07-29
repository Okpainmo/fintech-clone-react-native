# Adventure notes.

# Section 1: App installation/set-up.

- Installation command: 

```
npx create-expo-app <app name> -t tabs
```

- Second installation commands.

```
npx expo install expo-dev-client react-native-reanimated react-native-gesture-handler
```

- Pre-build command

```
npx expo prebuild
```

- Start prebuild command

```
npx expo run:android
```

```
npx expo run:android --device
```

## Important component: 

1. expo av - for playing a video in the background.

```
npx expo install expo-asset
```

2. expo assets - for selecting the file in the first place.

```
npx expo install expo-asset
```

**=> USING SUPER TINY LINES**

![screenshot](<./adventure-images/Screenshot%20(1528).png>)

E.g

```rn-css
height: Stylesheet.hairlineWidth
```

3. Installing Clerk Section.

```
npm i @clerk/clerk-expo // for Clerk core
```

```
npx expo install expo-secure-store // to safely store the token in a secure way on the device in combination with Clerk
```

```
npm i react-native-confirmation-code-field
```


