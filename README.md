🔨🔨🔨 This is work in progress 🔨🔨🔨

# Custom notification UI widget for iOS written in Swift

This is a library for displaying a text notification bar. I can be used to show success messages and validation errors.

## Usage

### Show notification bar


```Swift
view.dodo.success("Success is not a good teacher, failure makes you humble.")
view.dodo.info("Extinction is the rule. Survival is the exception.")
view.dodo.warning("This world is but a canvas to our imagination.")
view.dodo.error("Goodness is the only investment that never fails.")

```

Note: if there is an existing notification bar in a UIView it will be replaced by the new one.


### Hide notification bar

```Swift
view.dodo.hide()
```

### Syling

```Swift
view.dodo.style.label.color = UIColor.whiteColor()
view.dodo.style.label.font = UIFont.preferredFontForTextStyle(UIFontTextStyleBody)
view.dodo.style.bar.backgroundColor = DodoColor.fromHexString("#00000090")
view.dodo.style.bar.cornerRadius = 10
```