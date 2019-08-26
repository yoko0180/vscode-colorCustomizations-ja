# vscode-colorCustomizations-ja

#### 参照
https://code.visualstudio.com/api/references/theme-color

# テーマカラー

workbench.colorCustomizationsユーザー設定を使用して、アクティブなVisual Studio Codeカラーテーマをカスタマイズできます。

```json
{
  "workbench.colorCustomizations": {
    "activityBar.background": "#00AA00"
  }
}
```

## 目次

- [コントラスト色](コントラスト色)
- [ベースカラー](ベースカラー)
- [テキストの色](テキストの色)
- [ボタンコントロール](ボタンコントロール)
- [ドロップダウン制御](ドロップダウン制御)
- [入力制御](入力制御)
- [スクロールバーコントロール](スクロールバーコントロール)
- [バッジ](バッジ)
- [プログレスバー](プログレスバー)
- [リストとツリー](リストとツリー)
- [アクティビティバー](アクティビティバー)
- [サイドバー](サイドバー)
- [ミニマップ](ミニマップ)
- [エディターの色](エディターの色)
- [発生](発生)
- [一致を見つける](一致を見つける)
- [ホバーハイライト](ホバーハイライト)
- [行のハイライト](行のハイライト)
- [コードレンズ](コードレンズ)
- [ブラケット色](ブラケット色)
- [エラーと警告：](エラーと警告：)
- [未使用のソースコード：](未使用のソースコード：)
- [差分エディターの色](差分エディターの色)
- [エディターウィジェットの色](エディターウィジェットの色)
- [ピークビューの色](ピークビューの色)
- [競合のマージ](競合のマージ)
- [パネル色](パネル色)
- [ステータスバーの色](ステータスバーの色)
- [タイトルバーの色](タイトルバーの色)
- [メニューバーの色](メニューバーの色)
- [通知センター](通知センター)
- [拡張機能](拡張機能)
- [クイックピッカー](クイックピッカー)
- [統合ターミナルの色](統合ターミナルの色)
- [デバッグ](デバッグ)
- [ようこそページ](ようこそページ)
- [ぱんくずリスト](ぱんくずリスト)
- [スニペット](スニペット)


# コントラスト色
通常、コントラストの色は、コントラストの高いテーマにのみ設定されます。設定すると、UI全体のアイテムの周囲に追加の境界線が追加され、コントラストが向上します。

```javascript
contrastActiveBorder：アクティブな要素の周囲に余分な境界線を追加し、他の要素と区別してコントラストを高めます。
contrastBorder：要素を囲む余分な境界線で、要素を他と区別してコントラストを高めます。
```

# ベースカラー

```javascript
focusBorder：フォーカスされた要素の全体的な境界線の色。この色は、コンポーネントによってオーバーライドされない場合にのみ使用されます。
foreground：全体的な前景色。この色は、コンポーネントによってオーバーライドされない場合にのみ使用されます。
widget.shadow：エディター内の検索/置換などのウィジェットの影の色。
selection.background：ワークベンチ内のテキスト選択の背景色（入力フィールドまたはテキスト領域の場合、エディターおよびターミナル内の選択には適用されません）。
descriptionForeground：ラベルなどの追加情報を提供する説明テキストの前景色。
errorForeground：エラーメッセージの全体的な前景色（この色は、コンポーネントによってオーバーライドされない場合にのみ使用されます）。
```

# テキストの色
ウェルカムページなどのテキストドキュメント内の色。

```javascript
textBlockQuote.background：テキスト内のブロック引用の背景色。
textBlockQuote.border：テキスト内のブロック引用の境界線の色。
textCodeBlock.background：テキストのコードブロックの背景色。
textLink.activeForeground：マウスのホバーをクリックしたときのテキスト内のリンクの前景色。
textLink.foreground：テキスト内のリンクの前景色。
textPreformat.foreground：事前にフォーマットされたテキストセグメントの前景色。
textSeparator.foreground：テキスト区切りの色。
```

# ボタンコントロール
新しいウィンドウのエクスプローラーの[フォルダーを開く ]ボタンなどのボタンウィジェットの色のセット。

```javascript
button.background：ボタンの背景色。
button.foreground：ボタンの前景色。
button.hoverBackground：ホバリング時のボタンの背景色。
```

# ドロップダウン制御
統合ターミナルや出力パネルなど、すべてのドロップダウンウィジェットの色のセット。現在、ドロップダウンコントロールはmacOSでは使用されていないことに注意してください。

