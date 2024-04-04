# FileSystem
filesystem for android using sqlite and kotlin

see an example app for this filesystem here 👇
www.github.com/anbu1506/urlvault

<a href="https://jitpack.io/#anbu1506/Filesystem" > Click here to see how to use this library </a>
maven-------------------------------------------------------
Step 1. Add the JitPack repository to your build file

    <repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
    </repositories>

Step 2. Add the dependency

    <dependency>
	    <groupId>com.github.anbu1506</groupId>
	    <artifactId>FileSystem</artifactId>
	    <version>Tag</version>
    </dependency>



Gradle------------------------------------------------------
Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.anbu1506:FileSystem:1.0'
	}
