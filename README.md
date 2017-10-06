# Spritekit - Label Multiple Line

How to create Label from Sprite Kit (SKLabelNode) Multiple Line

1. Get Label Node
2. set lineBreakMode
3. set numberOfLines = 0
4. set width of label


v

v

v


```swift
let label = self.childNode(withName: "helloLabel") as? SKLabelNode
label.text = "Lorem ~ jaawdawdsawdo8" 
label.lineBreakMode = NSLineBreakMode.byWordWrapping 
label.numberOfLines = 0 
label.preferredMaxLayoutWidth = 500
```


(More lineBreakNode)[https://developer.apple.com/documentation/uikit/nslinebreakmode]