```
dropdown.background：ドロップダウンの背景。
dropdown.listBackground：ドロップダウンリストの背景。
dropdown.border：ドロップダウンボーダー。
dropdown.foreground：ドロップダウンの前景。
```

# 入力制御
[検索]ビューや[検索/置換]ダイアログなどの入力コントロールの色。

```
input.background：入力ボックスの背景。
input.border：入力ボックスの境界線。
input.foreground：入力ボックスの前景。
input.placeholderForeground：プレースホルダーテキストの入力ボックスの前景色。
inputOption.activeBackground：入力フィールドのアクティブ化されたオプションの背景色。
inputOption.activeBorder：入力フィールドのアクティブ化されたオプションの境界線の色。
inputValidation.errorBackground：エラーの重大度の入力検証背景色。
inputValidation.errorForeground：エラーの重大度の入力検証前景色。
inputValidation.errorBorder：エラーの重大度の入力検証境界色。
inputValidation.infoBackground：情報の重大度の入力検証背景色。
inputValidation.infoForeground：情報の重要度の入力検証前景色。
inputValidation.infoBorder：情報の重大度の入力検証境界色。
inputValidation.warningBackground：情報警告用の入力検証背景色。
inputValidation.warningForeground：警告の重大​​度の入力検証前景色。
inputValidation.warningBorder：警告の重大​​度の入力検証境界線の色。
```

# スクロールバーコントロール

```
scrollbar.shadow：ビューがスクロールされていることを示すスクロールバースライダーの影。
scrollbarSlider.activeBackground：クリックしたときのスクロールバースライダーの背景色。
scrollbarSlider.background：スクロールバースライダーの背景色。
scrollbarSlider.hoverBackground：ホバー時のスクロールバースライダーの背景色。
```

# バッジ
バッジは、検索結果の数などの小さな情報ラベルです。

```
badge.foreground：バッジの前景色。
badge.background：バッジの背景色。
```

# プログレスバー

```
progressBar.background：長時間実行される操作に対して表示される進行状況バーの背景色。
```

# リストとツリー
ファイルエクスプローラーのようなリストとツリーの色。アクティブリスト/ツリーにはキーボードフォーカスがあり、非アクティブリストにはありません。

```
list.activeSelectionBackground：リスト/ツリーがアクティブなときの選択されたアイテムのリスト/ツリーの背景色。
list.activeSelectionForeground：リスト/ツリーがアクティブなときの選択されたアイテムのリスト/ツリーの前景色。
list.dropBackground：マウスを使用してアイテムを移動するときのリスト/ツリーの背景のドラッグアンドドロップ。
list.focusBackground：リスト/ツリーがアクティブなときのフォーカスされたアイテムのリスト/ツリーの背景色。
list.focusForeground：リスト/ツリーがアクティブなときのフォーカスされたアイテムのリスト/ツリーの前景色。アクティブリスト/ツリーにはキーボードフォーカスがあり、非アクティブリストにはありません。
list.highlightForeground：リスト/ツリー内を検索するときに一致するハイライトのリスト/ツリーの前景色。
list.hoverBackground：マウスを使用してアイテムの上にマウスを移動したときのリスト/ツリーの背景。
list.hoverForeground：マウスを使用してアイテムの上にマウスを移動したときのリスト/ツリーの前景。
list.inactiveSelectionBackground：リスト/ツリーが非アクティブのときの選択されたアイテムのリスト/ツリーの背景色。
list.inactiveSelectionForeground：リスト/ツリーが非アクティブのときの選択されたアイテムのリスト/ツリーの前景色。アクティブリスト/ツリーにはキーボードフォーカスがあり、非アクティブリストにはありません。
list.inactiveFocusBackground：リストがアクティブでないときのフォーカスされたアイテムのリストの背景色。アクティブリストにはキーボードフォーカスがあり、非アクティブリストにはありません。現在、リストでのみサポートされています。
list.invalidItemForeground：エクスプローラーの未解決のルートなど、無効なアイテムのリスト/ツリーの前景色。
list.errorForeground：エラーを含むリストアイテムの前景色。
list.warningForeground：警告を含むリストアイテムの前景色。
listFilterWidget.background：リスト/ツリー内を検索するときに、入力したテキストのリスト/ツリーフィルターの背景色。
listFilterWidget.outline：リスト/ツリー内を検索するときのリスト/ツリーフィルターウィジェットの入力テキストのアウトラインカラー。
listFilterWidget.noMatchesOutline：リスト/ツリー内を検索するときに、入力したテキストに一致するものが見つからない場合のリスト/ツリーフィルターウィジェットのアウトラインカラー。
tree.indentGuidesStroke：ツリーウィジェットのインデントガイドのストロークの色。
```

