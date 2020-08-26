# UIColorExtension
 Extensions UIColor Swift Class



### Class Initializer with hexadecimal String parameter

```swift
if let color = UIColor.init(hex: "#EE5DA3", alpha: 1) {
 ...
}
```

### Convert UIColor to Hexadecimal String

```swift
if let colorHex = color.toHex() {
 ...
}
```

### Get RGB values from UIColor
* Get Red, Green and Blue values in 0...255 range

```swift
print(color.rgba.red) //238
print(color.rgba.green) //93
print(color.rgba.blue) //163
```

### Get HSB values from UIColor
* Get Hue value in 0...365 range
* Get Saturation and Brightness values in 0...100 range

```swift
print(color.hsba.hue) //330.91
print(color.hsba.saturation) //61.05
print(color.hsba.brightness) //93.33
```
