Scorekeeper - Solution Code
===========================

The Scorekeeper app keeps score for any game involving two teams.
The user can increment or decrement the score for each team using simple Button
views.

Pre-requisites
--------------

For this app you should be familiar with:
* Creating and running apps in Android Studio.
* Creating and edit UI elements using the Layout Editor, XML, and code.
* Adding onClick functionality to a button.
* Updating views at runtime.
* Adding menu items with onClick functionality.
* Passing data between activities using Intents.
* Defining a style.
* Applying a style to a view.
* Applying a theme to an activity or application both in XML and programmatically.
* Using drawable resources.


Getting Started
---------------

1. Download and open the app in Android Studio.

License
-------

Copyright 2018 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
------------
https://codelabs.developers.google.com/codelabs/android-training-espresso-for-ui-testing/index.html?index=..%2F..%2Fandroid-training#7
steps to test using Espresso:
1.In Android Studio, check for and install the Android Support Repository.
2.Add dependencies to the build.gradle (Module: app) file:
{testImplementation 'junit:junit:4.12'
androidTestImplementation 'com.android.support.test:runner:1.0.1'
androidTestImplementation 
           'com.android.support.test.espresso:espresso-core:3.0.1'}
3.Add the following instrumentation statement to the end of the defaultConfig section:
testInstrumentationRunner 
                "android.support.test.runner.AndroidJUnitRunner"
