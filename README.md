# Firebase Firestore - Titanium Module
Use the native Firebase SDK in Axway Titanium. This repository is part of the [Titanium Firebase](https://github.com/hansemannn/titanium-firebase) project.

## Requirements
- [x] iOS: Titanium SDK 6.2.0+
- [x] Android: Titanium SDK 7.0.0+


## Usage

```
var FireStore = require("firebase.firestore");
var animals = FireStore.createCollection("animals",{
			name : FireStore.TYPE.STRING,
			color : FireStore.TYPE.STRING,
			age : FirerStore.TYPE_INT,
			length : FireStore.FLOAT
});

animals.add({
		name: "cat",
		color: "black",
		age : 7,
		length : 123.4
});

```