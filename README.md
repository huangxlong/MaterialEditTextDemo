# MaterialEditTextDemo
github: https://github.com/rengwuxian/MaterialEditText

use:  implementation 'com.rengwuxian.materialedittext:library:2.1.4'

# 全部参数
## 通用颜色
met_baseColor: 底部横线和所有文字在无焦点状态的基础色。默认为黑色。

met_primaryColor: 底部横线和 Floating label 的高亮色（如果 met_floatingLabel 设置为 highlight 的话）。默认使用 baseColor。

met_textColor: 和自带的 android:textColor 作用相同。换用这个就好。

met_textColorHint: 和自带的 android:textColorHint 作用相同。换用这个就好。

met_underlineColor: 自定义底部横线的颜色。

Floating label
met_floatingLabel: Floating label 应该怎样被展示。选项有：none, normal, highlight。 默认是 none.

met_floatingLabelText: 自定义 floating label 的文字。

met_floatingLabelTextSize: Floating label 的字体大小。默认为 12sp。

met_floatingLabelTextColor: Floating label 的字体颜色。默认为半透明的 baseColor.

met_floatingLabelPadding: Floating label 和主文字区域的间隔。

met_floatingLabelAnimating: 是否使用动画来显示和消失 floating label 。默认为 true 。

met_floatingLabelAlwaysShown: 是否总是显示 Floating label 。默认为 false 。

## 字数限制
met_minCharacters: 限制的最少字数。默认为0。

met_maxCharacters: 限制的最大字数。0为无限制。默认为0.

Helper/Error text
met_helperText: 底部的 helper text。

met_helperTextAlwaysShown: 是否总是显示 helper text， 而不仅仅是在获得焦点状态时。默认为 false。

met_helperTextColor: Helper text 的字体颜色。

met_errorColor: Error text 的字体颜色。

met_bottomTextSize: 底部文字（Helper/Error text）的字体大小。默认为12sp。

met_minBottomTextLines:底部为文字预留的行数，不管是否有 Helper/Error text 正在显示。

## 字体（Typeface）
met_typeface: 主文字的字体.

met_accentTypeface: 辅助文字的字体.

Material Design 风格的左右图标
met_iconLeft: 左边的图标.

met_iconRight: 右边的图标.

met_iconPadding: 图标和主区域之间的padding。默认为16dp, 遵守 Google's Material Design Spec 中的建议.

## Others
met_hideUnderline: 是否隐藏底部横线。默认为 false。

met_autoValidate: 是否自动检查字符串。默认为 false。

met_singleLineEllipsis: 是否在文字超长时显示底部的省略号。默认为 false。

met_clearButton: 是否显示用来清空文字的 Clear button 。默认为 false。
