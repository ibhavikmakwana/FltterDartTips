# Flutter/Dart Tips

### 7. Want to set different Theme for a perticular widget ?

Just wrap the widget with the `Theme` Widget and pass the `ThemeData()`.

<img src="./tips/ThemeWidgetExample.png" height="250" alt="Screenshot"/>

### 6. Use Ternary operator instead of the if else to shorter your Dart code.

Use below.

<img src="./tips/ternary.png" height="250" alt="Screenshot"/>

Instead of this.

<img src="./tips/if_else.png" height="250" alt="Screenshot"/>

### 5. Want to run task periodically in Dart?

What about using `Timer.periodic`
It will create a repeating timer, It will take a two argument one is `duration` and second is `callback` that must take a one Timer parameter.

<img src="./tips/timer.png" height="250" alt="Screenshot"/>

You can cancle the timer using the `timer.cancel()`.

### 4. Apply style as a Theme in a `Text` widget.
Check out below article for detail information about this tip.
[Apply style as a Theme in a `Text` widget](https://medium.com/flutter-community/flutter-apply-style-as-a-theme-in-a-text-widget-90268328bd23)

<img src="./tips/text_theme.png" height="250" alt="Screenshot"/>

## Monthly Tip Article

This article contains the Tips that I have wirtten over here.

[#1 Flutter + Dart Tips](https://medium.com/flutter-community/1-flutter-dart-tips-830854c3a418)


### 3. Do not explicitly initialize variables to `null`.

Adding `= null` is redundant and unneeded.

<img src="./tips/avoid_init_null.png" height="250" alt="Screenshot"/>

### 2. Using `ListView.separated()`
Want to add the separator in your Flutter ListView?

Go for the
`ListView.separated();`

Best part about seprated is it can be any widget.😃

Check out the below image for the sample code.

<img src="./tips/ListViewSeprated.png" height="250" alt="Screenshot"/>

### 1. Using `null-aware operators`
While checking the null in the Dart, Use `null-aware operators` help you reduce the amount of code required to work with references that are potentially null.

<img src="./tips/DartTip_14-1-2019.png" height="250" width="250" alt="Screenshot"/>
