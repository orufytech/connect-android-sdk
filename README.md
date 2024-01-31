# connect-android-sdk
Orufy Connect Android SDK

#### Quick Steps
Add it in your root **build.gradle** at the end of repositories:
```
dependencyResolutionManagement {
	repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
	repositories {
    	mavenCentral()
    	maven { url 'https://jitpack.io' }  // Add this if not present
	}
}
```
App Module gradle file **(app/build.gradle)**
```
dependencies {
    implementation 'com.github.orufytech:connect-android-sdk:{latest-release}'
}
```
## Contact us
If you have any questions, concerns, or feature requests, please don't hesitate to contact us at support@orufy.com
