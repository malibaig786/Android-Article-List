# Android-Article-List
This is the list of Android article divided into categories

# Content
- [Hacking](#Hacking)
- [New Things](#New_things)
- [Learning Android Development](#Learning)
- [Building Block](#Building)
     - [Activity](#Activity)
     - [Fragment](#Fragment)
          - [Fragment Testing](#Testing)
     - [Service](#Service)
     - [BroadCast Receiver](#BroadCast)
     - [Content Provider](#Content)
     - [Intent](#Intent)
     - [Notification](#Notification)
     - [Context](#Context)
- [UI](#UI)
     - [Views_OR_Widgets](#Views_OR_Widgets)
     - [Layouts](#Layouts)
     - [DataBinding](#Databinding)
- [Animations](#ANIMATIONS)
  - [MotionLayout](#MotionLayout)
- [Data_Persistence](#Data_Persistence)
     - [SharedPreferences](#SharedPreferences)
     - [Database](#Database)
     - [File](#File)
     - [FireBase](#Firebase)
- [Multimedia](#Multimedia)
     - [Audio_Focus](#Audio_Focus)
     - [Audio](#Audio)
     - [Exoplayer](#Exoplayer)
     - [Camera](#Camera)
- [Animation](#Animation)
- [MultiThreading](#MultiThreading)
     - [RxJava](#RxJava)
- [Fetching_Data_Online](#Fetching_Data_Online)
     - [Retrofit](#Retrofit)
     - [Gson](#Gson)
     
________________________________________________________________________________________________________________________________________
# Hacking
- [How to avoid reverse engineering of an APK file?](https://stackoverflow.com/questions/13854425/how-to-avoid-reverse-engineering-of-an-apk-file?noredirect=1&lq=1)
- [How can I protect sqlite db in android from being stolen](https://stackoverflow.com/questions/20842060/how-can-i-protect-sqlite-db-in-android-from-being-stolen)
# New_things
- [Now in Android #20](https://medium.com/androiddevelopers/now-in-android-20-9f2072f43ed6)
- [App Actions & Slices — Extending your app to Google Search & Google Assistant](https://android.jlelse.eu/app-actions-slices-extending-your-app-to-google-search-google-assistant-30dd803d4e79)
- [Android App Bundle](https://twitter.com/GooglePlayDev/status/1054429042034782208)
- [Exploring the Android App Bundle](https://medium.com/google-developer-experts/exploring-the-android-app-bundle-ca16846fa3d7)
- [Instant apps](https://twitter.com/lehtimaeki/status/1058071656067928065)
- [D8: Used to compile your project's Java bytecode into DEX bytecode](https://developer.android.com/studio/command-line/d8)
- [R8: R8 is a version of D8 that also performs optimization.](https://jakewharton.com/r8-optimization-staticization/)
________________________________________________________________________________________________________________________________________
# Learning Android Development
- [CodePath Android Cliffnotes(Learning Map)](https://guides.codepath.com/android)
- [Discussions:Three upcoming AMAs with the Android team!](https://www.reddit.com/r/androiddev/comments/hf6l0h/announcement_three_upcoming_amas_with_the_android/)
- [Learning Android Development in 2018 — Part 1](https://android.jlelse.eu/learning-android-development-in-2018-part-1-83a514f6a205)
________________________________________________________________________________________________________________________________________
# Building Blocks

## Activity
- [A Better Way to Launch Activities on Android](https://medium.com/capital-one-developers/a-better-way-to-launch-activities-on-android-8a1045181b16)
- [Activity's four startup modes - illustrated](http://www.apkbj.com/news/show-2305.html)
- [The Android Lifecycle cheat sheet — part IV :](https://medium.com/androiddevelopers/the-android-lifecycle-cheat-sheet-part-iv-49946659b094?linkId=62539868)

## Fragment
### Introduction
- [Fragments](https://developer.android.com/guide/components/fragments)
- [1.1: Fragments](https://google-developer-training.github.io/android-developer-advanced-course-concepts/unit-1-expand-the-user-experience/lesson-1-fragments/1-1-c-fragments/1-1-c-fragments.html)
- [Creating and Using Fragments](https://guides.codepath.com/android/creating-and-using-fragments)
- [Building dynamic user interfaces](http://www.vogella.com/tutorials/AndroidFragments/article.html)
- [Best practice for instantiating a new Android Fragment](https://stackoverflow.com/questions/9245408/best-practice-for-instantiating-a-new-android-fragment)
- [Using newInstance() to Instantiate a Fragment](https://www.androiddesignpatterns.com/2012/05/using-newinstance-to-instantiate.html)
- [Using Fragments to Simplify the Android Navigation Drawer](https://stablekernel.com/using-fragments-to-simplify-android-navigation-drawers/)

### Testing
- [FragmentScenario Component: An easy way to test our fragments in isolation.](https://medium.com/google-developer-experts/exploring-the-android-fragment-scenario-component-e369ec587419)

### Problem of Fragments
- [Advocating Against Android Fragments](https://medium.com/square-corner-blog/advocating-against-android-fragments-81fd0b462c97)
- [The Dark side of Fragments](https://android.jlelse.eu/the-dark-side-of-fragments-ca0f871b1199)

## Notification
- [Android Notification Styling](https://www.journaldev.com/15468/android-notification-styling)
________________________________________________________________________________________________________________________________________

# UI
## Views_OR_Widgets

### TextView
- [Underspanding spans](https://medium.com/google-developers/underspanding-spans-1b91008b97e4)
- [Spantastic text styling with Spans](https://medium.com/google-developers/spantastic-text-styling-with-spans-17b0c16b4568)
- [Android-Text-Sample](https://github.com/googlesamples/android-text)

### EditText
- [Easy EditText content validation with Kotlin](https://proandroiddev.com/easy-edittext-content-validation-with-kotlin-316d835d25b3)
- [Optimize your app for autofill](https://developer.android.com/guide/topics/text/autofill-optimize)

### ImageView
- [Android ImageView ScaleType: A Visual Guide](https://robots.thoughtbot.com/android-imageview-scaletype-a-visual-guide)

### CustomView
- [Make your custom view 60fps in Android](https://medium.com/rosberryapps/make-your-custom-view-60fps-in-android-4587bbffa557)

### RecyclerView
- [Add selection support to RecyclerView Selection](http://androidkt.com/recyclerview-selection-28-0-0/)
- [How to Add Multiple Selection to Android RecyclerView](https://code.tutsplus.com/tutorials/how-to-add-selection-support-to-a-recyclerview--cms-32175)
- [Inside RecyclerView’s SnapHelper](https://proandroiddev.com/android-recyclerview-snaphelper-19eaa9598da6)
- [RecyclerView — More Animations with Less Code using Support Library ListAdapter](https://medium.com/@trionkidnapper/recyclerview-more-animations-with-less-code-using-support-library-listadapter-62e65126acdb)
- [DiffUtil](https://developer.android.com/reference/android/support/v7/util/DiffUtil)

## Layouts
- [Android Tools Attributes — Hidden Gems of Android Studio](https://android.jlelse.eu/tools-attributes-hidden-gems-of-android-studio-d7451b194e0b)
- [Android Studio Layout Editor for Beginners](https://www.codebrainer.com/blogs/android_studio_layout_editor_for_beginners?utm_source=Social&utm_medium=Blog_post&utm_campaign=Layout%20editor)
- [Layouts, Attributes, and you](https://www.youtube.com/watch?annotation_id=annotation_4174682615&feature=iv&index=6&list=PLWz5rJ2EKKc-lJo_RGGXL2Psr8vVCTWjM&src_vid=eOV2owswDkE&v=akP6n9VWHSI)
- [Tuning your apps and games for long screen devices](https://android-developers.googleblog.com/2017/12/tuning-your-apps-and-games-for-long.html)

### ConstraintLayout
- [GUIDELINES, BARRIERS, CHAINS AND GROUPS](https://riggaroo.co.za/constraintlayout-guidelines-barriers-chains-groups/)
- [Build awesome animations with 7 lines of code using ConstraintLayout](https://android.jlelse.eu/build-awesome-animations-with-7-lines-of-code-using-constraintlayout-854e8fd3ad93)
- [The making of AccordionView using ConstraintLayout](https://proandroiddev.com/the-making-of-accordionview-using-constraintlayout-c86992ffbb7b)
- [ConstraintLayout in the LIMELIGHT](https://android.jlelse.eu/constraintlayout-in-the-limelight-6c22b54d9726)

## DataBinding
- [Data Binding Doc](https://developer.android.com/topic/libraries/data-binding)
- [George Mount](https://medium.com/@georgemount007)
- [Android working with DataBinding](https://www.androidhive.info/android-working-with-databinding/)
- [Android DataBinding in RecyclerView – Profile Screen](https://www.androidhive.info/android-databinding-in-recyclerview-profile-screen/)
- [Top 5 Reasons to Use Android Data Binding](https://www.captechconsulting.com/blogs/top-5-reason-to-use-android-data-binding)
### Binding Adapter
- [Android Data Binding: Custom Setters](https://medium.com/androiddevelopers/android-data-binding-custom-setters-55a25a7aea47)
- [Android BindingAdapter order of execution?](https://stackoverflow.com/questions/40932933/android-bindingadapter-order-of-execution)
- [Custom attributes using BindingAdapters in Kotlin](https://proandroiddev.com/custom-attributes-using-bindingadapters-in-kotlin-971ef8fcc259)

### Abstract Adapter
- [Android Data Binding + ListAdapter](https://proandroiddev.com/android-data-binding-listadapter-9e72ce50e8c7)
- [Service Locator pattern in Android](https://medium.com/inloop/service-locator-pattern-in-android-af3830924c69)
### DataBinding Samples
- [Android-Databinding-Sample](https://github.com/googlesamples/android-databinding)
- [Todo-mvvm-Databinding](https://github.com/googlesamples/android-architecture/tree/todo-mvvm-databinding)
- [Android-Sunflower](https://github.com/googlesamples/android-sunflower)
### DataBinding Cons
- [An Argument Against Data Binding](https://medium.com/@hellotimmutton/an-argument-against-data-binding-13e2aaf7a9b1)

## Fonts
- [Downloadable Fonts: How does it work?](https://android.jlelse.eu/downloadable-fonts-how-does-it-work-904b9d03e5b6)
## Emoji
- [Exploring the Android EmojiCompat Library](https://medium.com/exploring-android/exploring-the-android-emoji-compatibility-library-1b9f3bb724aa)
________________________________________________________________________________________________________________________________________
# Animations
## MotionLayout
- [Complex UI/Animations on Android](https://proandroiddev.com/complex-ui-animations-on-android-featuring-motionlayout-aa82d83b8660)
________________________________________________________________________________________________________________________________________
# ViewPager 1
- [Android How to Build Intro Slider for your App](https://www.androidhive.info/2016/05/android-build-intro-slider-app/)

# ViewPager 2
- [Why ViewPager2?](https://medium.com/google-developer-experts/exploring-the-view-pager-2-86dbce06ff71)
- [Why ViewPager2?](https://proandroiddev.com/look-deep-into-viewpager2-13eb8e06e419)
- [ViewPager2 Offical](https://developer.android.com/jetpack/androidx/releases/viewpager2)
- [ViewPager2 Example 1](https://www.androidhive.info/2020/01/viewpager2-pager-transformations-intro-slider-pager-animations-pager-transformations/)
- [ViewPager2 Example 2](https://developer.android.com/training/animation/screen-slide-2)
- [ViewPager2 Example 3: Dots library](https://ahsensaeed.com/android-viewpager2-example-tutorial/)
- [ViewPager2 Tabs Example 1](https://androidwave.com/viewpager2-with-fragments-android-example/)
- [ViewPager2 Tabs Example 2](https://blog.stylingandroid.com/viewpager2/)



# Data_Persistence

## SharedPreferences
- [Prefekt](https://blog.stylingandroid.com/prefekt-introduction/)

## Database
- [Android password protect sqlite](https://stackoverflow.com/questions/29125417/android-password-protect-sqlite)
- [What are the best practices for SQLite on Android?](https://stackoverflow.com/questions/2493331/what-are-the-best-practices-for-sqlite-on-android?rq=1)
- [Improve INSERT-per-second performance of SQLite](https://stackoverflow.com/questions/1711631/improve-insert-per-second-performance-of-sqlite?rq=1)
- [A Survey of Object-Relational Mapping (ORM) Libraries for Android and iOS](https://dzone.com/articles/a-survey-of-object-relational-mapping-orm-librarie)
- [Android-ORM-benchmark](https://github.com/AlexeyZatsepin/Android-ORM-benchmark)
### SQLCipher
- [Bulletproof Android: Practical Advice for Building Secure Apps](https://www.informit.com/articles/article.aspx?p=2268753&seqNum=3)
- [Encrypting database with Room createFromAsset() method](https://discuss.zetetic.net/t/encrypting-database-with-room-createfromasset-method/4458)
- [How to apply SQLCipher to pre-existing Room database?](https://discuss.zetetic.net/t/how-to-apply-sqlcipher-to-pre-existing-room-database/4320)
- [SQLCipher with Room Persistence Library exception in SQLCipherUtils.getDatabaseState](https://stackoverflow.com/questions/53452700/sqlcipher-with-room-persistence-library-exception-in-sqlcipherutils-getdatabases)

## File

## Firebase
________________________________________________________________________________________________________________________________________

# MultiMedia
- [Audio & Video](https://developer.android.com/guide/topics/media)

## Audio_Focus
- [Managing audio focus: Offical](https://developer.android.com/guide/topics/media-apps/audio-focus)
- [Respecting Audio Focus: Offical](https://android-developers.googleblog.com/2013/08/respecting-audio-focus.html)
- [Understanding Audio Focus (Part 1 / 3: Offical](https://medium.com/androiddevelopers/audio-focus-1-6b32689e4380)
- [How to _properly_ handle audio interruptions: Offical](https://medium.com/google-developers/how-to-properly-handle-audio-interruptions-3a13540d18fa)
- [OLD: Managing Audio Focus: OFFICAL](https://stuff.mit.edu/afs/sipb/project/android/docs/training/managing-audio/audio-focus.html)
- [Handling Audio Focus In Android](http://markojerkic.com/handling-audio-focus-in-android/)

## Audio
- [Introducing Oboe: A C++ library for low latency audio](https://android-developers.googleblog.com/2018/10/introducing-oboe-c-library-for-low.html?linkId=58065430)

## ExoPlayer
- [ExoPlayer 2.9.0 — What’s new](https://medium.com/google-exoplayer/exoplayer-2-9-0-whats-new-5aa39a3aadce?linkId=57692866)

## Camera
- [Using multiple camera streams simultaneously](https://medium.com/androiddevelopers/using-multiple-camera-streams-simultaneously-bf9488a29482?linkId=58066789)
- [Understanding Android camera capture sessions and requests](https://medium.com/androiddevelopers/understanding-android-camera-capture-sessions-and-requests-4e54d9150295)
________________________________________________________________________________________________________________________________________

# Animation
- [Animate all the things. Transitions in Android](https://medium.com/@andkulikov/animate-all-the-things-transitions-in-android-914af5477d50)
- [Transitions-Everywhere: Set of extra Transitions on top of Jetpack Transitions Library](https://github.com/andkulikov/Transitions-Everywhere)
- [Move content to side in Drawer Layout Android](http://thetechnocafe.com/slide-content-to-side-in-drawer-layout-android/)
- [Polishing UI: Android StateListAnimator](https://android.jlelse.eu/polishing-ui-android-statelistanimator-7b74a06b85a5)
- [Implement Google Inbox Style Animation on Android](https://proandroiddev.com/implement-google-inbox-style-animation-on-android-18c261baeda6)
- [StateListAnimator — a Powerful Little Tool for Elevation Animation](https://proandroiddev.com/statelistanimator-a-powerful-little-tool-for-elevation-animation-4b31781e98a0)
- [TransitionDrawable — Small Gems of the Android Framework](https://proandroiddev.com/transitiondrawable-small-gems-of-the-android-framework-4dcdd3c83319)
________________________________________________________________________________________________________________________________________
# MultiThreading

## Loaders
- [It’s time to ditch Loaders in Android](https://medium.com/inloop/its-time-to-ditch-loaders-in-android-6492616775f7)

## Background
- [Modern background execution in Android](https://android-developers.googleblog.com/2018/10/modern-background-execution-in-android.html?linkId=58286424)
- [Android background in a nutshell. Part 4 — RxJava](https://proandroiddev.com/android-background-in-a-nutshell-part-4-rxjava-a41c16985d71)
- [Exploring Background Execution Limits on Android Oreo](https://medium.com/exploring-android/exploring-background-execution-limits-on-android-oreo-ab384762a66c)

## RxJava
- [RxAndroid’s New Async API](https://medium.com/@ZacSweers/rxandroids-new-async-api-4ab5b3ad3e93)
- [I bet your RxJava is on the wrong thread](https://lorentzos.com/i-bet-your-rxjava-is-on-the-wrong-thread-ae02e66a3eac)
- [How we migrated from RxJava1 to RxJava2](https://medium.com/lifesum-healthy-living-simplified/how-we-migrated-from-rxjava1-to-rxjava2-bcf0c9eb1a6f)
- [RxJava - Flowables - What, when and how to use it?](http://www.aanandshekharroy.com/articles/2018-01/rxjava-flowables)
- [RxJava — Schedulers — What, when and how to use it?](https://android.jlelse.eu/rxjava-schedulers-what-when-and-how-to-use-it-6cfc27293add)
- [rxlint](https://bitbucket.org/littlerobots/rxlint/src/default/README.md?fileviewer=file-view-default)
- [Article](https://www.littlerobots.nl/blog/rxlint-1.7.0/)
- [Rx Chain Retrier](https://proandroiddev.com/rx-chain-retrier-45013616efcb)
________________________________________________________________________________________________________________________________________
# Fetching_Data_Online

## Retrofit
- [Retrofit meets coroutines](https://zsmb.co/retrofit-meets-coroutines/)
- [How to use Retrofit on android with Kotlin (KAD 21)](https://antonioleiva.com/retrofit-android-kotlin)
- [Concise Error Handling with LiveData and Retrofit](https://proandroiddev.com/concise-error-handling-with-livedata-and-retrofit-15937ceb555b)

## Gson
- [Most elegant way of using Gson + Kotlin with default values and null safety](https://medium.com/@MaxMello/most-elegant-way-of-using-gson-kotlin-with-default-values-and-null-safety-b6216ac5328c)

## Firebase_Firestore
- [Understanding Cloud Firestore Security Rules](https://www.ericdecanini.com/2018/02/03/understanding-cloud-firestore-security-rules/)
________________________________________________________________________________________________________________________________________


# Design & UX
- [Applying human-centered design to emerging technologies](https://medium.com/googleplaydev/applying-human-centered-design-to-emerging-technologies-6ad7f39d8d30)
- [Design your app for decision-making](https://medium.com/googleplaydev/design-your-app-for-decision-making-e9e5745508e4)
- [The right app rewards to boost motivation](https://medium.com/googleplaydev/the-right-app-rewards-to-boost-motivation-c1ec86390450)
- [The promise of persuasive apps](https://medium.com/googleplaydev/the-promise-of-persuasive-apps-98b428ee18ef)
- [Taking the guesswork out of paid user acquisition](https://medium.com/googleplaydev/taking-the-guesswork-out-of-paid-user-acquisition-720d9d74882e)
## From Design to Android
- [From design to android, part 1](http://saulmm.github.io/from-design-to-android-part1)
- [From design to android, part 2](https://medium.com/@saulmm2/from-design-to-android-part-2-2a6c141547d9)


# Productivity
- [Super charging your app development](https://android.jlelse.eu/supercharging-your-app-development-speed-with-custom-file-templates-3e6acb6db6c3)
- [Top 12 Things That Destroy Developer Productivity](https://hackernoon.com/top-12-things-that-destroy-developer-productivity-2ddf0abc190)

## Shortcuts
- [Pro Android Studio - Code navigation](https://jeroenmols.com/blog/2018/02/22/androidstudioshortcuts/)
- [android-tips-tricks](https://github.com/nisrulz/android-tips-tricks)

## GIT
- [Pretty Handy](https://twitter.com/JakeWharton/status/982253714315460608)
- [Ooga-chaka: Git hooks to enforce code quality](https://proandroiddev.com/ooga-chaka-git-hooks-to-enforce-code-quality-11ce8d0d23cb)

## Utilities
- [Including Open Source Notices](https://developers.google.com/android/guides/opensource)
- [Time for non-Time Lords](https://blog.stylingandroid.com/category/time/)
- [ThreeTen Android Backport](https://github.com/JakeWharton/ThreeTenABP)
- [LogUtil often used in Android development](http://www.apkbj.com/news/show-2306.html)

### Utils_RxJava
- [RxRelay: RxJava types that are both an Observable and a Consumer.](https://github.com/JakeWharton/RxRelay)
- [RxReplayingShare: An RxJava 2 transformer which combines replay(1), publish(), and refCount() operators.](https://github.com/JakeWharton/RxReplayingShare)
- [RxIdler: An IdlingResource for Espresso which wraps an RxJava](https://github.com/square/RxIdler)

## Gradle
- [Add build dependencies](https://developer.android.com/studio/build/dependencies)
- [Android 101: Gradle dependencies](https://android.jlelse.eu/android-101-gradle-dependencies-9e2742b59f9)
- [How I reduced my Android build times by 89%](https://android.jlelse.eu/how-i-reduced-my-android-build-times-by-89-4242e51ce946)
- [Making incremental KAPT work (Speed Up your Kotlin projects!)](https://medium.com/@daniel_novak/making-incremental-kapt-work-speed-up-your-kotlin-projects-539db1a771cf)
- [Using Gradle build cache with Kotlin](https://blog.jetbrains.com/kotlin/2018/02/using-gradle-build-cache-with-kotlin/)

# Settings
- [Android Preference settings preferences Raiders](http://www.apkbj.com/news/show-19952.html)


# Android Architecture components
- [Android Architecture: Part 1 – Every New Beginning is Hard](http://five.agency/android-architecture-part-1-every-new-beginning-is-hard/)
- [Detecting when an Android app backgrounds in 2018](https://proandroiddev.com/detecting-when-an-android-app-backgrounds-in-2018-4b5a94977d5c)
- [Hacking Architecture Components by using Kotlin](https://antonioleiva.com/architecture-components-kotlin/)
- [Android Architecture components walk-through](https://www.linkedin.com/pulse/android-architecture-components-walk-through-mohamed-ibrahim/)
- [Is your Android Library, Lifecycle-Aware?](https://android.jlelse.eu/is-your-android-library-lifecycle-aware-127629d32dcc)
- [Modeling ViewModel States Using Kotlin’s Sealed Classes](https://engineering.udacity.com/modeling-viewmodel-states-using-kotlins-sealed-classes-a5d415ed87a7)
- [Types as tests: How to fail the build when there’s a logical error](https://proandroiddev.com/types-as-tests-how-to-fail-the-build-when-theres-a-logical-error-e7000e2f62b8)

# Clean Code
- [Understanding Clean Code in Android](https://medium.com/mindorks/understanding-clean-code-in-android-ebe42ad89a99)
- [Code Clean-up with Kotlin](https://proandroiddev.com/code-clean-up-with-kotlin-19ee1c8c0719)
- [Improve Code Inspection with Annotations](https://developer.android.com/studio/write/annotations.html#adding-nullness)
- [Simple but painful steps for writing a better code](https://medium.com/car2godevs/simple-but-painful-steps-for-writing-a-better-code-afb2651cef86)
- [Separated presentation](https://medium.com/android-testing-daily/separated-presentation-9a2982bd5553)
- [Android Architecture: Part 1 – Every New Beginning is Hard](https://proandroiddev.com/the-state-of-jetification-in-early-2019-plus-a-bonus-gradle-plugin-aac5854af910)
- [Clean architecture on Android](https://proandroiddev.com/clean-architecture-on-android-using-feature-modules-mvvm-view-slices-and-kotlin-e9ed18e64d83)
- [Where to Unbind the Presenter](https://proandroiddev.com/where-to-unbind-the-presenter-e50ce343d4ce)
- [Repository layer using Room and Dagger 2 — Android](https://medium.com/@saurabh30pant/repository-layer-using-room-and-dagger-2-android-12d311830fd9)

# Before_Launching_your_App
- [Automated Mobile Localization Process](https://proandroiddev.com/automated-mobile-localization-process-5e05b721bf69)
- [Basic Android Encryption Do’s and Don’ts](https://medium.com/@tiensinodev/basic-android-encryption-dos-and-don-ts-7bc2cd3335ff)

## Debugging
- [Debugging in Android Studio](https://medium.com/androiddevelopers/debugging-in-android-studio-dfbbf8a8d03c)
- [How to Display Dependency Tree of Your Android Project with Gradle?](https://wajahatkarim.com/2020/03/gradle-dependency-tree/)
- [Finding inter-procedural bugs at scale with Infer static analyzer](https://code.facebook.com/posts/1537144479682247/finding-inter-procedural-bugs-at-scale-with-infer-static-analyzer/)
- [Hide your crashes gracefully (and still report them)](https://proandroiddev.com/hide-your-crashes-gracefully-and-still-report-them-9b1c85b25875)
- [Making the most out of Android Studio Debugger](https://proandroiddev.com/making-the-most-out-of-the-android-studio-debugger-61713131d065)

### Emulator
- [Frameless emulator window](https://developer.android.com/studio/releases/emulator.html)
- [Quick Boot & the Top Features in the Android Emulator](https://android-developers.googleblog.com/2017/12/quick-boot-top-features-in-android.html)

### Android Profiler
- [Quick Tip: Network Profiler in Android Studio 3.1](https://android.jlelse.eu/quick-tip-network-profiler-in-android-studio-3-1-491e530ac8f2)

### GAPID
- [Diagnose and understand your app's GPU behavior with GAPID](https://android-developers.googleblog.com/2017/12/diagnose-and-understand-your-apps-gpu_13.html)

## Optimize your Android apps size
- [Patchwork Plaid — A modularization story](https://medium.com/androiddevelopers/a-patchwork-plaid-monolith-to-modularized-app-60235d9f212e?linkId=58394902)
- [Shrinking APKs, growing installs](https://medium.com/googleplaydev/shrinking-apks-growing-installs-5d3fcba23ce2)

## Battery
- [Moar Power in Android 9 Pie and the future](https://android-developers.googleblog.com/2018/09/moar-power-in-android-9-pie-and-future.html?linkId=56731552)

## ProGuard 
- [Troubleshooting ProGuard issues on Android](https://medium.com/google-developers/troubleshooting-proguard-issues-on-android-bce9de4f8a74)

# Tools
- [Bugsnag:Bugsnag monitors application stability, so you can make data-driven decisions on whether you should be building new features, or fixing bugs.](https://www.bugsnag.com/)
- [Stetho:A debug bridge for Android applications.With Setho we can use chrome Developer Tools feature natively part of the Chrome desktop browser](http://facebook.github.io/stetho/)

# Testing
- [Mastering the World of Android Testing (Part 2)](https://blog.aritraroy.in/mastering-the-world-of-android-testing-part-2-23293c34dbbf)
- [The Ultimate Guide to Mobile Application Testing Strategy](http://axblog.sigos.com/ultimate-guide-mobile-application-testing-strategy?utm_source=linkedin&utm_medium=social&utm_campaign=blog20171207&utm_content=post&utm_term=dap)
- [Testing Android UI with Pleasure](https://proandroiddev.com/testing-android-ui-with-pleasure-e7d795308821)
- [Testing common modules](https://blog.kotlin-academy.com/testing-common-modules-66b39d641617)
- [Register: Better In App Billing Testing on Android](https://open.nytimes.com/register-better-in-app-billing-testing-on-android-73af5fcc36dc)
- [JUnit 5 User Guide](http://junit.org/junit5/docs/current/user-guide/#release-notes-5.0.0)
- [An IdlingResource for Espresso which wraps an RxJava Scheduler](https://github.com/square/RxIdler)
- [Testability](https://blog.stylingandroid.com/category/kotlin/)
- [An introduction to in-app A/B testing](https://medium.com/googleplaydev/an-introduction-to-in-app-a-b-testing-c5a9a69a3791)
- [Use pre-launch and crash reports to improve your app](https://developer.android.com/distribute/best-practices/launch/pre-launch-crash-reports.html)
- [Beta test your app with users to get invaluable early feedback](https://developer.android.com/distribute/best-practices/launch/beta-tests.html)
- [Faster Renewals for Test Subscriptions](https://android-developers.googleblog.com/2018/01/faster-renewals-for-test-subscriptions.html)
- [Testing in-app purchases on Android](https://medium.com/bleeding-edge/testing-in-app-purchases-on-android-a6de74f78878)

## [Dagger 2](https://github.com/google/dagger)
- [Dependency injection in a multi module project](https://medium.com/androiddevelopers/dependency-injection-in-a-multi-module-project-1a09511c14b7)
- [Dagger 2 on Android: The Simple Way](https://proandroiddev.com/dagger-2-on-android-the-simple-way-f706a2c597e9)
- [Dagger 2 on Android: The Official Guidelines You Should Be Following](https://proandroiddev.com/dagger-2-on-android-the-official-guidelines-you-should-be-following-2607fd6c002e)
- [Moving from Dagger to Koin — Simplify your Android development](https://android.jlelse.eu/moving-from-dagger-to-koin-simplify-your-android-development-e8c61d80cddb)
- [How to use Dagger 2 on Android with Kotlin (KAD 20)](https://antonioleiva.com/dagger-android-kotlin)
- [Dagger - What's the one thing you struggle with the most when using it?](https://www.reddit.com/r/androiddev/comments/at6ad0/dagger_whats_the_one_thing_you_struggle_with_the/)

### Dagger_Videos
- [Helping Dagger Help You](https://jakewharton.com/helping-dagger-help-you/)

## Unit Testing
- [Unit tests on Android with Kotlin](https://antonioleiva.com/unit-tests-android-kotlin)

# Google Play
- [Academy for App Success](https://playacademy.exceedlms.com/student/catalog)
- [Latest apps sories](https://developer.android.com/stories/apps/)
- [Improving app security and performance on Google Play for years to come](https://android-developers.googleblog.com/2017/12/improving-app-security-and-performance.html)
- [Apply for early access to pre-registration](https://support.google.com/googleplay/android-developer/answer/9098022)
- [Implementing linkedPurchaseToken correctly to prevent duplicate subscriptions](https://medium.com/androiddevelopers/implementing-linkedpurchasetoken-correctly-to-prevent-duplicate-subscriptions-82dfbf7167da)
- [A guide to the Google Play Console](https://medium.com/googleplaydev/a-guide-to-the-google-play-console-1bdc79ca956f)
- [Updates and Other Resources](https://play.google.com/about/updates-resources/)
- [Use pre-launch reports to identify issues](https://support.google.com/googleplay/android-developer/answer/7002270#demo_loop)
- [How we fought bad apps and malicious developers in 2017](https://android-developers.googleblog.com/2018/01/how-we-fought-bad-apps-and-malicious.html)
- [Staged releases are now supported in your testing, as well as in production tracks](https://twitter.com/GooglePlayDev/status/1037389370116980736)

### Legal issues
- [Google just terminated our start-up Google Play Publisher Account on Christmas day](https://android.jlelse.eu/google-just-terminated-our-start-up-google-play-publisher-account-on-christmas-day-5cb69a454da0)

### Build Excellent Apps
- [Generate positive social impact through your apps](https://twitter.com/GooglePlayDev/status/1042819669940494336)
- [Discover how GooglePlay developers grew their subscription business](https://twitter.com/GooglePlayDev/status/1037756440423870464)
- [How do you successfully engage and retain your app users in the long term?](https://twitter.com/GooglePlayDev/status/1045353482675507202)

### Monetization 
- [Predicting your app’s monetization future](https://medium.com/googleplaydev/predicting-your-apps-monetization-future-27180e82ae34)
- [From app explorer to first-time buyer](https://medium.com/googleplaydev/from-app-explorer-to-first-time-buyer-6476be50893)

### Outsoucrcing app
- [Part 1](https://twitter.com/GooglePlayDev/status/1039554766609760256)
- [Part 2](https://twitter.com/GooglePlayDev/status/1042086293923135490)
- [Part 3](https://twitter.com/GooglePlayDev/status/1046817021151924225)

# App Building Process
- [Test and publish your apps with CircleCI + Fastlane + Firebase Test Lab](https://proandroiddev.com/test-and-publish-your-apps-with-circleci-fastlane-firebase-test-lab-e716c075b99b)

# Complete Tutorials
- [Build Your First Android App: A Time Zone Converter](https://dragosholban.com/2018/02/24/build-your-first-android-app-a-time-zone-converter)
- [Building a video player app in Android (Part 5 / 5)](https://medium.com/google-developers/building-a-video-player-app-in-android-part-5-5-725c1ec2557a)
- [YoutubeUX](https://github.com/burhanrashid52/YoutubeUX)

# Open Source apps

## From Google or there developers
- [The Google I/O 2018 Android App](https://github.com/google/iosched)
- [Muzei Live Wallpaper for Android ](https://github.com/romannurik/muzei)
- [android-UniversalMusicPlayer](https://github.com/googlesamples/android-UniversalMusicPlayer)
- [Plaid](https://github.com/nickbutcher/plaid)
- [Android Sunflower (alpha)](https://github.com/googlesamples/android-sunflower)
- [santa-tracker-android](https://github.com/google/santa-tracker-android)
- [todo-mvvm-live](https://github.com/googlesamples/android-architecture/tree/todo-mvvm-live)
- [android-architecture](https://github.com/googlesamples/android-architecture)
- [SdkSearch](https://github.com/JakeWharton/SdkSearch)
- [tivi](https://github.com/chrisbanes/tivi)
- [JakeWharton/u2020: A sample Android app which showcases advanced usage of Dagger among other open source libraries.](https://github.com/JakeWharton/u2020)
- [Sunshine-Version-2](https://github.com/udacity/Sunshine-Version-2)
- []()


## Other
- [Quran for Android](https://github.com/quran/quran_android)
- [Simple Mobile: Multiple Apps](https://www.simplemobiletools.com/)
- [Twidere-Android](https://github.com/TwidereProject/Twidere-Android)
- [kotlinconf-app](https://github.com/JetBrains/kotlinconf-app)
- [Materialistic: A material-design Hacker News Android reader ](https://github.com/hidroh/materialistic)
- [Easy-library: I completely changed my original Dagger setup, I added Data Binding](https://github.com/tfcporciuncula/easy-library)
- [Blue-Podcast: Used some good libraries](https://github.com/vidbregar/Blue-Podcast)
- [Baking-App: Used some good libraries](https://github.com/vidbregar/Baking-App)
- [Dagger-Kotlin-20line](https://github.com/mohamedebrahim96/Dagger-Kotlin-20line)
- [The ownCloud Android App](https://github.com/owncloud/android)
- [Nextcloud Android app](https://github.com/nextcloud/android)
- [Bandhook-Kotlin](https://github.com/antoniolg/Bandhook-Kotlin)
- [PaperPlane](https://github.com/TonnyL/PaperPlane)
- [LookLook](https://github.com/xinghongfei/LookLook)
- [android-movies-app](https://github.com/vpaliy/android-movies-app)
- [bodyweight-fitness-android](https://github.com/mazurio/bodyweight-fitness-android)


## TODO List
- [Minimal-Todo](https://github.com/avjinder/Minimal-Todo)
- [MVVM-To-Do-App](https://github.com/Naveentp/MVVM-To-Do-App)
- [android-minimal-todo](https://github.com/cuongpm/android-minimal-todo)
- [WanAndroid](https://github.com/iceCola7/WanAndroid)
- [Firebucket](https://github.com/remychantenay/Firebucket)

## Material Design
- [kickmaterial](https://github.com/byoutline/kickmaterial)
- [Material Design Music Player](https://github.com/naman14/Timber)
- [kotlin-life](https://github.com/Cuieney/kotlin-life)
- [Douya](https://github.com/DreaminginCodeZH/Douya)
- [MagicPrint-ECommerce-App-Android](https://github.com/singhkshitij/MagicPrint-ECommerce-App-Android)
- [LeafPic](https://github.com/HoraApps/LeafPic)
- [ECommerce-App-Android](https://github.com/hiteshsahu/ECommerce-App-Android)
- [talon-for-twitter-android](https://github.com/klinker24/talon-for-twitter-android)
- [What2Do](https://github.com/Aayushjn/What2Do)
- [TravelWithList](https://github.com/gshockv/TravelWithList)
- [Minimal_ToDo](https://github.com/rob729/Minimal_ToDo)
- [CaptainChef](https://github.com/bapspatil/CaptainChef)
- [Moviemade](https://github.com/michaelbel/Moviemade)
- [BottomAppBarImplementation](https://github.com/ranger163/BottomAppBarImplementation)
- [Material-Componets-Catalog](https://github.com/nikhilbansal97/Material-Componets-Catalog)

# Testing
- [Memento2](https://github.com/mdnaseemashraf/Memento2)
- [UITesting](https://github.com/JSBerrocoso/UITesting)

# Material Design + MVP + RxJava
- [Ghost](https://github.com/GeekGhost/Ghost)
- [AndroidFire](https://github.com/jaydenxiao2016/AndroidFire)
- [GitNav: GitHub Android App](https://github.com/GLodi/GitNav)
- [android-mvp-architecture](https://github.com/MindorksOpenSource/android-mvp-architecture)
- [MovieGuide](https://github.com/esoxjem/MovieGuide)
- [MvpApp](https://github.com/Rukey7/MvpApp)
- [android-kotlin-mvp-architecture](https://github.com/MindorksOpenSource/android-kotlin-mvp-architecture)
- [An Android app for dribbble.com](https://github.com/TonnyL/Mango)

# High Profile Apps
- [Lawnchair](https://github.com/LawnchairLauncher/Lawnchair)
- [uhabits](https://github.com/iSoron/uhabits)
- [conference-app-2018](https://github.com/DroidKaigi/conference-app-2018)
- [open-event-android](https://github.com/fossasia/open-event-android)
- [duckduckgo/Android](https://github.com/duckduckgo/Android)

# MVVM + Architecture Components
- [YoutubeUX](https://github.com/burhanrashid52/YoutubeUX)
- [android-architecture-counter-sample](https://github.com/dlew/android-architecture-counter-sample)
- [countries](https://github.com/patloew/countries)
- [crweather](https://github.com/elpassion/crweather)
- [android-arch-news-sample](https://github.com/AkshayChordiya/android-arch-news-sample)
- [Android-Architecture-Components](https://github.com/KucherenkoIhor/Android-Architecture-Components)
- [kotlin-architecture-components](https://github.com/satorufujiwara/kotlin-architecture-components)





# Contribute
- [Bug Reports: A Story](https://zdominguez.com/2019/02/20/bug-reports.html)

# Android Jobs
- [Discover New Android Opportunities](https://www.androidjobs.io/)
- [How I negotiated a $300,000 job offer in Silicon Valley](https://blog.usejournal.com/how-i-negotiated-a-software-engineer-offer-in-silicon-valley-f11590f5c656)

## Interview
- [Cheat Sheet for Android Interviews](https://github.com/anitaa1990/Android-Cheat-sheet)

# Runtime Permissions
- [Request App Permissions](https://developer.android.com/training/permissions/requesting)
- [Request permissions at runtime appropriately](https://developer.android.com/distribute/best-practices/develop/runtime-permissions)
- [EasyPermissions](https://github.com/googlesamples/easypermissions)

