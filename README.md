NewOmniFocusAction
==================

open New Inbox Item screen in OmniFocus for iOS

---

```swift
func applicationDidBecomeActive(application: UIApplication) {
    UIApplication.sharedApplication().openURL(NSURL(string: "omnifocus:///add")!)
}
```
