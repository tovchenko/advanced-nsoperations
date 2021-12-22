# Advanced NSOperations

It is code project from the most interesting and still actual WWDC session from 2015. Unfortunately the original project is not available any more and of cource is not compilable in 2021. Due to this I had decided to prolongate it's life cycle and updated it.

This shows how to use NSOperations to simplify app architecture. It includes several different kinds of ready-to-use NSOperation subclasses to guarantee that your code will only execute if certain conditions have been met. By composing and chaining these operations together, you can quickly construct complex behaviors with extremely little code.

## Modifications

The original project was made in 2015. It used the 1st Swift version that's why many changes have been done by me to make it compilable and runnuble in XCode 13 and Swift 5: re-written KVO for Operation's state, updated deprecated methods and enums names, resolved type casts and errors handling, changed @escaping in closures, updated project's build settings and etc. During this process I was trying to keep the original logic as much as possible.

P.S.
When you run the app for the first time just swipe down to preload the data.


### Original video session

https://developer.apple.com/videos/play/wwdc2015/226/
