# iOS Knowledge Matrix


## User Interface

Qualified | Competent | Expert
:--|:--|:--
*Autolayout* | |
[Anatomy of constraint](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/AutolayoutPG/AnatomyofaConstraint.html), <br/>[external and internal changes, autolayout vs frame-based layout](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/AutolayoutPG/) |  [Stackview](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/AutolayoutPG/LayoutUsingStackViews.html), [debugging autolayout](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/AutolayoutPG/DebuggingTricksandTips.html), [anchors](https://medium.com/@hassanahmedkhan/autolayouts-via-layout-anchors-5214b3f746a9), [safe area](https://medium.com/@hassanahmedkhan/playing-it-safe-with-safe-area-layout-guide-b3f09bdc71fe), [self-sized views](https://useyourloaf.com/blog/self-sizing-table-view-cells/), <br/>[Hugging priority/Content compression resistance](https://medium.com/@abhimuralidharan/ios-content-hugging-and-content-compression-resistance-priorities-476fb5828ef) | [Layout directions (left-to-right/right-to-left)](https://developer.apple.com/library/content/documentation/MacOSX/Conceptual/BPInternational/SupportingRight-To-LeftLanguages/SupportingRight-To-LeftLanguages.html), <br/>[VFL](https://www.raywenderlich.com/174078/auto-layout-visual-format-language-tutorial-2), <br/>[autoresizing masks (springs&struts)](http://www.thecodedself.com/autoresizing-masks/)
*Xibs (Nibs), Storyboards* | |
[xibs and/vs storyboards](https://codewithchris.com/xcode-using-storyboards-and-xibs-versus-creating-views-programmatically/), [custom UI elements in xibs and storyboards](https://cheesecakelabs.com/blog/building-custom-ui-controls-xcodes-interface-builder/), file's owner, [loading from xibs and storyboards programmaticaly](https://stackoverflow.com/questions/9282365/load-view-from-an-external-xib-file-in-storyboard), [segue](https://developer.apple.com/library/content/featuredarticles/ViewControllerPGforiPhoneOS/UsingSegues.html), [pass data via segue](https://www.appcoda.com/storyboards-ios-tutorial-pass-data-between-view-controller-with-segue/), customization ui best practices | [IBInspectable/IBDesignable](http://nshipster.com/ibinspectable-ibdesignable/), [size classes](https://useyourloaf.com/blog/size-classes/),  [xib vs nib](https://www.toptal.com/ios/ios-user-interfaces-storyboards-vs-nibs-vs-custom-code), NIB object lifecycle, [unwind segues](https://medium.com/@mimicatcodes/create-unwind-segues-in-swift-3-8793f7d23c6f), git conflicts in xibs and storyboards, xib's xml structure |
*Animations* | |
[animations via autolayout](https://useyourloaf.com/blog/animating-autolayout-constraints/),[UIView.animate](https://medium.com/ios-os-x-development/uiview-animation-in-swift-3-2b499abb58c5), [CALayer](https://medium.com/ios-os-x-development/uiview-animation-in-swift-3-2b499abb58c5), [CAAnimation](https://www.objc.io/issues/12-animations/animations-explained/) | facebook pop, [UIDynamics](https://www.raywenderlich.com/50197/uikit-dynamics-tutorial), 3D animations, [UIViewPropertyAnimator](https://www.shinobicontrols.com/blog/ios-10-day-by-day-day-4-uiviewpropertyanimator), [CADisplayLink](https://developer.apple.com/documentation/quartzcore/cadisplaylink) | SpriteKit? Adobe After Effects?
*Other* | |
Localizations<br/>[HIG](https://developer.apple.com/ios/human-interface-guidelines/overview/) | Internationalization i18n & Localisation l10n |

## Data persistence

Qualified | Competent | Expert
:--|:--|:--
*Core Data* | |
[Core Data Stack & Architecture](https://cocoacasts.com/what-is-the-core-data-stack), [Relationships](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/CoreData/HowManagedObjectsarerelated.html), Data Types, [fetching](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/CoreData/FetchingObjects.html) | [Performance](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/CoreData/Performance.html), [concurrency/multithreading/multiple contexts](https://cocoacasts.com/core-data-and-concurrency), [changes and updates tracking](changes and updates tracking) | [Migrations](https://www.raywenderlich.com/174025/lightweight-migrations-in-core-data-tutorial), nestedcontexts, profiling, persistence under the hood (SQLite, XML, Binary, In-memory). iCloud synchronization,Security
*Other approaches* | |
[UserDefaults](https://www.hackingwithswift.com/read/12/2/reading-and-writing-basics-userdefaults), [KeyedArchiver](http://nshipster.com/nscoding/) | [Realm](https://www.raywenderlich.com/112544/realm-tutorial-getting-started), [Keychain](https://www.andyibanez.com/using-ios-keychain/) |


## Languages

Qualified | Competent | Expert
:--|:--|:--
*Swift* | |
[Basic syntax](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/TheBasics.html#//apple_ref/doc/uid/TP40014097-CH5-ID309), [optionals](https://developer.apple.com/documentation/swift/optional), [control flow](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/ControlFlow.html), [error handling](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/ErrorHandling.html#//apple_ref/doc/uid/TP40014097-CH42-ID508), [memory management (ARC)](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/AutomaticReferenceCounting.html#//apple_ref/doc/uid/TP40014097-CH20-ID48), [classes, structures](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/ClassesAndStructures.html#//apple_ref/doc/uid/TP40014097-CH13-ID82), [enums](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Enumerations.html#//apple_ref/doc/uid/TP40014097-CH12-ID145), [functions](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Functions.html#//apple_ref/doc/uid/TP40014097-CH10-ID158), [initialization](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Initialization.html#//apple_ref/doc/uid/TP40014097-CH18-ID203)/[deinitialization](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Deinitialization.html#//apple_ref/doc/uid/TP40014097-CH19-ID142), [inheritance](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Inheritance.html#//apple_ref/doc/uid/TP40014097-CH17-ID193) | [Objective-C Interoperability](https://developer.apple.com/library/content/documentation/Swift/Conceptual/BuildingCocoaApps/InteractingWithObjective-CAPIs.html#//apple_ref/doc/uid/TP40014216-CH4-ID35), [POP](https://www.appcoda.com/protocol-oriented-programming/), [generics](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Generics.html#//apple_ref/doc/uid/TP40014097-CH26-ID179), [type safety](http://www.dummies.com/programming/macintosh/type-safety-in-swift/), [KVO/KVC](https://www.uraimo.com/swiftbites/kvo-and-kvc-in-swift), [value and reference types](https://developer.apple.com/swift/blog/?id=10), [subscripts](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/Subscripts.html#//apple_ref/doc/uid/TP40014097-CH16-ID305), [bitwise operators, overflow operators, operator methods](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/AdvancedOperators.html), [access control](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/AccessControl.html#//apple_ref/doc/uid/TP40014097-CH41-ID3) | [Swift performance](https://github.com/apple/swift/blob/master/docs/OptimizationTips.rst), [Swift + LLVM](https://www.infoworld.com/article/3247799/development-tools/what-is-llvm-the-power-behind-swift-rust-clang-and-more.html), [method dispatch](https://www.raizlabs.com/dev/2016/12/swift-method-dispatch/), [swizzling](http://nshipster.com/swift-objc-runtime/), [@dynamic](https://cocoacasts.com/what-does-the-dynamic-keyword-mean-in-swift-3/), final, playgrounds, Swift Standard Library
*Objective-C* | |
[Basic syntax](https://www.tutorialspoint.com/objective_c/objective_c_basic_syntax.htm), [variables](https://www.tutorialspoint.com/objective_c/objective_c_variables.htm) and [types](https://www.tutorialspoint.com/objective_c/objective_c_data_types.htm), [collections](https://www.objc.io/issues/7-foundation/collections/), [initializations](https://developer.apple.com/library/content/documentation/General/Conceptual/CocoaEncyclopedia/Initialization/Initialization.html) | [Blocks](https://medium.com/@amyjoscelyn/blocks-and-closures-in-objective-c-2b763e9e0dc8), [categories](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/CustomizingExistingClasses/CustomizingExistingClasses.html), [Integrating Swift into ObjC](https://developer.apple.com/library/content/documentation/Swift/Conceptual/BuildingCocoaApps/MixandMatch.html), [C/C++ code usage inside Obj-C](https://www.sitepoint.com/using-c-and-c-in-an-ios-app-with-objective-c/) | [Runtime](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/ObjCRuntimeGuide/Introduction/Introduction.html), [Class structure (isa)](https://www.cocoawithlove.com/2010/01/what-is-meta-class-in-objective-c.html), [Method swizzling](https://medium.com/@abhimuralidharan/method-swizzling-in-ios-swift-1f38edaf984f), [MRC](https://www.raywenderlich.com/2657/memory-management-tutorial-for-ios)


## Networking

Qualified | Competent | Expert
:--|:--|:--
*URLSession* | |
[NSURLSession basics](https://www.raywenderlich.com/158106/urlsession-tutorial-getting-started), encoding/decoding of URL data, lifecycle of a URL Session | Multipart requests, response caching, handling redirects | Background handling, NSURLAuthentication, [TLS Chain Validation](https://developer.apple.com/library/content/documentation/NetworkingInternetWeb/Conceptual/NetworkingOverview/SecureNetworking/SecureNetworking.html), [streams, sockets](https://www.raywenderlich.com/157128/real-time-communication-streams-tutorial-ios), [NSURLConnection](https://www.objc.io/issues/5-ios7/from-nsurlconnection-to-nsurlsession/)
*Response handling* | |
[JSONSerialization](https://developer.apple.com/swift/blog/?id=37), error handling | [Codable/Decodable](https://developer.apple.com/documentation/foundation/archives_and_serialization/encoding_and_decoding_custom_types), [NSCoding](http://nshipster.com/nscoding/) |
*Building a network layer* | |
[Alamofire](https://github.com/Alamofire/Alamofire), mappers | [Moya](https://github.com/Moya/Moya) , [CFNetwork](https://developer.apple.com/library/content/documentation/Networking/Conceptual/CFNetwork/Introduction/Introduction.html)|


## Deployment

Qualified | Competent | Expert
:--|:--|:--
[Understanding of code signing, provisioning profiles](https://medium.com/ios-os-x-development/ios-code-signing-provisioning-in-a-nutshell-d5b247760bef), [app schemes configuration](https://medium.com/m/global-identity?redirectUrl=https://zeemee.engineering/how-to-set-up-multiple-schemes-configurations-in-xcode-for-your-react-native-ios-app-7da4b5237966),  Launching app on device | Working with iTunes Connect, [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/). Build automation, beta-testing tools and deployment platforms. [Fastlane](https://fastlane.tools) | Advanced automation skills (plugins, scripts)

## iOS essentials

Qualified | Competent | Expert
:--|:--|:--
[UIViewController lifecycle](https://blog.caramba.io/ios-uiviewcontroller-lifecycle-261e3e2f6133), [iOS app lifecycle](https://developer.apple.com/library/content/documentation/iPhone/Conceptual/iPhoneOSProgrammingGuide/TheAppLifeCycle/TheAppLifeCycle.html), [NotificationCenter](https://medium.com/@JoyceMatos/using-nsnotificationcenter-in-swift-eb70cf0b60fc) |  [Working with filesystem](https://developer.apple.com/library/content/documentation/FileManagement/Conceptual/FileSystemProgrammingGuide/FileSystemOverview/FileSystemOverview.html), [background modes](https://www.raywenderlich.com/143128/background-modes-tutorial-getting-started), Xcode project structure |


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
[Push Notifications](https://www.raywenderlich.com/156966/push-notifications-tutorial-getting-started), [URL schemes](https://www.appcoda.com/working-url-schemes-ios/) | [Deep linking, Universal links](https://medium.com/@abhimuralidharan/universal-links-in-ios-79c4ee038272), App Indexing | Advertisements (AdSupport, AdMob etc) |

## Testing

Qualified | Competent | Expert
:--|:--|:--
[Basic knowledge of unit tests](https://www.raywenderlich.com/150073/ios-unit-testing-and-ui-testing-tutorial) |  Complex unit tests, [XCTest](https://www.objc.io/issues/15-testing/xctest/), [Quick/Nimble](https://github.com/Quick/Nimble) ([Kiwi](https://github.com/kiwi-bdd/Kiwi) for Obj-C) | [TDD](https://blog.codecentric.de/en/2015/11/introduction-to-tdd-in-ios/), [UI tests](https://medium.com/@johnsundell/getting-started-with-xcode-ui-testing-in-swift-ac7b1f5101e5), web testing and debugging |

## Xcode build system

Qualified | Competent | Expert
:--|:--|:--
 | xcodebuild, xcrun. Targets, bundles, frameworks, libraries. pbxproj, xcconfig, xcodeproj, xcworkspace, xcscheme, xctoolchain. Build phases, shell scripts, build rules, build configurations. | lldb, lipo, llbuild, swift package manager, linker. Flags |

## Security

Qualified | Competent | Expert
:--|:--|:--
 | Keychain, [iOS security guidelines](https://developer.apple.com/library/content/documentation/Security/Conceptual/SecureCodingGuide/Introduction.html), [TouchID, FaceID](https://www.raywenderlich.com/179924/secure-ios-user-data-keychain-biometrics-face-id-touch-id) | [Security framework - authorization and authentication](https://developer.apple.com/library/content/documentation/Security/Conceptual/AuthenticationAndAuthorizationGuide/Introduction/Introduction.html), code signing, cryptography, result codes. Secure coding guide. [iOS security overview](https://developer.apple.com/documentation/security) |

## Performance

Qualified | Competent | Expert
:--|:--|:--
[Basic knowledge of measuring app performance with Xcode instruments](https://medium.com/@kazmiekr/what-every-ios-developer-should-be-doing-with-instruments-d1661eeaf64f). [Object Graph](https://useyourloaf.com/blog/xcode-visual-memory-debugger/), [Network Link Conditioner](https://useyourloaf.com/blog/network-link-conditioner/). UI optimization (opaque views, fat XIBs, image sizes, main thread blockers, layers vs paths etc) | Optimization modes in Xcode, [whole module optimization](https://useyourloaf.com/blog/swift-whole-module-optimization/), gzip compression, lazy load and reuse of views, caching, [tableview and collectionview optimization](https://medium.com/capital-one-developers/smooth-scrolling-in-uitableview-and-uicollectionview-a012045d77f), date formatters | Memory warnings handling, [speeding up app launch time](https://useyourloaf.com/blog/slow-app-startup-times/)([static vs dynamic libraries](https://www.ca.com/us/developers/mas/blog/dynamic-versus-static-framework-in-ios.html), merging several frameworks into one monolithic) |

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
Basic AVFoundation, CoreBluetooth, AVKit | Core Audio. Advanced AVFoundation, CoreBluetooth, AVKit. WebKit. Core Telephony, Core Media | Core Motion, IOKit, Compression

## Other

Qualified | Competent | Expert
:--|:--|:--
Basic MapKit & CoreLocation. Basic socials integration. Sharing | AddressBook, AddressBookUI, Messages, MessagesUI, Advanced MapKit & CoreLocation. Advanced socials integration. | In-app purchases |

## Optionals

Qualified | Competent | Expert
:--|:--|:--
App extensions | tvOS, watchOS, SpriteKit, SceneKit, HomeKit, HealthKit, EventKit | Metal, CoreGraphics, OpenGL, cross-platform development, ARKit CryptoTokenKit, SiriKit |

# Android Knowledge Matrix


## User Interface

Qualified | Competent | Expert
:--|:--|:--
Activity, fragment, view group, view | Material design principles; material design implementation in support library; draw canvas, layout inflater, measuring view tree | Remote views; view tree observer; rendering optimization
*Layouts* | |
Linear Layout, Frame Layout, Relative Layout | Constraint Layout, Coordinator Layout, Pull-to-refresh, Drawer |
*Styles and Themization* | |
Android themes; day-night theme; status bar themization; text appearance; difference between style and theme attributes | |
*Animations* | |
Custom and system animations; object animator, property animation; animation resources; animation set and complex animations; animating constrains; vector animations; animate layout changes; recycler view animations; animate view | Optimization animation; complex vector animation; executing animations on render thread; application and fragment transition with shared element |
*Cuctom Chrome Tabs* | |
Using web view vs Chrome Tabs | Chrome tabs customization; using KeepAlive service; cutom controls | flow architecture to intercept results
*Notifications* | |
Notification Manager, Notification Builder, Notification Parameters | Using Pending Intents in notifications; using resources for notifications | Notifications in Oreo, channels; Push Notifications; Urbanairship, Pushwoosh; Using console to test notification
*Remote Views* | |
Application Widget and Pin | Lock guard themization, using remore views for Custom Chrome tabs |
*Other* | |
Resource types | Localization; Vector Drawables, Animated Vector Drawables, importing resources | External Resources; using tools to mock resources for tests

## Data persistence

Qualified | Competent | Expert
:--|:--|:-
SQLite, Database helper, Shared Preference Manager | Realm, Firebase Storage; Content resolver and Content provider, Room database; | Data synchronization, backup, restoring device, changing device

## Languages

Qualified | Competent | Expert
:--|:--|:-
*Java* | |
Primitive types; loop and branch syntax, blocks, local variables; operation and operand order; scopes; packages, wildcard import, static import; inheritance; method signature; incapsulation; class, abstract class, enum, interface, annotation; Serializable interface; final keyword; immutable pattern; String and datetime basic operations; Checked and unchecked Exceptions; try-catch syntax; java-beans, POJO; singleton, setters, getters, builders | Collections; Atomic types; Concurrency programming: synchronization, threads, executors, futures, thread safe collections, fork-jon framework; generics; Arrays and Objects utility classes; reflexions; Annotations and preprocessors; auto-closeable try catch; work with filesystem NIO2; lambdas, functional interfaces, default method; locales, formatting and internationalization; creating own annotations | Streams; javax; guava; data structures; sorting algorythms; big data optimization; math extensions; parallel programming; blockchains; matrix computations; O-complexity of basic algorythms; grpc (.protobuff), gson
*Kotlin* | |
Scopes, val and var keywords, NPE safe; migration java class to Kotlin | Extensions, coroutines, companion objects |

## Networking

Qualified | Competent | Expert
:--|:--|:-
HttpURLConnection, OkHttp, basic REST | Socket.IO, MQTT, XMPP (Jabber), TLS; RetroFit, Volley; Download manager; handling network changes | Certificate pinning, SSLSocketFactory interception; Samsung Smart switch

## Android essentials

Qualified | Competent | Expert
:--|:--|:-
*App Fundamentals* | |
Manifest; App Components; system services available from context | User id, proces id, android id; AsynckTask, Loaders; Fragment Manager tree; Android specific classes: Sparse Array, Text Utils | Support Java 8 in Android limitations;
*App Components* | Lollipop, Marshmallow, Oreo specific work with components; themization and localization context |
Context: application context, services, activities, broadcast receivers; Context wrappers | |
*Manifest* | |
Manifest structure | |
*Activities* | |
Activity lifecycle, activity manager; starting activities, starting activities for result | Activity lifecycle callbacks; task, activity, affinity; shared element; launch modes; start activity flags; saving state | Persistable activity; starting foreign activity; activity and multi-process
*Fragments* | |
Fragment Manager, Child Fragment Manager; Fragment Lifecycle | |
*Services* | |
Start service, bind service; Service, IntentService, JobService | Services in Lollipop, Marshmallow and Oreo; starting service security issues; binding flags and types; starting foreground service |
*Broadcast Receivers* | |
Main purpose, sending broadcasts | Security issues sending broadcasts; Local Broadcast Manager | Sticky broadcasts
*Content Providers* | |
Main purpose for content providers; known system content providers; content resolver; system preferences | Creating content provider; database helper, migration, contract, urls |
*Intercomponent communication* | |
Intents, intent filters, actions, categories | Binder, aidl files; Parcellable vs Object stream (Serializable); marshalling data using Parcel; using content providers; exported activities and services; running intent as user; resolving permission for contacts; activity picker, contact picker, account picker; Deeplinks | Using power locks, secure communication, activity manager flow switching activities; App Indexing; App Links

## Testing

Qualified | Competent | Expert
:--|:--|:-
Instrumentation Tests, Espresso, UIAuthomator; unittest and android test; popular test runners; mocks and stubs | PowerMock, Mockito, Multidex runner, Roboelectric; Mocking context; Creating Rules |

## Build system

Qualified | Competent | Expert
:--|:--|:-
*Build environment* | |
Android Studio, Eclipse; adding classes, resources; navigation panels | Gradle, cmake; repositories, artifacts; instant run optimization; libraries, modules; maven project; signing keystores; .jar, .aar, .so, .dex, .class; aapt2, shrinking resources; build vatiants, flavors | Groovy, gradle tasks; errorprone; compile preprocessors; gragle plugins: android, firebase, kotlin; Lombok
*Java Machine in Android* | |
Java machine environment; UI and background threads | JNI, embedding C++ libraries; render thread; zygote, process; multidex, D8 | Kernel versions; using kernel libraries; using HAL to launch own system implementation; Class loader tree

## Security

Qualified | Competent | Expert
:--|:--|:-
Permitions, permition levels, groups; file system permitions; runtime permitions | Account Management; User Management; Lock types; Lock Guard; Confirm Credentials; Fingerprint Manager; resolving runtime permitions; share permitions for external activities; fileholder permitions; Keychain | Android Keystore (version related difference, hardware backed); Trust Zone: DEK, KEK; Safety Net; available security algorythms depending on version; DRM; system permissions; Kiosk mode; boot aware mode; root permissions; device administrator

## Performance

Qualified | Competent | Expert
:--|:--|:-
*Memory management* | |
handling memory callbacks; memory alocation; retain release; drawing canvas | increase memory limits; caching strategies; LRU collections; ashmem; heap | Garbage collector; row hammer attack; uisng leak canary
*Profiling App* | |
ADB integration, monitoring memory | Memory dumps |
*Battery Management* | |
Power optimization best practices | Dump battery stats |

## Architecture Patterns

Qualified | Competent | Expert
:--|:--|:-
MVC, MVP, MVVM, SOLID, Clean Architecture, KISS; | TDD, DDD; GOF Patterns |

## Functional/Reactive programming

Qualified | Competent | Expert
:--|:--|:-
*RxJava* | |
Reactive programming concepts; using lambdas; subscribers, observers | Difference RxJava 1 and 2; transformers; rx functional interfaces; publishers and thread safe; schedulers | Mocking RxJava schedulers

## Hardware & Media

Qualified | Competent | Expert
:--|:--|:-
Camera and Gallery; Location Manager; Sensor Manager; BlueTooth manager | Android TV, Smart watches, Google glass |

## Other

Qualified | Competent | Expert
:--|:--|:-
*Data Binding Library* | |
MVVM concept; data binding inflator; bindings; observable fields | binding adaptors |
*Support Library* | |
AppCompatActivity, AppCompat... components | ContextCompat utility class; Material design with Support Library |
*Play Services* | |
Basic components of play services; Google maps | |
*Continuous Integration* | |
basic principles; Google Test Lab | Jenkins, Fabric, Crashlytics, Leak Canary; deploying apps onto play market | Bitrise, Fastline; gradle signing task
*Source control* | |
Git, git-flow; branches, repositories, commits | git hooks; Gerrit, gitlab; managing git history; garbage collection; merging strategies; integration git and Android Studio |
*Project Management* | |
Basic knowledge of JIRA; tickets, stories, estimations, estimation strategies, time reporting, kanban | |
*Dependency Injection* | |
dependency injection principles; DDD concept; basic annotations | Dagger Android; Dagger 1 and 2 difference; Object graph; Scopes, components, subcomponents |

## Optionals

Qualified | Competent | Expert
:--|:--|:-
*Android Platform Architecture* | |
Dalvik, ART; Android framework; System apps | IPC; Kernel, drivers, Binder, HAL, Android framework | Trust Zone, Trusty; Andoid without framework; AOSP
*Instant App* | |
Feature modules, instant app limits | Dynamic links |
