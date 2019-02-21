
# Android Apps Development


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