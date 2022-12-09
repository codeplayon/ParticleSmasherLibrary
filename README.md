# ParticleSmasherLibrary
image partical library 
How to
To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
allprojects {
		repositories {
	
			maven { url 'https://jitpack.io' }
		}
	}
  
  Step 2. Add the dependency
  
  dependencies {
	        implementation 'com.github.codeplayon:ParticleSmasherLibrary:Tag'
	}
  
   private ParticleSmasher mSmasher;
   mSmasher.with(view)
                        .setStyle(SmashAnimator.STYLE_FLOAT_TOP)
                        .setHorizontalMultiple(2)
                        .setVerticalMultiple(3)
                        .setDuration(2500)
                        .start();
