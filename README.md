# HKID Validator for Android

This is a Hong Kong ID (HKID) validator design for Android

### How to install

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}

Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.seventhmoon:hkid-validator:1.0.0'
	}
	     
### How to use

    HkidValidator.calcCheckDigit("A123456") //calculate the check digit in ( )
