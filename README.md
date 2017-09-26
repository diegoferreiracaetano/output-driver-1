[![N|Solid](http://www.autodoc.com.br/site/informativo/qr/img/logo-autodoc.png)](http://site.autodoc.com.br/)

# Output - Driver

Android Things user-space drivers [![Build Status](https://travis-ci.org/androidthings/contrib-drivers.svg?branch=master)](https://travis-ci.org/androidthings/contrib-drivers)
=================================

Sample peripheral drivers for Android Things.

NOTE: these drivers are not production-ready. They are offered as sample
implementations of Android Things user space drivers for common peripherals
as part of the Developer Preview release. There is no guarantee
of correctness, completeness or robustness.


How to use a driver
===================

Add in build.gradle
```gradle
allprojects {
	repositories {
		maven { url 'https://jitpack.io' }
	}
}
```

Add in dependecies
```gradle
dependencies {
	compile 'com.github.autodocdev:output-driver:1.0.0'
}
```


License
-------

Copyright 2017 Autodoc Inc.

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
```