# Spritekit - Label Multiple Line

How to create Label from Sprite Kit (SKLabelNode) Multiple Line


```swift
let label = self.childNode(withName: "helloLabel") as? SKLabelNode
label.text = "Lorem ~ jaawdawdsawdo8" 
label.lineBreakMode = NSLineBreakMode.byWordWrapping 
label.numberOfLines = 0 
label.preferredMaxLayoutWidth = 500
```
