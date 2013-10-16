iOS development tools repository
================================

__Getting started:__

> First, install the iOS SDK which is bundled with Xcode 5, the current version as I'm writing this. It's available on Mac App Store for free. Then you should start reading Programming with Objective-C, which is an excelent guide from Apple on how to use ObjC, iOS SDK main programming language. Then you have a lot of resources about diferent framework of the iOS SDK available at iOS Developer Center, but I would recommend to start with iOS Technology Overview, which explains the OS layers and the frameworks within each one. One important reading, even if you're not a UX professional, would be iOS Human Interface Guidelines, recently updated to iOS 7. Lastly, Apple recommends this document as the entry point for iOS developement, iOS App Programming Guide, excelent reading.  

Programming with Objective-C: https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html  
iOS Technology Overview: https://developer.apple.com/library/ios/documentation/Miscellaneous/Conceptual/iPhoneOSTechOverview/Introduction/Introduction.html#//apple_ref/doc/uid/TP40007898  
iOS Human Interface Guidelines: https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/index.html#//apple_ref/doc/uid/TP40006556  
iOS App Programming Guide: https://developer.apple.com/library/ios/documentation/iPhone/Conceptual/iPhoneOSProgrammingGuide/Introduction/Introduction.html  

__Intermediate:__

> Ray Wenderlich has a lot of tutorials on iOS on his blog, you should check those as you need them. If you haven't yet, you should start with concurrency topics on ObjC. Concurrency Programming Guide it's an excelent start. I think now it's the moment to start getting familiar with the most popular open source frameworks out there. AFNetworking it's an absolute brilliant implementation of async networking using the concurrency topics pointed before. Magical Record, AFIncrementalStore and fmdb are different wrapplers that solve the same issue: local storage, you should check out them and decide which one suits better your needs. There are also a lot of open source projects that resolve common user interface controls needs, you should ALWAYS check for those before starting to do your own. Lastly I would recommed to start reading about software desing patterns on cocoa, there are a lot of books out there, but If you are like me and you prefer short readings, I think you will love iOS Design Patters article from Ray Wenderlich blog. One of those design patters is used almost everywhere on iOS SDK: Key-Value Observing, you should read the Key-Value Observing Programming Guide from Apple. I would recommend also checking into third party tools like Cocoapods for dependency management, Gradle Xcode Plugin for a build system, RevealApp for runtime inspection, Deploymate for static analysis, TestFlight for beta testing deployment and AppCode for a wonderful IDE.  

Ray Wenderlich blog: http://www.raywenderlich.com/  
Concurrency Programming Guide: https://developer.apple.com/library/ios/DOCUMENTATION/General/Conceptual/ConcurrencyProgrammingGuide/Introduction/Introduction.html  
AFNetworking: https://github.com/AFNetworking/AFNetworking  
MagicalRecord: https://github.com/magicalpanda/MagicalRecord    
AFIncrementalStore: https://github.com/AFNetworking/AFIncrementalStore    
fmdb: https://github.com/ccgus/fmdb  
iOS Design Patterns: http://www.raywenderlich.com/46988/ios-design-patterns  
Key-Value Observing Programming Guide: https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/KeyValueObserving/KeyValueObserving.html  
CocoaPods: http://cocoapods.org/  
Gradle Xcode Plugin: http://openbakery.org/gradle.php  
RevealApp: http://revealapp.com/  
Deploymate: http://www.deploymateapp.com/  
TestFlight: https://testflightapp.com/  
AppCode: http://www.jetbrains.com/objc/  

__Advanced:__

> I can't consider myself an expert iOS developer, so this section probably would be an intermediate for most of the iOS developers out there. The first advance topic for me on iOS was runtime, Apple has a great guide on this topic. Then I would said that unit testing was pretty advanced to me, but there are great tools out there like OCMockito, for mocks and stubs, and OCHamcrest, for matchers. For functional testing I have used Frank (which use Cucumber). Objc.io newsletter is amazing! It covers advanced topics on iOS development with great examples. Matt Thompson has an excelent blog where it covers very specific topics of cocoa development, you definetly should check it out. Peter Steinberger is one of the best iOS runtime hackers out there, you should check his blog. Now, I would like to share how I make iOS apps. This depends on the project, but my preferred way to develop iOS apps (also, I have been doing this a lot recently) its using ReactiveCocoa, Mantle, AFNetworking and a lot of reactive extensions available out there, I actualy started developing my own extensions recently :). But this is generally a lot of code, and I also hate to write code, so I'm also using RestKit a lot recently, as I said before, it depends on the project.  

Objective-C Runtime Programming Guide: https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/ObjCRuntimeGuide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40008048-CH1-SW1  
OCMockito: https://github.com/jonreid/OCMockito  
OCHamcrest: https://github.com/hamcrest/OCHamcrest  
Frank: http://www.testingwithfrank.com/  
Objc.io: http://www.objc.io/  
Matt Thompson blog: http://nshipster.com/  
Peter Steinberger blog: http://petersteinberger.com/  
ReactiveCocoa: https://github.com/ReactiveCocoa/ReactiveCocoa  
Mantle: https://github.com/github/Mantle  
Reactive extensions search on GitHub: https://github.com/search?l=Objective-C&o=desc&q=reactive+&ref=searchresults&s=stars&type=Repositories  
RestKit: https://github.com/RestKit/RestKit 
