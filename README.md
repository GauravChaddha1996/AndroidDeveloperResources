# Android Developer Resources
Resources about Android Development

# Table of Content

### Structure
* [Android app architecture](#android-app-architecture)
* [MVP resources](#mvp-resources)

### Development patterns, practises and security
* [Java 8](#java-8)
* [Data Binding](#data-binding)
* [Dependency Injection](#dependency-injection)
* [Good Practises](#good-practises)
* [Android Security](#android-security)

### Networking
* [Retrofit](#retrofit)
* [Networking](#networking-2)

### RxJava and Kotlin
* [RxJava](#rxjava)
* [Kotlin](#kotlin)

### Views, Layouts, Animations and Custom views
* [Animation and Vector Drawable's stuff](#animation-and-vector-drawables-stuff)
* [Recycler View](#recycler-view)
* [Making Custom Library and Views](#making-custom-library-and-views)

### Application helper tasks
* [Login and Account Authentication](#login-and-account-authentication)
* [Settings and Preferences](#settings-and-preferences)
* [Scheduling Jobs and alarms](#scheduling-jobs-and-alarms)
* [Audio in android](#audio-in-android)

### App analytics
* [App analytics](#app-analytics)

### Testing - Unit and prodcution tests
* [Testing](#testing)
* [App production testing](#app-production-testing)

### Git Resources
* [Git Resources](#git-resources)

### Open Source and stuff
* [Open Source and stuff](#open-source-and-stuff)

### Libraries
* [Utility and design libraries](#utility-and-design-libraries)

### Proguard
* [Proguard](#proguard)
* [Tools for reversing apk for educational purposes](#tools-for-reversing-apk-for-educational-purposes)

### Miscellaneous
* [Miscellaneous](#miscellaneous)

# Structure

### Android app architecture
* [Shades of mvvm](https://www.bignerdranch.com/blog/shades-of-mvvm/)
* [RxJava: Android MVVM app structure with retrofit](https://medium.com/@manuelvicnt/rxjava-android-mvvm-app-structure-with-retrofit-a5605fa32c00#.n1dgvzdjo)
* [RxJava 2: Android MVVM Lifecycle App Structure with Retrofit 2](https://medium.com/@manuelvicnt/rxjava2-android-mvvm-lifecycle-app-structure-with-retrofit-2-cf903849f49e#.hb69pqls3)
* [Android application architecture powered by RxJava](https://labs.ribot.co.uk/android-application-architecture-8b6e34acda65#.aif4u3g7r)
* [Restoring state in android mvp architecture](https://pspdfkit.com/blog/2016/restoring-state-in-android-mvp-architecture/)
* [Inloop Pragmatic android application architecture](https://medium.com/inloop/a-pragmatic-android-application-architecture-fecae198ecf8#.9d1bdy89l)
* [Offline App Architecture: how to build for the next billion](https://hackernoon.com/so-you-want-to-develop-for-the-next-billion-9eb072c26bc8#.eoverdgtl)
* [Package by feature, not layers!](https://medium.com/@cesarmcferreira/package-by-features-not-layers-2d076df1964d#.h4yypl78m)

### MVP resources
* [Yet another MVP article — Part 1: Lets get to know the project](https://hackernoon.com/yet-another-mvp-article-part-1-lets-get-to-know-the-project-d3fd553b3e21#.m8tr2xvgw)

# Development patterns, practises and security

## Java 8 
* [Java 8 Streams:10 missing features](https://medium.com/@johnmcclean/java-8-streams-10-missing-features-ec82ee90b6c0#.uonjprdj3)
* [Java 8 Language Features on Android](https://medium.com/@muratcanbur/java-8-language-features-on-android-ee8ea414f9f0#.izr0humg0)
* [Effective Java for Android cheatsheet](https://medium.com/rocknnull/effective-java-for-android-cheatsheet-bf4e3433889a#.zsn2ir0zb)

### Data Binding 
* [Android Data binding by Boyar Mount](https://realm.io/news/data-binding-android-boyar-mount/)

### Dependency Injection
* [For Basic DI understanding](http://ganeshtiwaridotcomdotnp.blogspot.in/2011/05/understanding-dependency-injection-and.html)
* [Snorkeling with Dagger2](https://github.com/konmik/konmik.github.io/wiki/Snorkeling-with-Dagger-2)
* [Fernando Cejas: Tasting Dagger 2 on android](http://fernandocejas.com/2015/04/11/tasting-dagger-2-on-android/)
* [Dagger 2 by Antonio leiva](https://antonioleiva.com/dependency-injection-android-dagger-part-1/)
* [Inject everything Dagger 2 example](http://frogermcs.github.io/inject-everything-viewholder-and-dagger-2-example/)
* [Introduction to Dagger 2, Using Dependency Injection in Android](https://blog.mindorks.com/introduction-to-dagger-2-using-dependency-injection-in-android-part-1-223289c2a01b#.4cae8wf66)
* [Android Dagger2: Critical things to know before you implement.](https://blog.mindorks.com/android-dagger2-critical-things-to-know-before-you-implement-275663aecc3e#.crrgqwnbi)

### Good Practises
* [Making android app faster](https://medium.com/@jorgemf/making-your-android-app-faster-735328eaba25#.86ddkca4d)
* [Android process kill and big implications for your app](https://medium.com/inloop/android-process-kill-and-the-big-implications-for-your-app-1ecbed4921cb#.8kr1hg4jd)
* [Your presenters don’t need all those lifecycle events!](https://medium.com/@anupcowkur/your-presenters-dont-need-all-those-lifecycle-events-721f500eeef4#.bi7q3jbo0)
* [Taming android layout resources](https://medium.com/@cesarmcferreira/taming-android-layout-resources-af249d6db21d#.38ypckpz1)
* [Adventures with FragmentStatePagerAdapter](https://medium.com/inloop/adventures-with-fragmentstatepageradapter-4f56a643f8e0#.r2qtxvlg9)
* [Guide to ConstraintLayout](https://medium.com/@loutry/guide-to-constraintlayout-407cd87bc013#.8wr4zts8q)
* [Futurice - Best practices in Android development](https://github.com/futurice/android-best-practices)
* [Nisrulz android tips and tricks](https://github.com/nisrulz/android-tips-tricks)
* [Successful XML naming convention](http://jeroenmols.com/blog/2016/03/07/resourcenaming/)
* [Things to consider before choosing implementation for worker thread](https://blog.yipl.com.np/things-to-consider-before-running-background-tasks-e71f00d2ad3a#.fe1auoxur)
* [Presenters are not for persisting](https://medium.com/@theMikhail/presenters-are-not-for-persisting-f537a2cc7962#.t7fizf93e)
* [Understanding Android Core: Looper, Handler, and HandlerThread](https://blog.mindorks.com/android-core-looper-handler-and-handlerthread-bd54d69fe91a#.vvz4dudf1)

### Android Security
* [How To Make Your Android Application Secured](https://medium.com/uptech-team/how-to-make-your-android-application-secured-21c054b371e7#.vonbsiw88)
* [Devknox – Autocorrect for Security Issues](https://blog.devknox.io/devknox-autocorrect-for-security-issues/)
* [Hiding Secrets in Android Apps](https://rammic.github.io/2015/07/28/hiding-secrets-in-android-apps/)
* [Dear Android Developer- This is an intervention about your app's security](https://www.reddit.com/r/androiddev/comments/3dedaj/dear_android_developer_this_is_an_intervention/)

# Networking

### Retrofit
* [Basic Retrofit by vogella](http://www.vogella.com/tutorials/Retrofit/article.html)
* [Explore this wiki for more Retrofit stuff](https://github.com/square/retrofit/wiki)

### Networking
* [Networking caching pattern with RxJava](http://www.andevcon.com/news/rxify-the-anti-cache-then-network-or-network-then-cache-problem)
* [OkHttp is quietly retrying requests. Is your API ready?](https://medium.com/inloop/okhttp-is-quietly-retrying-requests-is-your-api-ready-19489ef35ace#.ifu68kx4z)

# RxJava and Kotlin

### RxJava
* [Understanding why you need RxJava and some related terminology](https://medium.com/@Batdroid/understanding-the-enigma-of-rxjava-part-1-8e04a456d9de)
* [Why should I do Functional Reative Programming](https://medium.com/@cesarmcferreira/why-you-should-be-doing-functional-reactive-programming-858bd9bb8001#.y8p1je1o5)
* [Dan Lew's Grokking RxJava Series](http://blog.danlew.net/2014/09/15/grokking-rxjava-part-1/)
* [Crunching RxAndroid Series](https://medium.com/crunching-rxandroid/crunching-rxandroid-part-1-4ac7b7123238#.svvpyf3a2)
* [RxAndroid Basics Series](https://medium.com/@kurtisnusbaum/rxandroid-basics-part-1-c0d5edcf6850#.jy9seoya5)
* [Realm:Intro to Functional Reactive Programming](https://realm.io/news/droidcon-gomez-functional-reactive-programming/)
* [The introduction to Reactive Programming you've been missing by Andre staltz](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)
* [Jake Wharton: Exploring RxJava 2 for Android](https://realm.io/news/gotocph-jake-wharton-exploring-rxjava2-android/)
* [StableKernel: AsyncTasks vs. RxJava](http://blog.stablekernel.com/replace-asynctask-asynctaskloader-rx-observable-rxjava-android-patterns/)
* [Instacart Kaushik Gopal's: Subjects in RxJava](https://tech.instacart.com/how-to-think-about-subjects-part-1/)
* [Dan Lew: Error handling in RxJava](http://blog.danlew.net/2015/12/08/error-handling-in-rxjava/)
* [Important RxJava Operators](https://medium.freecodecamp.com/rx-if-the-operators-could-speak-58567c4618f1#.ilsr3heh6)
* [RxMarbles site](http://rxmarbles.com/#concat)
* [Server polling and retrying failed operations. With Retrofit and RxJava](https://medium.com/@v.danylo/server-polling-and-retrying-failed-operations-with-retrofit-and-rxjava-8bcc7e641a5a#.112bsh9w9)
* [Reactive MVP in theory](https://medium.com/@mvarnagiris/reactive-mvp-part-1-b751ce3e3246#.tlcjwub41)
* [RxJava and RxBinding](https://guides.codepath.com/android/RxJava-and-RxBinding)
* [Reactive Android UI programming with RxBinding](https://realm.io/news/donn-felker-reactive-android-ui-programming-with-rxbinding/)
* [Improving UX with RxJava](https://lorentzos.com/improving-ux-with-rxjava-4440a13b157f#.nguy4cyi6)
* [Reactive Views Retrying errors](https://medium.com/xing-engineering/reactive-views-retrying-errors-a59fffbd827f#.8oxbz7q0v)
* [Things to learn from introducing RxJava](https://medium.com/@MauroFrezza/3-things-i-have-learned-from-introducing-rxjava-in-my-app-933bd4ba397d#.9azm4ryl6)
* [Pacoworks FRP Series(Can be advanced for a beginner)](http://www.pacoworks.com/intro-to-frp/)
* [Pacoworks: Fully Reactive apps](http://www.pacoworks.com/2016/11/02/fully-reactive-apps-at-droidcon-uk-2016-2/)
* [RxRecipes - wrap your way to Rx](https://hackernoon.com/rxrecipes-wrap-your-way-to-rx-fd40eb5254b6#.krpuhkmeu)

### Kotlin
* [Why Kotlin is my next programming language](https://medium.freecodecamp.com/why-kotlin-is-my-next-programming-language-c25c001e26e3#.4y7le31ke)
* [Why You Must Try Kotlin For Android Development ?](https://blog.mindorks.com/why-you-must-try-kotlin-for-android-development-e14d00c8084b#.edop4kxn9)
* [How Kotlin became our primary language for Android](https://medium.com/uptech-team/how-kotlin-became-our-primary-language-for-android-3af7fd6a994c#.plzqclif7)
* [Jake Wharton - Using Project Kotlin for android](https://docs.google.com/document/d/1ReS3ep-hjxWA8kZi0YqDbEhCqTt29hG8P44aA9W0DM8/edit#heading=h.v6i4iyf7kkxh)
* [Is kotlin another buzzword](https://www.reddit.com/r/androiddev/comments/5fdz4a/is_kotlin_another_buzzword/)
* [Antonio leiva Kotlin](https://antonioleiva.com/kotlin/)
* [Codemotion FRP + Kotlin](https://drive.google.com/file/d/0BxCm4NRlzb3PWjNNaG1KS0Utckk/view)
* [5 small things you probably don’t know about Kotlin](https://hackernoon.com/5-small-things-you-probably-dont-know-about-kotlin-255261940de6#.tzjpmvgh0)
* [RxAndroid and Kotlin (Part 1)](https://medium.freecodecamp.com/rxandroid-and-kotlin-part-1-f0382dc26ed8#.v3iehee6v)
* [Kotlin : Retrofit + RxAndroid + Realm](https://medium.com/@ahmedrizwan/kotlin-retrofit-rxandroid-realm-39d7be5dc9dc#.8y60zqht7)
* [Keddit - Learn kotlin making the reddit app in kotlin](https://medium.com/@juanchosaravia/learn-kotlin-while-developing-an-android-app-introduction-567e21ff9664#.c3opwtfsm)
* [A glimpse of Async-Await on Android](https://medium.com/@haarman.niek/async-await-in-android-f0202cf31088#.powk38ajh)
* [A dive into Async-Await on Android](https://medium.com/@haarman.niek/a-dive-into-async-await-on-android-5a6699029aa3#.1rr6wtuee)

# Views, Layouts, Animations and Custom views

### Animation and Vector Drawable's stuff
* [Animated icons on Android by using vector drawables](https://stories.uplabs.com/animated-icons-on-android-ee635307bd6#.969srmak8)
* [AnimatedVectorDrawableCompat by Bartek Lipinski](https://android.jlelse.eu/animatedvectordrawablecompat-3d9568727c53#.xde3feipq)
* [Introductio to icon animation techniques](http://www.androiddesignpatterns.com/2016/11/introduction-to-icon-animation-techniques.html)
* [View animation and much more! by Ribot](https://labs.ribot.co.uk/exploring-meaningful-motion-on-android-1cd95a4bc61d#.n5gk8fhyu)
* [Animation: Jump-through by Nick Butcher](https://medium.com/google-developers/animation-jump-through-861f4f5b3de4#.swky4np25)
* [Jeremie Martinez: How we design a beautiful animation](http://jeremie-martinez.com/2016/09/15/train-animations/?utm_source=androiddevdigest)
* [Transitions in the Android Support Library by Chet Haase](https://medium.com/google-developers/transitions-in-the-android-support-library-8bc86a1d688e#.o1yv84m4o)
* [Animations powered by RxJava](https://pspdfkit.com/blog/2016/android-animations-powered-by-rx-java/)
* [Great animations with PageTransformer](https://medium.com/@BashaChris/the-android-viewpager-has-become-a-fairly-popular-component-among-android-apps-its-simple-6bca403b16d4#.dhixt7apg)
* [Shared Element Transitions Between Views (not Activities or Fragments)](http://stackoverflow.com/questions/28386397/shared-element-transitions-between-views-not-activities-or-fragments)

### Recycler View
* [For Different Items in Recycler View](https://medium.com/@dpreussler/writing-better-adapters-1b09758407d2#.shhat9mq3)
* [Simplifying RecyclerView Adapters with Rx & Databinding](https://medium.freecodecamp.com/simplifying-recyclerview-adapters-with-rx-databinding-f02ebed0b386#.9n0pc14sw)
* [Writing Better Adapters-Managing adapter having multiple items in a list](https://medium.com/@dpreussler/writing-better-adapters-1b09758407d2#.dtk5p1qxq)
* [Pro Recycler View](https://realm.io/news/360andev-yigit-boyar-pro-recyclerview-android-ui-java/)
* [RecyclerView Prefetch](https://medium.com/google-developers/recyclerview-prefetch-c2f269075710#.6t00v1oc5)
* [RecyclerView Tips: How we achieved 60 FPS in Workable’s Android Recruiting App](https://blog.workable.com/recyclerview-achieved-60-fps-workables-android-app-tips/)
* [Epoxy: Airbnb’s View Architecture on Android](https://medium.com/airbnb-engineering/epoxy-airbnbs-view-architecture-on-android-c3e1af150394#.mw0vh53zr)
* [Grouping Data in recycler view](https://krtkush.github.io/2016/07/08/android-recyclerview-grouping-data.html)
* [Android Data Binding: RecyclerView](https://medium.com/google-developers/android-data-binding-recyclerview-db7c40d9f0e4#.d9odpzqps)
* [Using SnapHelper in RecyclerView](https://blog.mindorks.com/using-snaphelper-in-recyclerview-fc616b6833e8#.y3h2elk1d)

### Making Custom Library and Views
* [A deep dive into android view constructors](http://blog.danlew.net/2016/07/19/a-deep-dive-into-android-view-constructors/)
* [How to draw a custom view](https://hackernoon.com/android-draw-a-custom-view-ef79fe2ff54b#.dei8shybf)
* [Make an android custom view, publish and open source](https://medium.com/dualcores-studio/make-an-android-custom-view-publish-and-open-source-99a3d86df228#.bnjjtd54i)
* [How to make and publish your android library](https://m.signalvnoise.com/how-i-built-my-first-android-open-source-library-and-how-you-can-too-8a731abbdd2a#.4g36dd5h7)
* [Publishing libraries to maven](http://www.andevcon.com/news/publishing-android-libraries-to-maven?utm_source=androiddevdigest)
* [Publishig android library aar to maven](http://www.vandalsoftware.com/post/52468430435/publishing-an-android-library-aar-to-a-maven)
* [Guide to publishing your Android Library via MavenCentral](http://crushingcode.co/publish-your-android-library-via-mavencentral/)

# Application helper tasks

### Login and Account Authentication
* [Refer to This github rxjava project for login-registration demo code](https://github.com/manuelvicnt/RxJava-android-structure)
* [Improving sign-in experience with Google Sign-In and SmartLock] (https://medium.com/@p.tournaris/android-improving-sign-in-experience-with-google-sign-in-and-smartlock-f0bfd789602a#.g7mzdbq8i)
* [Tells using android account manager to add auth-token account verification](http://www.pilanites.com/android-account-manager/)	

### Settings and Preferences
* [OnePref library for making settings](https://android.jlelse.eu/one-pref-for-androids-pride-b254e79f7d88#.bky7jvwbx)

### Scheduling Jobs and alarms
* [Scheduling jobs like a pro with JobScheduler](https://medium.com/google-developers/scheduling-jobs-like-a-pro-with-jobscheduler-286ef8510129#.bjva7oevj)
* [Alarms in android and effect of doze on them](http://pguardiola.com/blog/darealfragmentation-alarms/)

### Audio in android
* [Audio (not) playing in Android](https://medium.com/uptech-team/audio-not-playing-in-android-cde9a0fdfafd#.q9u3ivu0q)
* [Create an Audio Recorder on Android](http://www.ssaurel.com/blog/create-an-audio-recorder-on-android/?utm_source=androiddevdigest)

# App analytics
* [The key concepts of app tracking for developers](https://medium.com/@sergii/the-key-concepts-of-app-tracking-for-developers-a11bebf1e65e#.2015w5bka)

# Testing - Unit and production tests
### Testing
* [Dan lew's series on testing](http://blog.danlew.net/2013/12/16/testing_on_android_part_1_unit_tests/)
* [Simple unit tests for android](https://stfalcon.com/en/blog/post/simple-unit-tests-for-android)
* [Testing Asynchronous RxJava code with Mockito](https://medium.com/@fabioCollini/testing-asynchronous-rxjava-code-using-mockito-8ad831a16877#.7u4tkaa8l)
* [What does 'Don't Test the framework' means](https://www.bignerdranch.com/blog/what-does-dont-test-the-framework-mean/)
* [Running tests on command line with gradle](https://medium.com/android-testing-daily/running-your-tests-on-the-command-line-with-gradle-bcba78244487#.qjxj6ud3h)
* [How Dagger2 helps in android espresso tests](http://www.ottodroid.net/?p=514&utm_source=Android+Weekly&utm_campaign=0edd406528-Android_Weekly_231&utm_medium=email&utm_term=0_4eb677ad19-0edd406528-337972929)
* [The Do’s and Don’ts of Writing Test cases in Android](https://blog.mindorks.com/the-dos-and-don-ts-of-writing-test-cases-in-android-70f1b5dab3e1#.mmxzvio69)

### App production testing
* [Stress testing android apps](https://medium.com/@mgazar/stress-testing-android-apps-601311ebf590#.k4k0rm810) 
* [The Ultimate Pre-Release Checklist for Android App Success On Play Store](https://blog.aritraroy.in/the-ultimate-pre-release-checklist-for-android-app-success-on-play-store-cb0eb9f59ce9#.kvq5oq6me)

# Git Resources
* [Git-Play-Love](http://eulercoder.me/blog/open%20source/Git-Play-Love)
* [Git workflow basics - Going above commit push pull](https://blog.codeminer42.com/git-workflow-basics-d405746f6205#.lwyhvlllv)

# Open Source and stuff
* [Getting started with Open Source](http://eulercoder.me/blog/open%20source/getting-started-with-open-source)
* [How to get started with Open Source](https://www.hackerearth.com/getstarted-opensource/)
* [How to find your first open source bug to fix](https://medium.freecodecamp.com/finding-your-first-open-source-project-or-bug-to-work-on-1712f651e5ba#.jtlai29uz)

# Utility and design libraries
* [Create chat heads like facebook messenger](https://medium.com/@kevalpatel2106/create-chat-heads-like-facebook-messenger-32f7f1a62064#.49f525don) 
* [App entry feature discovery to teach user about the app](https://github.com/KeepSafe/TapTargetView)
* [A Tap Target implementation in Android based on Material Design Onboarding guidelines. For more information on tap targets check out the guidelines.](https://github.com/sjwall/MaterialTapTargetPrompt)
* [Library to create complex multi state animations](https://github.com/KeepSafe/MultiStateAnimation)
* [Add curve at bottom of image views and relative layouts](https://github.com/developer-shivam/Crescento)
* [To live blur images](https://github.com/wonderkiln/blurkit-android)
* [Android 3D style Page Flip](https://github.com/eschao/android-PageFlip)
* [Library to ask for permissions](https://github.com/Karumi/Dexter)
* [Android library for animating the path created from text ](https://github.com/thoughtbot/stencil)
* [A material-styled android view that provisions picking of a date, time & recurrence option, all from a single user-interface](https://github.com/vikramkakkar/SublimePicker)
* [A utility library for scheduling periodic and non-periodic jobs efficiently](https://github.com/hypertrack/smart-scheduler-android)
* [Repository for android animations Rx wrapper](https://github.com/0ximDigital/RxAnimations)
* [FAB custom view with horizonatal and vertical expanding.](https://github.com/HarinTrivedi/FABRevealMenu-master)
* [VoronoiView is a view (ViewGroup) that allows you to add and display views inside Voronoi diagram regions. Voronoi diagram](https://github.com/Quatja/Vorolay)
* [Decorate TextView](https://github.com/nntuyen/text-decorator)
* [ A wave-like loading drawable ](https://github.com/race604/WaveLoading)
* [About screen libary](https://github.com/daniel-stoneuk/material-about-library)
* [Custom BottomSheetBehavior for Android that mimic Google Maps behavior ](https://github.com/miguelhincapie/CustomBottomSheetBehavior)
* [Animate your activity](https://github.com/ppamorim/Dragger)
* [App intro library](https://github.com/apl-devs/AppIntro)
* [Dynamic iOS-like blur of underlying Views for Android ](https://github.com/Dimezis/BlurView)
* [Android library for async data loading from multiple sources](https://github.com/NYTimes/Store)
* [An imageView can auto scroll with device rotating. ](https://github.com/gjiazhe/PanoramaImageView)

# Proguard
* [Useful Proguard snippets](https://github.com/krschultz/android-proguard-snippets)

# Tools for reversing apk for educational purposes
* [A tool for reverse engineering Android apk files](https://github.com/iBotPeaches/Apktool)

# Miscellaneous
* [How To Learn With Open Source API Fundamentals](https://hackernoon.com/how-to-learn-with-open-source-api-fundamentals-1f886383b8e1#.ugnbbbjyl)
