# FlexDialog
 This dialog can be designed manually
 
 Step 1: Add the JitPack repositor to your build file
 (Add it in your root build.gradle at the end of repostiories)
 
 allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}

Step 2: Add the dependency
(Add it in your root gradle at the end of repostiories)

dependencies {
		implementation 'com.github.WAI2017:FlexDialog:Tag'
}