# アクティビティバー
アクティビティバーはワークベンチの左端または右端に表示され、サイドバーのビューをすばやく切り替えることができます。

```
activityBar.background：アクティビティバーの背景色。
activityBar.dropBackground：アクティビティバーのアイテムのフィードバックカラーをドラッグアンドドロップします。
activityBar.foreground：アクティビティバーの前景色（たとえば、アイコンに使用）。
activityBar.inactiveForeground：アクティブでないときのアクティビティバー項目の前景色。
activityBar.border：アクティビティバーの境界線の色とサイドバー。
activityBarBadge.background：アクティビティ通知バッジの背景色。
activityBarBadge.foreground：アクティビティ通知バッジの前景色。
```

# サイドバー
サイドバーには、エクスプローラーや検索などのビューが含まれています。

```
sideBar.background：サイドバーの背景色。
sideBar.foreground：サイドバーの前景色。サイドバーは、エクスプローラーや検索などのビューのコンテナーです。
sideBar.border：エディターを分離するサイドのサイドバーの境界線の色。
sideBar.dropBackground：サイドバーセクションのフィードバックカラーをドラッグアンドドロップします。サイドバーのセクションがまだ透けて見えるように、色には透明性が必要です。サイドバーは、エクスプローラーや検索などのビューのコンテナーです。
sideBarTitle.foreground：サイドバーのタイトルの前景色。
sideBarSectionHeader.background：サイドバーセクションヘッダーの背景色。
sideBarSectionHeader.foreground：サイドバーセクションヘッダーの前景色。
sideBarSectionHeader.border：サイドバーセクションヘッダーの境界線の色。
```

# ミニマップ
ミニマップには、現在のファイルの縮小バージョンが表示されます。

```
minimap.findMatchHighlight：ファイル内の検索からの一致のハイライト色
```

エディターグループとタブ
エディタグループは、エディタのコンテナです。多くの編集者グループが存在する可能性があります。タブはエディターのコンテナーです。1つのエディターグループで複数のタブを開くことができます。

```
editorGroup.border：複数のエディターグループを互いに分離する色。
editorGroup.dropBackground：エディターをドラッグするときの背景色。
editorGroupHeader.noTabsBackground：タブが無効（設定"workbench.editor.showTabs": false）の場合のエディターグループタイトルヘッダーの背景色。
editorGroupHeader.tabsBackground：Tabsコンテナの背景色。
editorGroupHeader.tabsBorder：タブが有効な場合のエディターグループタイトルヘッダーの境界線の色。
editorGroup.emptyBackground：空のエディターグループの背景色。
editorGroup.focusedEmptyBorder：フォーカスされている空のエディターグループの境界線の色。
tab.activeBackground：アクティブなグループのアクティブなタブの背景色。
tab.unfocusedActiveBackground：非アクティブなエディターグループのアクティブなタブの背景色。
tab.activeForeground：アクティブグループのアクティブタブの前景色。
tab.border：タブを互いに区切るための境界線。
tab.activeBorder：アクティブなタブの下罫線。
tab.unfocusedActiveBorder：非アクティブなエディターグループのアクティブなタブの下枠。
tab.activeBorderTop：アクティブなタブの上境界線。
tab.unfocusedActiveBorderTop：非アクティブなエディターグループのアクティブなタブの上部の境界線
tab.inactiveBackground：非アクティブなタブの背景色。
tab.inactiveForeground：アクティブなグループの非アクティブなタブの前景色。
tab.unfocusedActiveForeground：非アクティブなエディターグループのアクティブなタブの前景色。
tab.unfocusedInactiveForeground：非アクティブなエディターグループの非アクティブなタブの前景色。
tab.hoverBackground：ホバリング時のタブの背景色
tab.unfocusedHoverBackground：ホバリング時のフォーカスのないグループのタブ背景色
tab.hoverBorder：ホバリング時にタブを強調表示する境界線
tab.unfocusedHoverBorder：ホバリング時にフォーカスのないグループのタブを強調表示する境界線
tab.activeModifiedBorder：アクティブなグループ内の変更された（ダーティな）アクティブなタブの上部の境界線。
tab.inactiveModifiedBorder：アクティブなグループ内の変更された（ダーティな）非アクティブなタブの上部の境界線。
tab.unfocusedActiveModifiedBorder：フォーカスされていないグループ内の変更された（ダーティな）アクティブなタブの上部の境界線。
tab.unfocusedInactiveModifiedBorder：フォーカスのないグループ内の変更された（ダーティな）非アクティブなタブの上部の境界線。
editorPane.background：中央のエディターレイアウトの左右に表示されるエディターペインの背景色。
```

