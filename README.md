<picture>
    <source srcset="./media/logo-dark.svg" media="(prefers-color-scheme: dark)" alt="realm by MongoDB">
    <img src="./media/logo.svg" alt="realm">
</picture>

# About Realm Database

Realm is a mobile database that runs directly inside phones, tablets or wearables.
This repository is a detached fork of the source code for the iOS, macOS, tvOS & watchOS versions of Realm Swift & Realm Objective-C.

## Building Realm

You can build Realm yourself from source.

Prerequisites:

* Building Realm requires Xcode 14.1 or newer.
* Building Realm documentation requires [jazzy](https://github.com/realm/jazzy) (official repo) or [jazzy fork](https://github.com/dacharyc/jazzy)

Once you have all the necessary prerequisites, building Realm just takes a single command: `sh build.sh build`.
You'll need an internet connection the first time you build Realm to download the core binary.
This will produce Realm.xcframework and RealmSwift.xcframework in `build/Release/`.

Run `sh build.sh help` to see all the actions you can perform (build ios/osx, generate docs, test, etc.).

## License

Realm Objective-C & Realm Swift are published under the Apache 2.0 license.
Realm Core is also published under the Apache 2.0 license and a fork is
available [here](https://github.com/dacharyc/realm-core).
