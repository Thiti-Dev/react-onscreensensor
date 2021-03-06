This project was created and implemented by [Thiti Mahawannakit](https://www.facebook.com/thiti.developer)

## 🎓 React-OnScreenSensor

A React Library which provides the ability whether to check if the wrapped elements are being shown or not , most likely benifit in the use of Triggering Animation

## ✨ Features

- [x] Allowed multiple children inside
- [x] Using reference over timestamp [ PATCHED ]
- [x] Callback optional [ PATCHED ]


## 🚀 Getting Started

1. **Install the node modules.**

Installing via yarn / npm , your preference

```sh
yarn add react-onscreensensor
```

2. **Usage.**

```jsx
import React fron 'react';
import OnScreenSensor from 'react-onscreensensor'
const Example () => {
    return(
        <OnScreenSensor onChange={isVisible => console.log(`Visibility : ${isVisible}`)}>
            <div>Hello , Am i visible?</div>
        </OnScreenSensor>
    )
}

export default Example
```

### Changelog

## [1.0.7-stable] - Current Version
- Binding function once in constructor
- Remove event listener when un-mounting the right way ( mistaken fixed )

## [1.0.6-stable] - Deprecated
- Fixed the return boolean that always return false

## [1.0.42-a] - Deprecated
- Bundled files using webpack and all files are structured
- Updated Example of usage

## [1.0.41] - Deprecated
- Removed console logging when the class is created
- Removed unused state

## [1.0.4] - Deprecated
- Removed unused empty cycle

## [1.0.3] - Deprecated
- Renamed from onscreensensor to react-onscreensensor (The prefix does make sense)

## [1.0.1] - Deprecated ( old pkg name )
- Added a utils folder to contains separate function
- Fixed operators warning in functions
- Added README.md

## [1.0.0] - Deprecated ( old pkg name )
- Initialized all needed files

<p align="center">
  <b>: Contact me By :</b><br>
  <a href="https://www.facebook.com/thiti.developer">Facebook</a> |
  <a href="https://www.instagram.com/thiti.mwk/">Instagram</a> |
  <a href="https://www.linkedin.com/in/thiti-mahawannakit-558791183/">LinkedIn</a>
  <br><br>
  <img src="https://media.giphy.com/media/h1u6yvxlVKmfLiSryA/giphy.gif" width="250" height="220">
</p>

