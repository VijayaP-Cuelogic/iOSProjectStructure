# Project Structure 

## Prerequisites:
- macOS
- Xcode
- Simulator

## Getting started

To create new project:

- Download and install Xcode
- Create project.

## Folder structure
 * [DemoProject](./tree-md)
  * [AppDelegate](./dir1)
    * [SceneDelegate.swift](./dir1/SceneDelegate.swift)
    * [AppDElegate.swift](./dir1/AppDElegate.swift)
  * [Views](./dir2)
    * [CustomView.xib](./dir2/CustomView.xib)
    * [CustomView.swift](./dir2/CustomView.swift)
 * [ViewControllers](./dir3)
   * [ViewController.swift](./dir3/ViewController.swift)
 * [Utils](./dir4)
   * [Constants.swift](./dir4/Constants.swift)
   * [AlertMessage.swift](./dir4/AlertMessage.swift)
 * [ViewControllers](./dir5)
   * [ViewController.swift](./dir5/ViewController.swift)
 * [Resources](./dir6)
   * [Assets.xcassets](./dir6/Assets.xcassets)
 * [Network](./dir7)
   * [ConnectApi.swift](./dir7/ConnectApi.swift)
   * [NetworkingClass.swift](./dir7/NetworkingClass.swift)
 * [Libraries](./dir8)
 * [ModelClass](./dir9)
   * [CoreDataClass.xcdatamodel](./dir9/CoreDataClass.xcdatamodel)
 * [Main.storyboard](./Main.storyboard)
 * [LaunchScreen.storyboard](./LaunchScreen.storyboard)
 * [info.plist](./info.plist)
 * [README.md](./README.md)
 * [Products](./dir10)
   * [DemoProject.app](./dir10/DemoProject.app)

## Component architecture
  ### Components will be of the following types
  
  - `LaunchScreen.StoryBoard` - This is the first thins you see on screen on application launch.
  - `Main.StoryBoard` - ScreenDesigns of Application.
  - `AppDelegate.swift` - root boject of your app it handles UIApplicationStates.
  - `SceneDelegate.swift` - SceneDelegate is responsible for what’s displayed on the screen in terma of UI and data.
  - `Resources` - Inside Resources you can add images directly or can add images in `Assets`.
  - `Utils` folder contains all global constants files and environment configuration constants,macros, etc.
  - `Views`- it contains all custom views like popUps, DropdownViews,subViews, etc.
  - `ViewControllers`- it contains all ViewControllers(Screen) classes.
  - `ModelClass`- it contains all database related classes.
  - `Network`- it contains all APICalls, Networking, Reachability classes.
  - `Libraries`- it contains thirdparty libraries.
  - `info.plist`- It is the project configuration file, it contains bundle id,display name,version etc.
  
