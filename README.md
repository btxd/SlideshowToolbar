# Slideshow Toolbar
Slideshow Toolbar using slideshowimageview


![SlideshowToolbar Sample Material](https://raw.githubusercontent.com/JuL1205/SlideshowToolbar/master/screenshots/screen.gif)


 
# Usage

For a working implementation of this project see the `app/` folder.

* Include the following dependency in your project `build.gradle` file.

```groovy
repositories {
    maven {
        url 'https://dl.bintray.com/jul/maven/'
    }
}

...

compile 'com.funtory.jul:slideshow-imageview:1.0.1'
```
* For setting images
```java
 slideshowImageView.setImages(R.drawable.test1, R.drawable.test2, R.drawable.test3);
```

* For adding images
```java
slideshowImageView.addImages(R.drawable.test3, R.drawable.test4, R.drawable.test5);
```



# License

    Copyright 2016 JuL

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
