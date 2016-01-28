[![Build Status](https://snap-ci.com/reflectoring/infiniboard/branch/master/build_image)](https://snap-ci.com/reflectoring/infiniboard/branch/master)

# infiniboard
infiniboard is a customizable, general purpose project dashboard to assist you in gathering your most important project metrics in one place.


## developing server

Open a terminal and start a gradle deamon that builds continuously:
```
$ ./gradlew -t classes
```

Open another terminal and start the application:
```
$ ./gradlew bootRun
```

Now all changes are reloaded live.

## developing client

```
$ ./gradlew npmInstall
$ gulp
$ npm start
```


## license

> The MIT License (MIT)
> Copyright (c) 2016 reflectoring
> 
> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
> 
> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
