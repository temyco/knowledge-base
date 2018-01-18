## iOS Competency

### iOS Knowledge Matrix


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
Localizations<br/>[HIG](https://developer.apple.com/ios/human-interface-guidelines/overview/) | Internationalization i18n, i10 |

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
Alamofire, mappers | Moya |


## Deployment

Qualified | Competent | Expert
:--|:--|:--
Understanding of code signing, provisioning profiles,
app schemes configuration. Launching app on device | Working with iTunes Connect, App Review Guidelines. Build automation, beta-testing tools and deployment platforms. Fastlane | Advanced automation skills (plugins, scripts)
