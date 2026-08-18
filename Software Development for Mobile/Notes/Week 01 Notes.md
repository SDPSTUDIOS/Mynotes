XML and Jetpack compose

When the phone rings the call has the highest priority - Call pause or eco mode

Android and IOS is considered as Frameworks in this unit atleast

ART is the managed runtime environment used by Android to execute apps. It replaced the older Devkit runtime starting with Android 5.0 (Lollipop) as the default.

These will help 
- Event Handeling
- Callbacks - Hash table and hash maps
- Singleton, Factory, Visitor design patterns
- Have built user interfaces in another language/framework (incl. Swing/AWT)

Emulator vs Simulators
- Android has Emulator and IOS and Simulator
- Simulators are up fast and good enough
- Emulators - allow checking against different versions of the OS easily, and are closer to the phone hardware

## When making an App in android app

In the `mainactivity` is the first the script to run and `fun oncreate()`
# Test Hints

**What is the Gradle system?**
Gradle is the **build system** used by Android Studio (and lots of other Java/Kotlin projects) — it's the tool that takes your source code, resources, and dependencies, and turns them into an actual runnable app (an APK or AAB file).

Think of it as the automated assembly line behind the scenes. When you hit "Run" in Android Studio, Gradle is doing things like:

- **Compiling your code** — turning your Kotlin/Java into bytecode
- **Fetching dependencies** — downloading libraries your app relies on (like Retrofit, Coroutines, Jetpack Compose, etc.) from repositories like Maven Central or Google's Maven repo
- **Processing resources** — merging your XML layouts, images, strings, and manifest files
- **Packaging everything** — bundling it all into an APK/AAB, signing it, and optimizing it
- **Running tasks** — anything from running unit tests to generating documentation