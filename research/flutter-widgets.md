# Flutter Widgets Research

## 1. Introduction

Flutter Widgets are the basic building blocks
used to create user interfaces (UI).

Everything in Flutter UI is represented by widgets,
including text, images, buttons, layouts, and styling.

## 2. Widget Characteristics

- Widgets describe the user interface.
- Widgets are written using Dart.
- Widgets can be combined to create complex interfaces.
- Widgets are organized in a Widget Tree.
- Widgets help build reusable UI components.

## 3. Main Widget Categories

| Category | Examples |
|---|---|
| Basic | Text, Image, Icon |
| Layout | Row, Column, Stack |
| Styling | Container, Padding |
| Input | TextField, Checkbox |
| Buttons | ElevatedButton, TextButton |
| Scrolling | ListView, GridView |

## 4. StatelessWidget

StatelessWidget is a widget that does not
manage mutable state of its own.

Examples:
- Static Text
- Logo
- Icon
- Fixed Information

## 5. StatefulWidget

StatefulWidget is used when a widget needs
to manage mutable state.

Its UI can be updated when its state changes.

Examples:
- Counter
- Checkbox
- Switch
- Interactive Button

## 6. Comparison

| Feature | StatelessWidget | StatefulWidget |
|---|---|---|
| Own mutable state | No | Yes |
| UI updates | When rebuilt | When state changes |
| State management | No internal State object | Uses a State object |
| Example | Static Text | Counter |

## 7. Widget Tree

A Widget Tree is a hierarchical structure that represents how widgets are organized in a Flutter user interface.

### Example

The following diagram shows a simple Flutter Widget Tree:

```text
MaterialApp
└── Scaffold
    └── Column
        ├── Text
        ├── Image
        └── ElevatedButton
```

### Key Concepts

* Root Widget: The top-level widget.

* Parent Widget: A widget containing other widgets.

* Child Widget: A widget contained inside another widget.

* Widget Tree: The complete widget hierarchy.

### Explanation

* MaterialApp: The root widget of this example.

* Scaffold: Provides the basic screen structure.

* Column: Arranges its child widgets vertically.

* Text: Displays text.

* Image: Displays an image.

* ElevatedButton: Creates an interactive button.

## 8. Layout Widgets

Layout widgets control the position
and arrangement of other widgets.

| Widget | Purpose |
|---|---|
| Row | Arranges children horizontally |
| Column | Arranges children vertically |
| Stack | Places widgets on top of each other |
| Container | Provides layout and decoration |
| Padding | Adds empty space around a child |
| Center | Centers its child widget |

## 9. Button Widgets

Button widgets allow users to interact
with a Flutter application.

| Widget | Purpose |
|---|---|
| ElevatedButton | Displays a prominent button |
| TextButton | Displays a text-based button |
| OutlinedButton | Displays a button with an outline |
| IconButton | Displays a button with an icon |

## 10. Input Widgets

Input widgets allow users to enter
or select information.

| Widget | Purpose |
|---|---|
| TextField | Accepts text input |
| Checkbox | Provides a selection option |
| Switch | Changes between on and off |
| Radio | Selects one option |
| Slider | Selects a value within a range |

## 11. Scrolling Widgets

Scrolling widgets help users navigate
content that exceeds the available screen space.

| Widget | Purpose |
|---|---|
| ListView | Displays a scrollable list |
| GridView | Displays items in a grid |
| SingleChildScrollView | Provides scrolling for one child |
| PageView | Displays scrollable pages |

## 12. Widget Code Examples

### Text Widget

Displays text on the screen.

```dart
Text("Hello Flutter")

```

### Row Widget

Arranges children horizontally.

```dart
Row(
  children: [
    Text("One"),
    Text("Two"),
  ],
)
```

### Column Widget

Arranges children vertically.

```dart
Column(
  children: [
    Text("First"),
    Text("Second"),
  ],
)
```

### Container Widget

Creates a box that can contain a child widget and apply styling.

```dart
Container(
  padding: EdgeInsets.all(10),
  child: Text("Hello Flutter"),
)
```

### ElevatedButton Widget

Creates a raised button that responds to user interaction.

```dart
ElevatedButton(
  onPressed: () {
    print("Button pressed");
  },
  child: Text("Click Me"),
)
```

## 13. Research Summary

Flutter Widgets are the fundamental building blocks of Flutter applications.

Key findings:

- Widgets describe the user interface.
- StatelessWidget is used for UI without mutable state.
- StatefulWidget manages mutable state.
- Widget Tree represents the hierarchical UI structure.
- Layout widgets organize UI elements.
- Input widgets allow user interaction.
- Scrolling widgets display scrollable content.

Research Project: RZXXY Flutter Research
Subject: Flutter Widgets
Status: Documentation research completed.
Environment: iSH / Alpine Linux

## 14. Official References

- Flutter Widget Catalog: https://docs.flutter.dev/ui/widgets
- Flutter UI Documentation: https://docs.flutter.dev/ui
- Flutter Widget Index: https://docs.flutter.dev/reference/widgets
