# Ionic Book Theme (Docs)

Please follow this documentation for https://mythemebox.com/template/ionic-book-theme/


### Prerequisites

Please use following versions of tools before starting the setup

```
node -v
12.8.1

npm -v
6.11.3

ionic -v
5.4.4

cordova -v
9.0.0

java -version
1.8.0_201
```

### Installation

Once you have the right tools, we can start our setup.

- Download your purchased code from your account.
- Extract zip file to the decided folder
- open your command prompt/terminal & change your working directory to the extracted folder
Then follow these commands
```
cd ionbook
npm install
ionic serve
```
These commands will automatically install all the required dependencies. `ionic serve` execute/run your app in the browser.

### Running on Device

```
ionic cordova platform add android
ionic cordova platform add ios
ionic cordova run android
ionic cordova run ios
```
Note: ios build requires mac


### Customization

**How to change content?**

Navigate to `ionbook/src/app/services/global.service.ts` & update your json & settings

**How to change colors**

Navigate to `ionbook/src/themes/variable.scss` & update the primary color code as per your need