# エディターの色
最も顕著なエディターの色は、構文の強調表示に使用されるトークンの色であり、インストールされている言語の文法に基づいています。これらの色は色テーマで定義されていますが、editor.tokenColorCustomizations設定でカスタマイズすることもできます。参照してくださいカラーテーマをカスタマイズカラーテーマと利用可能なトークンタイプの更新の詳細については。

他のすべてのエディターの色は次のとおりです。

```
editor.background：エディターの背景色。
editor.foreground：エディターのデフォルトの前景色。
editorLineNumber.foreground：エディターの行番号の色。
editorLineNumber.activeForeground：アクティブなエディターの行番号の色。
editorCursor.background：エディターカーソルの背景色。ブロックカーソルが重なる文字の色をカスタマイズできます。
editorCursor.foreground：エディターカーソルの色。
```

1つ以上の文字を選択すると、選択色が表示されます。選択に加えて、同じコンテンツを持つすべての地域も強調表示されます。

選択ハイライト

```
editor.selectionBackground：エディター選択の色。
editor.selectionForeground：選択したテキストの色をハイコントラストにします。
editor.inactiveSelectionBackground：非アクティブなエディターでの選択の色。下にある装飾を隠さないように、色は不透明であってはなりません。
editor.selectionHighlightBackground：選択範囲と同じ内容の地域の色。下にある装飾を隠さないように、色は不透明であってはなりません。
editor.selectionHighlightBorder：選択範囲と同じ内容の地域の境界線の色。
```

カーソルが記号または単語内にある場合、単語のハイライト色が表示されます。ファイルタイプで利用可能な言語サポートに応じて、一致するすべての参照と宣言が強調表示され、読み取りアクセスと書き込みアクセスが異なる色になります。ドキュメントシンボル言語のサポートが利用できない場合、これは単語の強調表示にフォールバックします。

# 発生

```
editor.wordHighlightBackground：読み取りアクセス中、たとえば変数の読み取り中のシンボルの背景色。下にある装飾を隠さないように、色は不透明であってはなりません。
editor.wordHighlightBorder：読み取りアクセス中、たとえば変数の読み取り中のシンボルの境界線の色。
editor.wordHighlightStrongBackground：変数への書き込み時など、書き込みアクセス中のシンボルの背景色。下にある装飾を隠さないように、色は不透明であってはなりません。
editor.wordHighlightStrongBorder：書き込みアクセス中、たとえば変数への書き込み中のシンボルの境界線の色。
```

検索色は、[検索/置換]ダイアログの現在の検索文字列によって異なります。

# 一致を見つける

```
editor.findMatchBackground：現在の検索一致の色。
editor.findMatchHighlightBackground：一致する他の検索の色。下にある装飾を隠さないように、色は不透明であってはなりません。
editor.findRangeHighlightBackground：検索を制限する範囲に色を付けます（検索ウィジェットで[選択範囲を検索]を有効にします）。下にある装飾を隠さないように、色は不透明であってはなりません。
editor.findMatchBorder：現在の検索一致の境界色。
editor.findMatchHighlightBorder：一致する他の検索の境界線の色。
editor.findRangeHighlightBorder：境界線は、検索を制限する範囲を色付けします（検索ウィジェットで[選択範囲を検索]を有効にします）。
```

ホバーが強調表示されているシンボルの後ろにホバーハイライトが表示されます。

# ホバーハイライト

```
editor.hoverHighlightBackground：ホバーが表示される単語の下の強調表示。下にある装飾を隠さないように、色は不透明であってはなりません。
```

現在の行は通常、背景の強調表示または境界線（両方ではない）として表示されます。

# 行のハイライト

```
editor.lineHighlightBackground：カーソル位置の行のハイライトの背景色。
editor.lineHighlightBorder：カーソル位置の線の周りの境界線の背景色。
```

リンクをクリックすると、リンクの色が表示されます。

リンク

```
editorLink.activeForeground：アクティブなリンクの色。
```

検索結果を選択すると、範囲のハイライトが表示されます。

範囲ハイライト

```
editor.rangeHighlightBackground：ハイライトされた範囲の背景色。クイックオープン、ファイル内のシンボル、検索機能で使用されます。下にある装飾を隠さないように、色は不透明であってはなりません。
editor.rangeHighlightBorder：ハイライトされた範囲の周囲の境界線の背景色。
エディターの空白を表示するには、[ 空白の切り替え]を有効にします。

editorWhitespace.foreground：エディター内の空白文字の色。
エディターのインデントガイドを表示するには、を設定し"editor.renderIndentGuides": trueます。

editorIndentGuide.background：エディターのインデントガイドの色。
editorIndentGuide.activeBackground：アクティブなエディターのインデントガイドの色。
エディタールーラーを表示するには、場所を定義します。 "editor.rulers"

editorRuler.foreground：エディター定規の色。
```

