# iOS Knowledge Matrix


## User Interface

Qualified | Competent | Expert
:--|:--|:--
*Autolayout* | |
Anatomy of constraint, <br/>external and internal changes, autolayout vs frame-based layout |  Stackview, debugging autolayout, anchors, safe area, self-sized views, <br/>Hugging priority/Content compression resistance" | Layout directions (left-to-right/right-to-left), <br/>VFL, <br/>autoresizing masks (springs&struts)
*Xibs (Nibs), Storyboards* | |
xibs and/vs storyboards, custom UI elements in xibs and storyboards, file's owner, loading from xibs and storyboards programmaticaly, segue, pass data via segue, customization ui best practices | IBInspectable, IBDesignable, size classes,  xib vs nib, NIB object lifecycle, unwind segues, git conflicts in xibs and storyboards, xib's xml structure |
*Animations* | |
animations via autolayout, UIView.animate, CALayer, CAAnimation | facebook pop, UIDynamics, 3D animations, UIViewPropertyAnimator, CADisplayLink | SpriteKit? Adobe After Effects?
*Other* | |
Localizations<br/>[HIG](https://developer.apple.com/ios/human-interface-guidelines/overview/) | Internationalization i18n & Localisation l10n |

## Data persistence

Qualified | Competent | Expert
:--|:--|:--
*Core Data* | |
Core Data Stack & Architecture, Relationships, Data Types, fetching | Pefrormance, concurrency, multithreading, multiple contexts, changes and updates tracking | Migrations, nestedcontexts, profiling, persistence under the hood (SQLite, XML, Binary, In-memory). iCloud synchronization,Security
*Other approaches* | |
UserDefaults, KeyedArchiver | Realm, Keychain |


## Languages

Qualified | Competent | Expert
:--|:--|:--
*Swift* | |
Basic syntax, optionals, control flow, error handling, memory management (ARC), classes, structures, enums, functions, initialization/deinitialization, inheritance | Objective-CInteroperability, POP, generics, type safety, KVO/KVC, value and reference types, subscripts, bitwise operators, overflow operators, operator methods, access control | Swift performance, Swift + LLVM, method dispatch, swizzling, @dynamic, final, playgrounds, Swift Standard Library
*Objective-C* | |
Basic syntax, variables and types, collections, initializations | Blocks, categories, Integrating Swift into objc, C/C++ code usage inside Obj-C | Runtime, Class structure (isa), Method swizzling, MRC


## Networking

Qualified | Competent | Expert
:--|:--|:--
*URLSession* | |
NSURLSession basics, encoding/decoding of URL data, lifecycle of a URL Session | Multipart requests, response caching, handling redirects | Background handling, NSURLAuthentication, TLS Chain Validation, streams, sockets, NSURLConnection
*Response handling* | |
JSONSerialization, error handling | Codable/Decodable, NSCoding |
*Building a network layer* | |
Alamofire, mappers | Moya , CFNetwork|


## Deployment

Qualified | Competent | Expert
:--|:--|:--
Understanding of code signing, provisioning profiles, app schemes configuration. Launching app on device | Working with iTunes Connect, App Review Guidelines. Build automation, beta-testing tools and deployment platforms. Fastlane | Advanced automation skills (plugins, scripts)

## iOS essentials

Qualified | Competent | Expert
:--|:--|:--
UIViewController lifecycle, iOS app lifecycle, NotificationCenter |  Working with filesystem, background modes, xcode project structure |  |


## Multithreading

Qualified | Competent | Expert
:--|:--|:--
*Grand Central Dispatch* | |
basic knowledge about multithreading and concurrent programming, deadlocks, race conditions. async vs sync, main vs background |  Dispatch queues, units of work, prioritizing, quality of service, timing (time & after) | Dispatch groups, semaphores, dispatch I/O, dispatch sources. Interprocess communication, XPC Services |
*NSOperation* | |
basic knowledge about multithreading and concurrent programming, deadlocks, race conditions. |  Operation executing, cancelling and configuring. Operation states. NSOperationQueue. Subclassing and overriding. BlockOperation | Operation dependencies, NSOperationQueue |
*Thread (NSThread)* | |
| | Ability to work with Thread. Initializing, starting/stopping, state handling, prioritizing. Locks, NSRunLoop. |

## Marketing

Qualified | Competent | Expert
:--|:--|:--
Push Notifications, URL schemes |  Deep linking, Universal links, App Indexing | Advertisements (AdSupport, AdMob etc) |

## Testing

Qualified | Competent | Expert
:--|:--|:--
Basic knowledge of unit tests |  Complex unit tests, XCTest, Quick/Nimble (Kiwi for Obj-C) | TDD, UI tests, web testing and debugging |

## Xcode build system

Qualified | Competent | Expert
:--|:--|:--
 | xcodebuild, xcrun. Targets, bundles, frameworks, libraries. pbxproj, xcconfig, xcodeproj, xcworkspace, xcscheme, xctoolchain. Build phases, shell scripts, build rules, build configurations. | lldb, lipo, llbuild, swift package manager, linker. Flags |

## Security

Qualified | Competent | Expert
:--|:--|:--
 | Keychain, iOS security guidelines, TouchID, FaceID | Security framework - authorization and authentication, code signing, cryptography, result codes. Secure coding guide. iOS security overview |
 
## Performance
 
Qualified | Competent | Expert
:--|:--|:--
Basic knowledge of measuring app performance with Xcode instruments. Object Graph, Network Link Conditioner. UI optimization (opaque views, fat XIBs, image sizes, main thread blockers, layers vs paths etc) | Optimization modes in Xcode, whole module optimization, gzip compression, lazy load and reuse of views, caching, tableview and collectionview optimization, date formatters | Memory warnings handling, speeding up app launch time (static vs dynamic libraries, merging several frameworks into one monolithic) |

## Architecture Patterns

Qualified | Competent | Expert
:--|:--|:--
Delegate, MVC, observer, chain of responsibility, Singleton. | MVP, MVVM, VIPER, VIP, Router. State, Strategy, Visitor. Abstract Factory, Factory Method, Builder. Adapter, Decorator, Facade. | Flux, Redux. Mediator, Memento, Command, Prototype, Proxy |

## Functional/Reactive programming

Qualified | Competent | Expert
:--|:--|:--
Basic knowledge. Recursion | RxSwift/ReactiveCocoa/ReactiveSwift/ReactiveKit, higher order functions. | Futures&Promises. Pure functions. Complete understanding of reactive approach. Functors, Applicatives and Monads. |

## Hardware & Media

Qualified | Competent | Expert
:--|:--|:--
Basic AVFoundation, CoreBluetooth, AVKit | Core Audio. Advanced AVFoundation, CoreBluetooth, AVKit. WebKit. Core Telephony, Core Media | Core Motion, IOKit, Compression |

## Other

Qualified | Competent | Expert
:--|:--|:--
Basic MapKit & CoreLocation. Basic socials integration. Sharing | AddressBook, AddressBookUI, Messages, MessagesUI, Advanced MapKit & CoreLocation. Advanced socials integration. | In-app purchases |

## Optionals

Qualified | Competent | Expert
:--|:--|:--
App extensions | tvOS, watchOS, SpriteKit, SceneKit, HomeKit, HealthKit, EventKit | Metal, CoreGraphics, OpenGL, cross-platform development, ARKit CryptoTokenKit, SiriKit |
