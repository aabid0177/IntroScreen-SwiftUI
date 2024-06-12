### IntroScreen

### Package URL
https://github.com/aabid0177/IntroScreen-SwiftUI

### Preview
![ezgif com-video-to-gif-converter (3)](https://github.com/aabid0177/IntroScreen-SwiftUI/assets/58103845/033f84cd-c0c1-496b-b45b-cbb0de2f69fd)


### How to use?
-> Add package [IntroScreen](https://github.com/aabidDevit/IntroScreen) in your xcode <br>
![ezgif com-video-to-gif-converter (2)](https://github.com/aabid0177/IntroScreen-SwiftUI/assets/58103845/2b7f237e-6cea-4c70-92b9-a2308fd83949)


### Code
```swift
import SwiftUI
import IntroScreen

let introData: [IntroData] = [
    IntroData(title: "Choose Products", desc: "Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit.", imageInAsset: "twinlake"),
    IntroData(title: "Make Payment", desc: "Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit.", imageInAsset: "twinlake"),
    IntroData(title: "Get Your Order", desc: "Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit.", imageInAsset: "twinlake")
]

struct ContentView: View {
    var body: some View {
        Intro(introDataArray: introData, skipButtonTapEvent: {
            
        }, getStartedButtonTapEvent: {
            
        }, introTextStyle: IntroTextStyle(titleTextStyle: .init(textFont: Font.title), descTextStyle: .init(textFont: .system(.title3, weight: .regular)),skipTextStyle: .init(textColor: .pink),  prevTextStyle: .init(textColor: .pink), nextTextStyle: .init(textColor: .pink), pageCountTextStyle: .init(textColor: .pink)))
    }
}
```
