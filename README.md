Component Plugin Core Lib, see https://github.com/DSAppTeam/ComponentCornerstone
```
buildscript {
    repositories {
        maven { url 'https://jitpack.io' }
    }
    dependencies {
	        implementation 'com.github.DSAppTeam:ComponentCore:1.0.6'
	}
}
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}

```