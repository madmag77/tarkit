tarkit
======

untar and tar files on iOS and OS X. Also supports gzip tars. 

## Discussion
It is important to know that all the file system based tar commands used chunked/buffer methods to save memory. Due to the fact that tars are normally used to compress lots of content, It is strongly recommend to use those method versus the in memory data options.

## Credit

I got some of the tar code from here:

-[Light-Untar-for-iOS](https://github.com/mhausherr/Light-Untar-for-iOS)

## TODO

Need to add support for tar. Only does untar currently.

## Install ##

The recommended approach for installing tarkit is via the CocoaPods package manager (like most libraries).

## Requirements ##

HTTPKit requires at least iOS 5/OSX 10.7 or above.


## License ##

tarkit is license under the Apache License.

## Contact ##

### Dalton Cherry ###
* https://github.com/daltoniam
* http://twitter.com/daltoniam
* http://daltoniam.com
