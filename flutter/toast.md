# Popup(トースト)を出したい

[GitHub - ponnamkarthik/FlutterToast: Toast Plugin for Flutter](https://github.com/PonnamKarthik/FlutterToast)

これを使えば簡単に実装できた。

```dart
Fluttertoast.showToast(
        msg: "このメッセージが表示される",
        toastLength: Toast.LENGTH_SHORT,
        gravity: ToastGravity.CENTER,
        timeInSecForIosWeb: 1,
        backgroundColor: Colors.red,
        textColor: Colors.white,
        fontSize: 16.0
    );
```