# rich_textfield

flutter富文本输入框，支持表情、@某人、#话题#

![The example screen shot](https://github.com/wuxuan2811/flutter_expand_textfield/blob/master/screenShot/Screenshot_1.png)

## 使用方法
```Dart
import 'package:rich_textfield/rich_textfield.dart';
MyTextEditingController _editCtrl = new MyTextEditingController(
  topicStyle: new TextStyle(
    fontWeight: FontWeight.bold,
    color: Colors.yellow
  ),
  atStyle: new TextStyle(
    fontWeight: FontWeight.bold,
    color: Colors.green
  ),
  emojiImgSourceType: EmojiImgSourceType.asset
);

Widget ret = new MyTextField(
  controller: _editCtrl,
  focusNode: _focusNode,
  style: new TextStyle(
    fontSize: 20,
    color: const Color.fromARGB(255, 180, 180, 180)
  ),
);
```