CodeLens：

# コードレンズ

editorCodeLens.foreground：エディターCodeLensの前景色。
ブラケット一致：

# ブラケット色

```
editorBracketMatch.background：一致する括弧の背景色。
editorBracketMatch.border：一致するブラケットボックスの色。
```

概要ルーラー：

このルーラーは、エディターの右端のスクロールバーの下にあり、エディターの装飾の概要を示します。

```
editorOverviewRuler.border：概要ルーラーの境界線の色。
editorOverviewRuler.findMatchForeground：検索一致の概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
editorOverviewRuler.rangeHighlightForeground：クイックオープン、ファイル内のシンボル、検索機能など、ハイライトされた範囲の概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
editorOverviewRuler.selectionHighlightForeground：選択ハイライトの概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
editorOverviewRuler.wordHighlightForeground：シンボルハイライトの概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
editorOverviewRuler.wordHighlightStrongForeground：書き込みアクセスシンボルハイライトの概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
editorOverviewRuler.modifiedForeground：変更されたコンテンツの概要ルーラーマーカーの色。
editorOverviewRuler.addedForeground：追加されたコンテンツの概要ルーラーマーカーの色。
editorOverviewRuler.deletedForeground：削除されたコンテンツの概要ルーラーマーカーの色。
editorOverviewRuler.errorForeground：エラーの概要ルーラーマーカーの色。
editorOverviewRuler.warningForeground：警告の概要ルーラーマーカーの色。
editorOverviewRuler.infoForeground：情報の概要ルーラーマーカーの色。
editorOverviewRuler.bracketMatchForeground：一致するブラケットの概要ルーラーマーカーの色。
```

# エラーと警告：

```
editorError.foreground：エディター内のエラー波線の前景色。
editorError.border：エディターのエラーボックスの境界線の色。
editorWarning.foreground：エディターの警告波線の前景色。
editorWarning.border：エディターの警告ボックスの境界色。
editorInfo.foreground：エディターでの情報の波線の前景色。
editorInfo.border：エディターの情報ボックスの境界線の色。
editorHint.foreground：エディターのヒントの前景色。
editorHint.border：エディターのヒントボックスの境界線の色。
```

# 未使用のソースコード：

```
editorUnnecessaryCode.border：エディターの不要な（未使用の）ソースコードの境界線の色。
editorUnnecessaryCode.opacity：エディター内の不必要な（未使用の）ソースコードの不透明度。たとえば、"#000000c0"75％の不透明度でコードをレンダリングします。ハイコントラストのテーマの場合、"editorUnnecessaryCode.border"テーマの色を使用して、不要なコードをフェードアウトする代わりに下線を引きます。
ガターには、グリフの余白と行番号が含まれます。

editorGutter.background：エディターのガターの背景色。ガターには、グリフの余白と行番号が含まれます。
editorGutter.modifiedBackground：変更された行のエディターのガターの背景色。
editorGutter.addedBackground：追加される行のエディターのガターの背景色。
editorGutter.deletedBackground：削除された行のエディターのガターの背景色。
```

# 差分エディターの色
挿入および削除されたテキストの色付けには、両方ではなく背景色または境界色のいずれかを使用します。

```
diffEditor.insertedTextBackground：挿入されたテキストの背景色。下にある装飾を隠さないように、色は不透明であってはなりません。
diffEditor.insertedTextBorder：挿入されたテキストのアウトラインカラー。
diffEditor.removedTextBackground：削除されたテキストの背景色。下にある装飾を隠さないように、色は不透明であってはなりません。
diffEditor.removedTextBorder：削除されたテキストのアウトラインカラー。
diffEditor.border：2つのテキストエディター間の境界線の色。
```

# エディターウィジェットの色
Editorウィジェットは、エディターのコンテンツの前に表示されます。例には、検索/置換ダイアログ、提案ウィジェット、およびエディターホバーがあります。

