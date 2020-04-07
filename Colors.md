# Colors

### Core colors

```tokens
let primary: Color = #color(css: "#45CBFF")
```

```tokens
let secondary: Color = #color(css: "#14CE7D")
```

### State colors

```tokens
let primaryActive: Color = Color.saturate(color: primary, factor: 0.5)
```

### Nested Colors

```tokens
extension Brand {
  static let red: Color = #color(css: "#E01212")
  static let orange: Color = #color(css: "#D98B00")
}
```

