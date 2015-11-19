iOS Guide
=========

Swift Vs. Objective-C
---------------------
To develop apps for iOS, you'd need to learn either *Swift* or *Objective-C*.
Objective-C used to be the main language used for both iOS and OSX development,
however, Apple recently released Swift which is easier to read and learn. Swift
will likely be the future of iOS development, so we recommend learning swift.

Swift
^^^^^
Apple's `Swift Guide`_ is a great way to get acquainted with Swift's
syntax and capabilities.
If you want more specific examples with sample projects, take a look at
`Learn Swift`_

.. _`Swift Guide`: https://developer.apple.com/library/prerelease/ios/documentation/Swift/Conceptual/Swift_Programming_Language/BasicOperators.html#//apple_ref/doc/uid/TP40014097-CH6-ID60
.. _`Learn Swift`: http://www.learnswift.tips/

.. note::

   Since Swift is a new language it's constantly evolving and changing, so it's
   recommended to check Apple's `Swift blog`_. Your code might break with newer versions
   of Swift, but you can use the **Migrator** tool in Xcode to update your swift code to the
   newest version (Edit->Convert->swiftVersion). You might need to update the code
   yourself.

.. _`Swift blog`: https://developer.apple.com/swift/blog/


Objective-C
^^^^^^^^^^^
`Code School`_ has a fun interactive course that goes over its fundamental building
blocks. TeamTreeHouse_ offers a great course that covers the
basics and advanced concepts of Objective-C.

.. _`Code School`: http://tryobjectivec.codeschool.com/
.. _TeamTreeHouse: http://teamtreehouse.com/library/objectivec-basics


iOS Development Basics
----------------------

We highly recommend following Apple's `Start Developing iOS Apps Today`_ tutorial.
It tries to familiarize you with Xcode's interface, and important concepts behind
iOS development such as the view hierarchy, types of views, and the basics of auto-layout.

.. _`Start Developing iOS Apps Today`: https://developer.apple.com/library/ios/referencelibrary/GettingStarted/RoadMapiOS/

Another important concept in iOS development is the UIViewController life cycle,
and the MVC development pattern.

- View Controller Life Cycle

  * `iOS Essentials: The UIViewController Lifecycle`_
  * `Blog article`_ that focuses on events used to load a view and how they should be used.

- MVC Development Pattern

  * `Raywenderlich's iOS design patterns in swift`_

.. _`iOS Essentials: The UIViewController Lifecycle`: http://roadfiresoftware.com/2015/01/ios-essentials-the-uiviewcontroller-lifecycle/
.. _`Blog article`: https://medium.com/@SergiGracia/ios-uiviewcontroller-lifecycle-261e3e2f6133
.. _`Raywenderlich's iOS design patterns in swift`: http://www.raywenderlich.com/86477/introducing-ios-design-patterns-in-swift-part-1


Where to go from here?
----------------------
TeamTreehouse's iOS development track covers a good range of iOS features that
you will likely need with developing your nonprofit's app. However, their
Swift track isn't as sophisticated as the Objective-C track.

- `TeamTreeHouse iOS Swift track`_
- `TeamTreeHouse iOS Objective-C track`_

.. _`TeamTreeHouse iOS Swift track`: http://teamtreehouse.com/tracks/ios-development-with-swift
.. _`TeamTreeHouse iOS Objective-C track`: http://teamtreehouse.com/tracks/ios-development-with-objectivec

We also recommend you learn and get comfortable with the following View Controllers:

- UIViewController
- UITableViewController
- UICollectionViewController
- UIScrollViewController

Below are a couple of resources and courses that are useful; see :doc:`../resources/ios_resources`
for more.

- `Developing iOS 8 Apps with Swift by Stanford`_ :
  A great course recommended to people with some programming experience.
  The course used Swift 1.1, so expect some minor issues that can be dealt with
  easily.
- Raywenderlich_: Has a lot of tutorials that are clearly explained and are regularly
  updated. Should be the first place to go to if you want to learn about a specific
  controller and framework, since they probably have a tutorial about it.
- AppCoda_: Another good tutorial site.


.. _`Developing iOS 8 Apps with Swift by Stanford`: https://itunes.apple.com/us/course/developing-ios-8-apps-swift/id961180099
.. _Raywenderlich: http://www.raywenderlich.com/
.. _AppCoda: http://www.appcoda.com/

Tools & Libraries
^^^^^^^^^^^^^^^^^
A popular concept in programming is to not reinvent the wheel. There are a lot
of 3rd party libraries that make networking a breeze (see Alamofire_),
make simple beautiful charts (see `ios-charts`_), and simplify building UI (`awesome-ios-ui`_).

.. _Alamofire: https://github.com/Alamofire/Alamofire
.. _`ios-charts`: https://github.com/danielgindi/ios-charts
.. _`awesome-ios-ui`: https://github.com/cjwirth/awesome-ios-ui


In order to incorporate these libraries to your project, you can either add their
files manually into your project, or choose a dependency manager. Cocapods_ is a
popular Objective-C dependency manager, that recently added Swift support. It
simplifies the process of discovering and integrating 3rd party libraries.
Carthage_ is another dependency manager that is gaining popularity, however,
it can only be used on iOS8 projects and higher.


.. _Cocapods: https://cocoapods.org/
.. _Carthage: https://github.com/Carthage/Carthage


Apple Guides
^^^^^^^^^^^^

- `iOS App Programming Guide`_
- `View Programming Guide for iOS`_

.. _`iOS App Programming Guide`: https://developer.apple.com/library/ios/documentation/iPhone/Conceptual/iPhoneOSProgrammingGuide/
.. _`View Programming Guide for iOS`: https://developer.apple.com/library/ios/documentation/WindowsViews/Conceptual/ViewPG_iPhoneOS/