```
editorWidget.background：検索/置換などのエディターウィジェットの背景色。
editorWidget.border：ウィジェットに境界が含まれていないか、独自の境界色を定義していない限り、エディターウィジェットの境界色。
editorWidget.resizeBorder：エディターウィジェットのサイズ変更バーの境界線の色。色は、ウィジェットがサイズ変更境界線を持つことを選択し、色がウィジェットによってオーバーライドされない場合にのみ使用されます。
editorSuggestWidget.background：提案ウィジェットの背景色。
editorSuggestWidget.border：提案ウィジェットの境界線の色。
editorSuggestWidget.foreground：提案ウィジェットの前景色。
editorSuggestWidget.highlightForeground：候補ウィジェットの一致のハイライトの色。
editorSuggestWidget.selectedBackground：提案ウィジェットで選択したエントリの背景色。
editorHoverWidget.background：エディターのホバーの背景色。
editorHoverWidget.border：エディターのホバーの境界線の色。
```

デバッグ例外ウィジェットは、デバッグが例外で停止したときにエディターに表示されるピークビューです。

```
debugExceptionWidget.background：例外ウィジェットの背景色。
debugExceptionWidget.border：例外ウィジェットの境界線の色。
```
エディターのエラーと警告にナビゲートすると、エディターマーカービューに表示されます（[ 次のエラーまたは警告]コマンドに移動）。

```
editorMarkerNavigation.background：エディターマーカーナビゲーションウィジェットの背景。
editorMarkerNavigationError.background：エディターマーカーナビゲーションウィジェットのエラーの色。
editorMarkerNavigationWarning.background：エディターマーカーナビゲーションウィジェットの警告色。
editorMarkerNavigationInfo.background：エディターマーカーナビゲーションウィジェットの情報の色。
```

# ピークビューの色
ピークビューは、参照と宣言をエディター内のビューとして表示するために使用されます。

ピークビュー

```
peekView.border：ピークビューの境界線と矢印の色。
peekViewEditor.background：ピークビューエディターの背景色。
peekViewEditorGutter.background：ピークビューエディタのガターの背景色。
peekViewEditor.matchHighlightBackground：ピークビューエディターでハイライトカラーを一致させます。
peekViewEditor.matchHighlightBorder：ピークビューエディターで強調表示の境界線の色を一致させます。
peekViewResult.background：ピークビューの結果リストの背景色。
peekViewResult.fileForeground：ピークビューの結果リスト内のファイルノードの前景色。
peekViewResult.lineForeground：ピークビューの結果リストのラインノードの前景色。
peekViewResult.matchHighlightBackground：ピークビューの結果リストでハイライトの色と一致します。
peekViewResult.selectionBackground：プレビュービューの結果リストで選択したエントリの背景色。
peekViewResult.selectionForeground：プレビュービューの結果リストで選択したエントリの前景色。
peekViewTitle.background：ピークビューのタイトル領域の背景色。
peekViewTitleDescription.foreground：ピークビューのタイトル情報の色。
peekViewTitleLabel.foreground：ピークビュータイトルの色。
```

# 競合のマージ
エディターに特別なdiff範囲が含まれる場合、マージ競合の装飾が表示されます。

範囲をマージ

```
merge.currentHeaderBackground：インラインマージの競合における現在のヘッダーの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
merge.currentContentBackground：インラインマージの競合における現在のコンテンツの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
merge.incomingHeaderBackground：インラインマージの競合における着信ヘッダーの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
merge.incomingContentBackground：インラインマージの競合における着信コンテンツの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
merge.border：ヘッダーの境界線の色とインラインマージ競合のスプリッター。
merge.commonContentBackground：インラインマージ競合における共通の祖先コンテンツの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
merge.commonHeaderBackground：インラインmerge-conflictsの共通の祖先ヘッダーの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
editorOverviewRuler.currentContentForeground：インラインマージ競合の現在の概要ルーラー前景。
editorOverviewRuler.incomingContentForeground：インラインマージ競合の着信概要ルーラー前景。
editorOverviewRuler.commonContentForeground：インラインマージ競合の共通の祖先概要ルーラーの前景。
```

# パネル色
パネルはエディター領域の下に表示され、出力や統合ターミナルなどのビューが含まれています。

```
panel.background：パネルの背景色。
panel.border：パネルをエディターから分離するためのパネルの境界線の色。
panel.dropBackground：パネルタイトルアイテムのフィードバックカラーをドラッグアンドドロップします。色は透明である必要がありますので、パネルのエントリはまだ透けて見えます。
panelTitle.activeBorder：アクティブなパネルタイトルの境界線の色。
panelTitle.activeForeground：アクティブなパネルのタイトル色。
panelTitle.inactiveForeground：非アクティブなパネルのタイトル色。
```

# ステータスバーの色
ステータスバーは、ワークベンチの下部に表示されます。

