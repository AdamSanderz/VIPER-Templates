# Installation

1. Copy the template folders or create a symbolic link to the GIT repo
  - Copy the VIPER Template folders to 
```
/Applications/Xcode.app/Contents/Developer/Library/Xcode/Templates/File\ Templates/Source/
```

   OR

```
  sudo ln -s (path to viper template repo)/VIPER.xctemplate /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Xcode/Templates/File\ Templates/Source/VIPER.xctemplate
  sudo ln -s (path to viper template repo)/VIPER\ Tests.xctemplate /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Xcode/Templates/File\ Templates/Source/VIPER\ Tests.xctemplate
```
2. Start Xcode and create a new file (File > New > File or ⌘N)
3. Choose VIPER or VIPER Test

# VIPER - Objective-C

- `Interactor.h`
- `Interactor.m`
- `InteractorProtocols.h` - Interactor Input protocol
- `Presenter.h`
- `Presenter.m`
- `PresenterProtocols.h` - Interactor Output, Presenter Interface, Routing protocols
- `View.h`
- `View.m`
- `ViewProtocols.h` - View Interface protocol
- `Wireframe.h`
- `Wireframe.m`
- `WireframeProtocols.h` - Module Delegate and Wireframe Interface protocols

# VIPER - Swift

- `Interactor.swift`
- `InteractorProtocols.swift` - Interactor Input protocol
- `Presenter.swift`
- `PresenterProtocols.swift` - Interactor Output, Presenter Interface, Routing protocols
- `View.swift`
- `ViewProtocols.swift` - View Interface protocol
- `Wireframe.swift`
- `WireframeProtocols.swift` - Module Delegate and Wireframe Interface protocols

# VIPER Tests - Objective-C

- `InteractorTests.m`
- `PresenterTests.m`
- `ViewTests.m`
- `WireframeTests.m`

# VIPER Tests - Swift

- `InteractorTests.swift`
- `PresenterTests.swift`
- `ViewTests.swift`
- `WireframeTests.swif`

# TODO

- Keep it sexy
