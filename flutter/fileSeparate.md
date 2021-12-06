# ファイル分割

Dartで書いてる時にどうしても1ファイルが長くなってしまって、見通し悪いなとおもった。

以下にて分割可能。

1. lib配下に任意ディレクトリ作成
2. 作成したディレクトリ内でファイル作成。分割したいクラスを記載。
3. 分割元のファイルでimportにより分割先ファイルを指定する。

```dart
//testproject
//main.dart

import 'package:testproject/sub1/sub.dart';

void main(){
	runApp(MainApp());
}

class MainApp extends ~~~~
// subClassを呼び出し可能

```

```dart
//sub.dart

class subClass extends StatefulWidget {
	~~~~~
```