```
statusBar.background：標準ステータスバーの背景色。
statusBar.foreground：ステータスバーの前景色。
statusBar.border：ステータスバーとエディターを分離するステータスバーの境界線の色。
statusBar.debuggingBackground：プログラムのデバッグ中のステータスバーの背景色。
statusBar.debuggingForeground：プログラムのデバッグ中のステータスバーの前景色。
statusBar.debuggingBorder：プログラムのデバッグ中にステータスバーとエディターを分離するステータスバーの境界線の色。
statusBar.noFolderForeground：フォルダーが開かれていないときのステータスバーの前景色。
statusBar.noFolderBackground：フォルダが開かれていないときのステータスバーの背景色。
statusBar.noFolderBorder：フォルダーが開かれていないときのステータスバーとエディターを分離するステータスバーの境界線の色。
statusBarItem.activeBackground：クリック時のステータスバー項目の背景色。
statusBarItem.hoverBackground：ホバリング時のステータスバー項目の背景色。
statusBarItem.prominentForeground：ステータスバーの目立つアイテムの前景色。
statusBarItem.prominentBackground：ステータスバーの目立つアイテムの背景色。
statusBarItem.prominentHoverBackground：ホバリング時のステータスバーの目立つアイテムの背景色。
```

重要なことを示すために、他のステータスバーのエントリよりも目立つアイテムが目立ちます。1つの例は、Toggle Tab Key Moves Focusコマンド変更モードインジケーターです。

# タイトルバーの色

```
titleBar.activeBackground：ウィンドウがアクティブなときのタイトルバーの背景。
titleBar.activeForeground：ウィンドウがアクティブなときのタイトルバーの前景。
titleBar.inactiveBackground：ウィンドウがアクティブでないときのタイトルバーの背景。
titleBar.inactiveForeground：ウィンドウがアクティブでないときのタイトルバーの前景。
titleBar.border：タイトルバーの境界線の色。
```

# メニューバーの色

```
menubar.selectionForeground：メニューバーで選択されたメニュー項目の前景色。
menubar.selectionBackground：メニューバーで選択されたメニュー項目の背景色。
menubar.selectionBorder：メニューバーで選択したメニュー項目の境界線の色。
menu.foreground：メニュー項目の前景色。
menu.background：メニュー項目の背景色。
menu.selectionForeground：メニューで選択されたメニュー項目の前景色。
menu.selectionBackground：メニューで選択されたメニュー項目の背景色。
menu.selectionBorder：メニューで選択されたメニュー項目の境界線の色。
menu.separatorBackground：メニュー内のセパレータメニュー項目の色。
```

通知の色
注：以下の色は、VS Codeバージョン1.21以降にのみ適用されます。

通知トーストは、ワークベンチの右下から上にスライドします。

通知トースト

通知センターで開くと、ヘッダー付きのリストに表示されます。

# 通知センター

```
notificationCenter.border：通知センターの境界線の色。
notificationCenterHeader.foreground：通知センターのヘッダーの前景色。
notificationCenterHeader.background：通知センターのヘッダーの背景色。
notificationToast.border：通知トーストの境界線の色。
notifications.foreground：通知の前景色。
notifications.background：通知の背景色。
notifications.border：通知センターの他の通知と区別する通知境界線の色。
notificationLink.foreground：通知リンクの前景色。
1.21（2018年2月）リリースより前のVS Codeバージョンを対象とする場合、これらは古い（サポートされなくなった）色です。

notification.background
notification.foreground
notification.buttonBackground
notification.buttonForeground
notification.buttonHoverBackground
notification.errorBackground
notification.errorForeground
notification.infoBackground
notification.infoForeground
notification.warningBackground
notification.warningForeground
```

# 拡張機能

```
extensionButton.prominentForeground：拡張ビューボタンの前景色（たとえば、インストールボタン）。
extensionButton.prominentBackground：拡張表示ボタンの背景色。
extensionButton.prominentHoverBackground：拡張表示ボタンの背景ホバーカラー。
```

# クイックピッカー

```
pickerGroup.border：境界線をグループ化するためのクイックピッカー（クイックオープン）色。
pickerGroup.foreground：ラベルをグループ化するためのクイックピッカー（クイックオープン）色。
```

# 統合ターミナルの色

```
terminal.background：統合ターミナルのビューポートの背景。
terminal.border：ターミナル内の分割ペインを区切る境界線の色。デフォルトはpanel.borderです。
terminal.foreground：統合端末のデフォルトの前景色。
terminal.ansiBlack：端末の「黒」ANSIカラー。
terminal.ansiBlue：ターミナルの「青色」ANSI色。
terminal.ansiBrightBlack：ターミナルの「BrightBlack」ANSIカラー。
terminal.ansiBrightBlue：ターミナルの「BrightBlue」ANSIカラー。
terminal.ansiBrightCyan：端末の 'BrightCyan' ANSIカラー。
terminal.ansiBrightGreen：端末の「BrightGreen」ANSIカラー。
terminal.ansiBrightMagenta：ターミナルの「BrightMagenta」ANSIカラー。
terminal.ansiBrightRed：ターミナルの「BrightRed」ANSIカラー。
terminal.ansiBrightWhite：端末の 'BrightWhite' ANSIカラー。
terminal.ansiBrightYellow：ターミナルの「明るい黄色」ANSI色。
terminal.ansiCyan：ターミナルの「シアン」ANSIカラー。
terminal.ansiGreen：ターミナルの「グリーン」ANSI色。
terminal.ansiMagenta：ターミナルの「マゼンタ」ANSIカラー。
terminal.ansiRed：ターミナルの「赤」ANSI色。
terminal.ansiWhite：ターミナルの「白」ANSI色。
terminal.ansiYellow：端末の「黄色」のANSIカラー。
terminal.selectionBackground：ターミナルの選択背景色。
terminalCursor.background：ターミナルカーソルの背景色。ブロックカーソルが重なる文字の色をカスタマイズできます。
terminalCursor.foreground：ターミナルカーソルの前景色。
```

# デバッグ

```
debugToolBar.background：ツールバーの背景色をデバッグします。
debugToolBar.border：ツールバーの境界線の色をデバッグします。
editor.stackFrameHighlightBackground：エディターの一番上のスタックフレームのハイライトの背景色。
editor.focusedStackFrameHighlightBackground：エディター内のフォーカスされたスタックフレームハイライトの背景色。
```

# ようこそページ

```
welcomePage.background：ようこそページの背景色。
welcomePage.buttonBackground：ようこそページのボタンの背景色。
welcomePage.buttonHoverBackground：[ようこそ]ページのボタンの背景色をホバーします。
walkThrough.embeddedEditorBackground：インタラクティブプレイグラウンドの埋め込みエディターの背景色。
```

Gitカラー

```
gitDecoration.addedResourceForeground：追加されたGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
gitDecoration.modifiedResourceForeground：変更されたGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
gitDecoration.deletedResourceForeground：削除されたGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
gitDecoration.untrackedResourceForeground：追跡されていないGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
gitDecoration.ignoredResourceForeground：無視されたGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
gitDecoration.conflictingResourceForeground：競合するGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
gitDecoration.submoduleResourceForeground：サブモジュールリソースの色。
設定エディターの色
注：これらの色は、Preferences: Open Settings (UI)コマンドで開くことができるGUI設定エディター用です。

settings.headerForeground：セクションヘッダーまたはアクティブなタイトルの前景色。
settings.modifiedItemIndicator：変更された設定を示す行。
settings.dropdownBackground：ドロップダウンの背景。
settings.dropdownForeground：ドロップダウンの前景。
settings.dropdownBorder：ドロップダウンボーダー。
settings.dropdownListBorder：ドロップダウンリストの境界線。
settings.checkboxBackground：チェックボックスの背景。
settings.checkboxForeground：チェックボックスの前景。
settings.checkboxBorder：チェックボックスの境界線。
settings.textInputBackground：テキスト入力ボックスの背景。
settings.textInputForeground：テキスト入力ボックスの前景。
settings.textInputBorder：テキスト入力ボックスの境界線。
settings.numberInputBackground：数値入力ボックスの背景。
settings.numberInputForeground：数字入力ボックスの前景。
settings.numberInputBorder：数値入力ボックスの境界線。
```

# パンくずリスト
パンくずリストナビゲーションのテーマの色：

```
breadcrumb.foreground：パンくずリストのアイテムの色。
breadcrumb.background：パンくずリストの背景色。
breadcrumb.focusForeground：フォーカスされたパンくずリストの色。
breadcrumb.activeSelectionForeground：選択したパンくずリストの色。
breadcrumbPicker.background：パンくずリストピッカーの背景色。
```

# スニペット
スニペットのテーマの色：

```
editor.snippetTabstopHighlightBackground：スニペットタブストップの背景色を強調表示します。
editor.snippetTabstopHighlightBorder：スニペットタブストップの境界線の色を強調表示します。
editor.snippetFinalTabstopHighlightBackground：スニペットの最後のタブストップの背景色を強調表示します。
editor.snippetFinalTabstopHighlightBorder：スニペットの最後のタブストップの境界線の色を強調表示します。
```
