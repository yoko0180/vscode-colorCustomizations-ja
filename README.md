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

- [コントラスト色](#コントラスト色)
- [ベースカラー](#ベースカラー)
- [テキストの色](#テキストの色)
- [ボタンコントロール](#ボタンコントロール)
- [ドロップダウン制御](#ドロップダウン制御)
- [入力制御](#入力制御)
- [スクロールバーコントロール](#スクロールバーコントロール)
- [バッジ](#バッジ)
- [プログレスバー](#プログレスバー)
- [リストとツリー](#リストとツリー)
- [アクティビティバー](#アクティビティバー)
- [サイドバー](#サイドバー)
- [ミニマップ](#ミニマップ)
- [エディターの色](#エディターの色)
- [発生](#発生)
- [一致を見つける](#一致を見つける)
- [ホバーハイライト](#ホバーハイライト)
- [行のハイライト](#行のハイライト)
- [コードレンズ](#コードレンズ)
- [ブラケット色](#ブラケット色)
- [エラーと警告：](#エラーと警告：)
- [未使用のソースコード：](#未使用のソースコード：)
- [差分エディターの色](#差分エディターの色)
- [エディターウィジェットの色](#エディターウィジェットの色)
- [ピークビューの色](#ピークビューの色)
- [競合のマージ](#競合のマージ)
- [パネル色](#パネル色)
- [ステータスバーの色](#ステータスバーの色)
- [タイトルバーの色](#タイトルバーの色)
- [メニューバーの色](#メニューバーの色)
- [通知の色](#通知の色)
- [拡張機能](#拡張機能)
- [クイックピッカー](#クイックピッカー)
- [統合ターミナルの色](#統合ターミナルの色)
- [デバッグ](#デバッグ)
- [ようこそページ](#ようこそページ)
- [パンくずリスト](#パンくずリスト)
- [スニペット](#スニペット)


# コントラスト色
通常、コントラストの色は、コントラストの高いテーマにのみ設定されます。設定すると、UI全体のアイテムの周囲に追加の境界線が追加され、コントラストが向上します。

```javascript
"contrastActiveBorder":"#ff0000", // アクティブな要素の周囲に余分な境界線を追加し、他の要素と区別してコントラストを高めます。
"contrastBorder":"#ff0000", // 要素を囲む余分な境界線で、要素を他と区別してコントラストを高めます。
```

# ベースカラー

```javascript
"focusBorder":"#ff0000", // フォーカスされた要素の全体的な境界線の色。この色は、コンポーネントによってオーバーライドされない場合にのみ使用されます。
"foreground":"#ff0000", // 全体的な前景色。この色は、コンポーネントによってオーバーライドされない場合にのみ使用されます。
"widget.shadow":"#ff0000", // エディター内の検索/置換などのウィジェットの影の色。
"selection.background":"#ff0000", // ワークベンチ内のテキスト選択の背景色（入力フィールドまたはテキスト領域の場合、エディターおよびターミナル内の選択には適用されません）。
"descriptionForeground":"#ff0000", // ラベルなどの追加情報を提供する説明テキストの前景色。
"errorForeground":"#ff0000", // エラーメッセージの全体的な前景色（この色は、コンポーネントによってオーバーライドされない場合にのみ使用されます）。
```

# テキストの色
ウェルカムページなどのテキストドキュメント内の色。

```javascript
"textBlockQuote.background":"#ff0000", // テキスト内のブロック引用の背景色。
"textBlockQuote.border":"#ff0000", // テキスト内のブロック引用の境界線の色。
"textCodeBlock.background":"#ff0000", // テキストのコードブロックの背景色。
"textLink.activeForeground":"#ff0000", // マウスのホバーをクリックしたときのテキスト内のリンクの前景色。
"textLink.foreground":"#ff0000", // テキスト内のリンクの前景色。
"textPreformat.foreground":"#ff0000", // 事前にフォーマットされたテキストセグメントの前景色。
"textSeparator.foreground":"#ff0000", // テキスト区切りの色。
```

# ボタンコントロール
新しいウィンドウのエクスプローラーの[フォルダーを開く ]ボタンなどのボタンウィジェットの色のセット。

```javascript
"button.background":"#ff0000", // ボタンの背景色。
"button.foreground":"#ff0000", // ボタンの前景色。
"button.hoverBackground":"#ff0000", // ホバリング時のボタンの背景色。
```

# ドロップダウン制御
統合ターミナルや出力パネルなど、すべてのドロップダウンウィジェットの色のセット。現在、ドロップダウンコントロールはmacOSでは使用されていないことに注意してください。

```
"dropdown.background":"#ff0000", // ドロップダウンの背景。
"dropdown.listBackground":"#ff0000", // ドロップダウンリストの背景。
"dropdown.border":"#ff0000", // ドロップダウンボーダー。
"dropdown.foreground":"#ff0000", // ドロップダウンの前景。
```

# 入力制御
[検索]ビューや[検索/置換]ダイアログなどの入力コントロールの色。

```
"input.background":"#ff0000", // 入力ボックスの背景。
"input.border":"#ff0000", // 入力ボックスの境界線。
"input.foreground":"#ff0000", // 入力ボックスの前景。
"input.placeholderForeground":"#ff0000", // プレースホルダーテキストの入力ボックスの前景色。
"inputOption.activeBackground":"#ff0000", // 入力フィールドのアクティブ化されたオプションの背景色。
"inputOption.activeBorder":"#ff0000", // 入力フィールドのアクティブ化されたオプションの境界線の色。
"inputValidation.errorBackground":"#ff0000", // エラーの重大度の入力検証背景色。
"inputValidation.errorForeground":"#ff0000", // エラーの重大度の入力検証前景色。
"inputValidation.errorBorder":"#ff0000", // エラーの重大度の入力検証境界色。
"inputValidation.infoBackground":"#ff0000", // 情報の重大度の入力検証背景色。
"inputValidation.infoForeground":"#ff0000", // 情報の重要度の入力検証前景色。
"inputValidation.infoBorder":"#ff0000", // 情報の重大度の入力検証境界色。
"inputValidation.warningBackground":"#ff0000", // 情報警告用の入力検証背景色。
"inputValidation.warningForeground":"#ff0000", // 警告の重大​​度の入力検証前景色。
"inputValidation.warningBorder":"#ff0000", // 警告の重大​​度の入力検証境界線の色。
```

# スクロールバーコントロール

```
"scrollbar.shadow":"#ff0000", // ビューがスクロールされていることを示すスクロールバースライダーの影。
"scrollbarSlider.activeBackground":"#ff0000", // クリックしたときのスクロールバースライダーの背景色。
"scrollbarSlider.background":"#ff0000", // スクロールバースライダーの背景色。
"scrollbarSlider.hoverBackground":"#ff0000", // ホバー時のスクロールバースライダーの背景色。
```

# バッジ
バッジは、検索結果の数などの小さな情報ラベルです。

```
"badge.foreground":"#ff0000", // バッジの前景色。
"badge.background":"#ff0000", // バッジの背景色。
```

# プログレスバー

```
"progressBar.background":"#ff0000", // 長時間実行される操作に対して表示される進行状況バーの背景色。
```

# リストとツリー
ファイルエクスプローラーのようなリストとツリーの色。アクティブリスト/ツリーにはキーボードフォーカスがあり、非アクティブリストにはありません。

```
"list.activeSelectionBackground":"#ff0000", // リスト/ツリーがアクティブなときの選択されたアイテムのリスト/ツリーの背景色。
"list.activeSelectionForeground":"#ff0000", // リスト/ツリーがアクティブなときの選択されたアイテムのリスト/ツリーの前景色。
"list.dropBackground":"#ff0000", // マウスを使用してアイテムを移動するときのリスト/ツリーの背景のドラッグアンドドロップ。
"list.focusBackground":"#ff0000", // リスト/ツリーがアクティブなときのフォーカスされたアイテムのリスト/ツリーの背景色。
"list.focusForeground":"#ff0000", // リスト/ツリーがアクティブなときのフォーカスされたアイテムのリスト/ツリーの前景色。アクティブリスト/ツリーにはキーボードフォーカスがあり、非アクティブリストにはありません。
"list.highlightForeground":"#ff0000", // リスト/ツリー内を検索するときに一致するハイライトのリスト/ツリーの前景色。
"list.hoverBackground":"#ff0000", // マウスを使用してアイテムの上にマウスを移動したときのリスト/ツリーの背景。
"list.hoverForeground":"#ff0000", // マウスを使用してアイテムの上にマウスを移動したときのリスト/ツリーの前景。
"list.inactiveSelectionBackground":"#ff0000", // リスト/ツリーが非アクティブのときの選択されたアイテムのリスト/ツリーの背景色。
"list.inactiveSelectionForeground":"#ff0000", // リスト/ツリーが非アクティブのときの選択されたアイテムのリスト/ツリーの前景色。アクティブリスト/ツリーにはキーボードフォーカスがあり、非アクティブリストにはありません。
"list.inactiveFocusBackground":"#ff0000", // リストがアクティブでないときのフォーカスされたアイテムのリストの背景色。アクティブリストにはキーボードフォーカスがあり、非アクティブリストにはありません。現在、リストでのみサポートされています。
"list.invalidItemForeground":"#ff0000", // エクスプローラーの未解決のルートなど、無効なアイテムのリスト/ツリーの前景色。
"list.errorForeground":"#ff0000", // エラーを含むリストアイテムの前景色。
"list.warningForeground":"#ff0000", // 警告を含むリストアイテムの前景色。
"listFilterWidget.background":"#ff0000", // リスト/ツリー内を検索するときに、入力したテキストのリスト/ツリーフィルターの背景色。
"listFilterWidget.outline":"#ff0000", // リスト/ツリー内を検索するときのリスト/ツリーフィルターウィジェットの入力テキストのアウトラインカラー。
"listFilterWidget.noMatchesOutline":"#ff0000", // リスト/ツリー内を検索するときに、入力したテキストに一致するものが見つからない場合のリスト/ツリーフィルターウィジェットのアウトラインカラー。
"tree.indentGuidesStroke":"#ff0000", // ツリーウィジェットのインデントガイドのストロークの色。
```

# アクティビティバー
アクティビティバーはワークベンチの左端または右端に表示され、サイドバーのビューをすばやく切り替えることができます。

```
"activityBar.background":"#ff0000", // アクティビティバーの背景色。
"activityBar.dropBackground":"#ff0000", // アクティビティバーのアイテムのフィードバックカラーをドラッグアンドドロップします。
"activityBar.foreground":"#ff0000", // アクティビティバーの前景色（たとえば、アイコンに使用）。
"activityBar.inactiveForeground":"#ff0000", // アクティブでないときのアクティビティバー項目の前景色。
"activityBar.border":"#ff0000", // アクティビティバーの境界線の色とサイドバー。
"activityBarBadge.background":"#ff0000", // アクティビティ通知バッジの背景色。
"activityBarBadge.foreground":"#ff0000", // アクティビティ通知バッジの前景色。
```

# サイドバー
サイドバーには、エクスプローラーや検索などのビューが含まれています。

```
"sideBar.background":"#ff0000", // サイドバーの背景色。
"sideBar.foreground":"#ff0000", // サイドバーの前景色。サイドバーは、エクスプローラーや検索などのビューのコンテナーです。
"sideBar.border":"#ff0000", // エディターを分離するサイドのサイドバーの境界線の色。
"sideBar.dropBackground":"#ff0000", // サイドバーセクションのフィードバックカラーをドラッグアンドドロップします。サイドバーのセクションがまだ透けて見えるように、色には透明性が必要です。サイドバーは、エクスプローラーや検索などのビューのコンテナーです。
"sideBarTitle.foreground":"#ff0000", // サイドバーのタイトルの前景色。
"sideBarSectionHeader.background":"#ff0000", // サイドバーセクションヘッダーの背景色。
"sideBarSectionHeader.foreground":"#ff0000", // サイドバーセクションヘッダーの前景色。
"sideBarSectionHeader.border":"#ff0000", // サイドバーセクションヘッダーの境界線の色。
```

# ミニマップ
ミニマップには、現在のファイルの縮小バージョンが表示されます。

```
"minimap.findMatchHighlight":"#ff0000", // ファイル内の検索からの一致のハイライト色
```

エディターグループとタブ
エディタグループは、エディタのコンテナです。多くの編集者グループが存在する可能性があります。タブはエディターのコンテナーです。1つのエディターグループで複数のタブを開くことができます。

```
"editorGroup.border":"#ff0000", // 複数のエディターグループを互いに分離する色。
"editorGroup.dropBackground":"#ff0000", // エディターをドラッグするときの背景色。
"editorGroupHeader.noTabsBackground":"#ff0000", // タブが無効（設定"workbench.editor.showTabs": false）の場合のエディターグループタイトルヘッダーの背景色。
"editorGroupHeader.tabsBackground":"#ff0000", // Tabsコンテナの背景色。
"editorGroupHeader.tabsBorder":"#ff0000", // タブが有効な場合のエディターグループタイトルヘッダーの境界線の色。
"editorGroup.emptyBackground":"#ff0000", // 空のエディターグループの背景色。
"editorGroup.focusedEmptyBorder":"#ff0000", // フォーカスされている空のエディターグループの境界線の色。
"tab.activeBackground":"#ff0000", // アクティブなグループのアクティブなタブの背景色。
"tab.unfocusedActiveBackground":"#ff0000", // 非アクティブなエディターグループのアクティブなタブの背景色。
"tab.activeForeground":"#ff0000", // アクティブグループのアクティブタブの前景色。
"tab.border":"#ff0000", // タブを互いに区切るための境界線。
"tab.activeBorder":"#ff0000", // アクティブなタブの下罫線。
"tab.unfocusedActiveBorder":"#ff0000", // 非アクティブなエディターグループのアクティブなタブの下枠。
"tab.activeBorderTop":"#ff0000", // アクティブなタブの上境界線。
"tab.unfocusedActiveBorderTop":"#ff0000", // 非アクティブなエディターグループのアクティブなタブの上部の境界線
"tab.inactiveBackground":"#ff0000", // 非アクティブなタブの背景色。
"tab.inactiveForeground":"#ff0000", // アクティブなグループの非アクティブなタブの前景色。
"tab.unfocusedActiveForeground":"#ff0000", // 非アクティブなエディターグループのアクティブなタブの前景色。
"tab.unfocusedInactiveForeground":"#ff0000", // 非アクティブなエディターグループの非アクティブなタブの前景色。
"tab.hoverBackground":"#ff0000", // ホバリング時のタブの背景色
"tab.unfocusedHoverBackground":"#ff0000", // ホバリング時のフォーカスのないグループのタブ背景色
"tab.hoverBorder":"#ff0000", // ホバリング時にタブを強調表示する境界線
"tab.unfocusedHoverBorder":"#ff0000", // ホバリング時にフォーカスのないグループのタブを強調表示する境界線
"tab.activeModifiedBorder":"#ff0000", // アクティブなグループ内の変更された（ダーティな）アクティブなタブの上部の境界線。
"tab.inactiveModifiedBorder":"#ff0000", // アクティブなグループ内の変更された（ダーティな）非アクティブなタブの上部の境界線。
"tab.unfocusedActiveModifiedBorder":"#ff0000", // フォーカスされていないグループ内の変更された（ダーティな）アクティブなタブの上部の境界線。
"tab.unfocusedInactiveModifiedBorder":"#ff0000", // フォーカスのないグループ内の変更された（ダーティな）非アクティブなタブの上部の境界線。
"editorPane.background":"#ff0000", // 中央のエディターレイアウトの左右に表示されるエディターペインの背景色。
```

# エディターの色
最も顕著なエディターの色は、構文の強調表示に使用されるトークンの色であり、インストールされている言語の文法に基づいています。これらの色は色テーマで定義されていますが、editor.tokenColorCustomizations設定でカスタマイズすることもできます。参照してくださいカラーテーマをカスタマイズカラーテーマと利用可能なトークンタイプの更新の詳細については。

他のすべてのエディターの色は次のとおりです。

```
"editor.background":"#ff0000", // エディターの背景色。
"editor.foreground":"#ff0000", // エディターのデフォルトの前景色。
"editorLineNumber.foreground":"#ff0000", // エディターの行番号の色。
"editorLineNumber.activeForeground":"#ff0000", // アクティブなエディターの行番号の色。
"editorCursor.background":"#ff0000", // エディターカーソルの背景色。ブロックカーソルが重なる文字の色をカスタマイズできます。
"editorCursor.foreground":"#ff0000", // エディターカーソルの色。
```

1つ以上の文字を選択すると、選択色が表示されます。選択に加えて、同じコンテンツを持つすべての地域も強調表示されます。

選択ハイライト

```
"editor.selectionBackground":"#ff0000", // エディター選択の色。
"editor.selectionForeground":"#ff0000", // 選択したテキストの色をハイコントラストにします。
"editor.inactiveSelectionBackground":"#ff0000", // 非アクティブなエディターでの選択の色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editor.selectionHighlightBackground":"#ff0000", // 選択範囲と同じ内容の地域の色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editor.selectionHighlightBorder":"#ff0000", // 選択範囲と同じ内容の地域の境界線の色。
```

カーソルが記号または単語内にある場合、単語のハイライト色が表示されます。ファイルタイプで利用可能な言語サポートに応じて、一致するすべての参照と宣言が強調表示され、読み取りアクセスと書き込みアクセスが異なる色になります。ドキュメントシンボル言語のサポートが利用できない場合、これは単語の強調表示にフォールバックします。

# 発生

```
"editor.wordHighlightBackground":"#ff0000", // 読み取りアクセス中、たとえば変数の読み取り中のシンボルの背景色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editor.wordHighlightBorder":"#ff0000", // 読み取りアクセス中、たとえば変数の読み取り中のシンボルの境界線の色。
"editor.wordHighlightStrongBackground":"#ff0000", // 変数への書き込み時など、書き込みアクセス中のシンボルの背景色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editor.wordHighlightStrongBorder":"#ff0000", // 書き込みアクセス中、たとえば変数への書き込み中のシンボルの境界線の色。
```

検索色は、[検索/置換]ダイアログの現在の検索文字列によって異なります。

# 一致を見つける

```
"editor.findMatchBackground":"#ff0000", // 現在の検索一致の色。
"editor.findMatchHighlightBackground":"#ff0000", // 一致する他の検索の色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editor.findRangeHighlightBackground":"#ff0000", // 検索を制限する範囲に色を付けます（検索ウィジェットで[選択範囲を検索]を有効にします）。下にある装飾を隠さないように、色は不透明であってはなりません。
"editor.findMatchBorder":"#ff0000", // 現在の検索一致の境界色。
"editor.findMatchHighlightBorder":"#ff0000", // 一致する他の検索の境界線の色。
"editor.findRangeHighlightBorder":"#ff0000", // 境界線は、検索を制限する範囲を色付けします（検索ウィジェットで[選択範囲を検索]を有効にします）。
```

ホバーが強調表示されているシンボルの後ろにホバーハイライトが表示されます。

# ホバーハイライト

```
"editor.hoverHighlightBackground":"#ff0000", // ホバーが表示される単語の下の強調表示。下にある装飾を隠さないように、色は不透明であってはなりません。
```

現在の行は通常、背景の強調表示または境界線（両方ではない）として表示されます。

# 行のハイライト

```
"editor.lineHighlightBackground":"#ff0000", // カーソル位置の行のハイライトの背景色。
"editor.lineHighlightBorder":"#ff0000", // カーソル位置の線の周りの境界線の背景色。
```

リンクをクリックすると、リンクの色が表示されます。

リンク

```
"editorLink.activeForeground":"#ff0000", // アクティブなリンクの色。
```

検索結果を選択すると、範囲のハイライトが表示されます。

範囲ハイライト

```
"editor.rangeHighlightBackground":"#ff0000", // ハイライトされた範囲の背景色。クイックオープン、ファイル内のシンボル、検索機能で使用されます。下にある装飾を隠さないように、色は不透明であってはなりません。
"editor.rangeHighlightBorder":"#ff0000", // ハイライトされた範囲の周囲の境界線の背景色。
エディターの空白を表示するには、[ 空白の切り替え]を有効にします。

"editorWhitespace.foreground":"#ff0000", // エディター内の空白文字の色。
エディターのインデントガイドを表示するには、を設定し"editor.renderIndentGuides": trueます。

"editorIndentGuide.background":"#ff0000", // エディターのインデントガイドの色。
"editorIndentGuide.activeBackground":"#ff0000", // アクティブなエディターのインデントガイドの色。
エディタールーラーを表示するには、場所を定義します。 "editor.rulers"

"editorRuler.foreground":"#ff0000", // エディター定規の色。
```

CodeLens：

# コードレンズ

"editorCodeLens.foreground":"#ff0000", // エディターCodeLensの前景色。
ブラケット一致：

# ブラケット色

```
"editorBracketMatch.background":"#ff0000", // 一致する括弧の背景色。
"editorBracketMatch.border":"#ff0000", // 一致するブラケットボックスの色。
```

概要ルーラー：

このルーラーは、エディターの右端のスクロールバーの下にあり、エディターの装飾の概要を示します。

```
"editorOverviewRuler.border":"#ff0000", // 概要ルーラーの境界線の色。
"editorOverviewRuler.findMatchForeground":"#ff0000", // 検索一致の概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editorOverviewRuler.rangeHighlightForeground":"#ff0000", // クイックオープン、ファイル内のシンボル、検索機能など、ハイライトされた範囲の概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editorOverviewRuler.selectionHighlightForeground":"#ff0000", // 選択ハイライトの概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editorOverviewRuler.wordHighlightForeground":"#ff0000", // シンボルハイライトの概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editorOverviewRuler.wordHighlightStrongForeground":"#ff0000", // 書き込みアクセスシンボルハイライトの概要ルーラーマーカーの色。下にある装飾を隠さないように、色は不透明であってはなりません。
"editorOverviewRuler.modifiedForeground":"#ff0000", // 変更されたコンテンツの概要ルーラーマーカーの色。
"editorOverviewRuler.addedForeground":"#ff0000", // 追加されたコンテンツの概要ルーラーマーカーの色。
"editorOverviewRuler.deletedForeground":"#ff0000", // 削除されたコンテンツの概要ルーラーマーカーの色。
"editorOverviewRuler.errorForeground":"#ff0000", // エラーの概要ルーラーマーカーの色。
"editorOverviewRuler.warningForeground":"#ff0000", // 警告の概要ルーラーマーカーの色。
"editorOverviewRuler.infoForeground":"#ff0000", // 情報の概要ルーラーマーカーの色。
"editorOverviewRuler.bracketMatchForeground":"#ff0000", // 一致するブラケットの概要ルーラーマーカーの色。
```

# エラーと警告：

```
"editorError.foreground":"#ff0000", // エディター内のエラー波線の前景色。
"editorError.border":"#ff0000", // エディターのエラーボックスの境界線の色。
"editorWarning.foreground":"#ff0000", // エディターの警告波線の前景色。
"editorWarning.border":"#ff0000", // エディターの警告ボックスの境界色。
"editorInfo.foreground":"#ff0000", // エディターでの情報の波線の前景色。
"editorInfo.border":"#ff0000", // エディターの情報ボックスの境界線の色。
"editorHint.foreground":"#ff0000", // エディターのヒントの前景色。
"editorHint.border":"#ff0000", // エディターのヒントボックスの境界線の色。
```

# 未使用のソースコード：

```
"editorUnnecessaryCode.border":"#ff0000", // エディターの不要な（未使用の）ソースコードの境界線の色。
"editorUnnecessaryCode.opacity":"#ff0000", // エディター内の不必要な（未使用の）ソースコードの不透明度。たとえば、"#000000c0"75％の不透明度でコードをレンダリングします。ハイコントラストのテーマの場合、"editorUnnecessaryCode.border"テーマの色を使用して、不要なコードをフェードアウトする代わりに下線を引きます。
ガターには、グリフの余白と行番号が含まれます。

"editorGutter.background":"#ff0000", // エディターのガターの背景色。ガターには、グリフの余白と行番号が含まれます。
"editorGutter.modifiedBackground":"#ff0000", // 変更された行のエディターのガターの背景色。
"editorGutter.addedBackground":"#ff0000", // 追加される行のエディターのガターの背景色。
"editorGutter.deletedBackground":"#ff0000", // 削除された行のエディターのガターの背景色。
```

# 差分エディターの色
挿入および削除されたテキストの色付けには、両方ではなく背景色または境界色のいずれかを使用します。

```
"diffEditor.insertedTextBackground":"#ff0000", // 挿入されたテキストの背景色。下にある装飾を隠さないように、色は不透明であってはなりません。
"diffEditor.insertedTextBorder":"#ff0000", // 挿入されたテキストのアウトラインカラー。
"diffEditor.removedTextBackground":"#ff0000", // 削除されたテキストの背景色。下にある装飾を隠さないように、色は不透明であってはなりません。
"diffEditor.removedTextBorder":"#ff0000", // 削除されたテキストのアウトラインカラー。
"diffEditor.border":"#ff0000", // 2つのテキストエディター間の境界線の色。
```

# エディターウィジェットの色
Editorウィジェットは、エディターのコンテンツの前に表示されます。例には、検索/置換ダイアログ、提案ウィジェット、およびエディターホバーがあります。

```
"editorWidget.background":"#ff0000", // 検索/置換などのエディターウィジェットの背景色。
"editorWidget.border":"#ff0000", // ウィジェットに境界が含まれていないか、独自の境界色を定義していない限り、エディターウィジェットの境界色。
"editorWidget.resizeBorder":"#ff0000", // エディターウィジェットのサイズ変更バーの境界線の色。色は、ウィジェットがサイズ変更境界線を持つことを選択し、色がウィジェットによってオーバーライドされない場合にのみ使用されます。
"editorSuggestWidget.background":"#ff0000", // 提案ウィジェットの背景色。
"editorSuggestWidget.border":"#ff0000", // 提案ウィジェットの境界線の色。
"editorSuggestWidget.foreground":"#ff0000", // 提案ウィジェットの前景色。
"editorSuggestWidget.highlightForeground":"#ff0000", // 候補ウィジェットの一致のハイライトの色。
"editorSuggestWidget.selectedBackground":"#ff0000", // 提案ウィジェットで選択したエントリの背景色。
"editorHoverWidget.background":"#ff0000", // エディターのホバーの背景色。
"editorHoverWidget.border":"#ff0000", // エディターのホバーの境界線の色。
```

デバッグ例外ウィジェットは、デバッグが例外で停止したときにエディターに表示されるピークビューです。

```
"debugExceptionWidget.background":"#ff0000", // 例外ウィジェットの背景色。
"debugExceptionWidget.border":"#ff0000", // 例外ウィジェットの境界線の色。
```
エディターのエラーと警告にナビゲートすると、エディターマーカービューに表示されます（[ 次のエラーまたは警告]コマンドに移動）。

```
"editorMarkerNavigation.background":"#ff0000", // エディターマーカーナビゲーションウィジェットの背景。
"editorMarkerNavigationError.background":"#ff0000", // エディターマーカーナビゲーションウィジェットのエラーの色。
"editorMarkerNavigationWarning.background":"#ff0000", // エディターマーカーナビゲーションウィジェットの警告色。
"editorMarkerNavigationInfo.background":"#ff0000", // エディターマーカーナビゲーションウィジェットの情報の色。
```

# ピークビューの色
ピークビューは、参照と宣言をエディター内のビューとして表示するために使用されます。

ピークビュー

```
"peekView.border":"#ff0000", // ピークビューの境界線と矢印の色。
"peekViewEditor.background":"#ff0000", // ピークビューエディターの背景色。
"peekViewEditorGutter.background":"#ff0000", // ピークビューエディタのガターの背景色。
"peekViewEditor.matchHighlightBackground":"#ff0000", // ピークビューエディターでハイライトカラーを一致させます。
"peekViewEditor.matchHighlightBorder":"#ff0000", // ピークビューエディターで強調表示の境界線の色を一致させます。
"peekViewResult.background":"#ff0000", // ピークビューの結果リストの背景色。
"peekViewResult.fileForeground":"#ff0000", // ピークビューの結果リスト内のファイルノードの前景色。
"peekViewResult.lineForeground":"#ff0000", // ピークビューの結果リストのラインノードの前景色。
"peekViewResult.matchHighlightBackground":"#ff0000", // ピークビューの結果リストでハイライトの色と一致します。
"peekViewResult.selectionBackground":"#ff0000", // プレビュービューの結果リストで選択したエントリの背景色。
"peekViewResult.selectionForeground":"#ff0000", // プレビュービューの結果リストで選択したエントリの前景色。
"peekViewTitle.background":"#ff0000", // ピークビューのタイトル領域の背景色。
"peekViewTitleDescription.foreground":"#ff0000", // ピークビューのタイトル情報の色。
"peekViewTitleLabel.foreground":"#ff0000", // ピークビュータイトルの色。
```

# 競合のマージ
エディターに特別なdiff範囲が含まれる場合、マージ競合の装飾が表示されます。

範囲をマージ

```
"merge.currentHeaderBackground":"#ff0000", // インラインマージの競合における現在のヘッダーの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
"merge.currentContentBackground":"#ff0000", // インラインマージの競合における現在のコンテンツの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
"merge.incomingHeaderBackground":"#ff0000", // インラインマージの競合における着信ヘッダーの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
"merge.incomingContentBackground":"#ff0000", // インラインマージの競合における着信コンテンツの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
"merge.border":"#ff0000", // ヘッダーの境界線の色とインラインマージ競合のスプリッター。
"merge.commonContentBackground":"#ff0000", // インラインマージ競合における共通の祖先コンテンツの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
"merge.commonHeaderBackground":"#ff0000", // インラインmerge-conflictsの共通の祖先ヘッダーの背景。下にある装飾を隠さないように、色は不透明であってはなりません。
"editorOverviewRuler.currentContentForeground":"#ff0000", // インラインマージ競合の現在の概要ルーラー前景。
"editorOverviewRuler.incomingContentForeground":"#ff0000", // インラインマージ競合の着信概要ルーラー前景。
"editorOverviewRuler.commonContentForeground":"#ff0000", // インラインマージ競合の共通の祖先概要ルーラーの前景。
```

# パネル色
パネルはエディター領域の下に表示され、出力や統合ターミナルなどのビューが含まれています。

```
"panel.background":"#ff0000", // パネルの背景色。
"panel.border":"#ff0000", // パネルをエディターから分離するためのパネルの境界線の色。
"panel.dropBackground":"#ff0000", // パネルタイトルアイテムのフィードバックカラーをドラッグアンドドロップします。色は透明である必要がありますので、パネルのエントリはまだ透けて見えます。
"panelTitle.activeBorder":"#ff0000", // アクティブなパネルタイトルの境界線の色。
"panelTitle.activeForeground":"#ff0000", // アクティブなパネルのタイトル色。
"panelTitle.inactiveForeground":"#ff0000", // 非アクティブなパネルのタイトル色。
```

# ステータスバーの色
ステータスバーは、ワークベンチの下部に表示されます。

```
"statusBar.background":"#ff0000", // 標準ステータスバーの背景色。
"statusBar.foreground":"#ff0000", // ステータスバーの前景色。
"statusBar.border":"#ff0000", // ステータスバーとエディターを分離するステータスバーの境界線の色。
"statusBar.debuggingBackground":"#ff0000", // プログラムのデバッグ中のステータスバーの背景色。
"statusBar.debuggingForeground":"#ff0000", // プログラムのデバッグ中のステータスバーの前景色。
"statusBar.debuggingBorder":"#ff0000", // プログラムのデバッグ中にステータスバーとエディターを分離するステータスバーの境界線の色。
"statusBar.noFolderForeground":"#ff0000", // フォルダーが開かれていないときのステータスバーの前景色。
"statusBar.noFolderBackground":"#ff0000", // フォルダが開かれていないときのステータスバーの背景色。
"statusBar.noFolderBorder":"#ff0000", // フォルダーが開かれていないときのステータスバーとエディターを分離するステータスバーの境界線の色。
"statusBarItem.activeBackground":"#ff0000", // クリック時のステータスバー項目の背景色。
"statusBarItem.hoverBackground":"#ff0000", // ホバリング時のステータスバー項目の背景色。
"statusBarItem.prominentForeground":"#ff0000", // ステータスバーの目立つアイテムの前景色。
"statusBarItem.prominentBackground":"#ff0000", // ステータスバーの目立つアイテムの背景色。
"statusBarItem.prominentHoverBackground":"#ff0000", // ホバリング時のステータスバーの目立つアイテムの背景色。
```

重要なことを示すために、他のステータスバーのエントリよりも目立つアイテムが目立ちます。1つの例は、Toggle Tab Key Moves Focusコマンド変更モードインジケーターです。

# タイトルバーの色

```
"titleBar.activeBackground":"#ff0000", // ウィンドウがアクティブなときのタイトルバーの背景。
"titleBar.activeForeground":"#ff0000", // ウィンドウがアクティブなときのタイトルバーの前景。
"titleBar.inactiveBackground":"#ff0000", // ウィンドウがアクティブでないときのタイトルバーの背景。
"titleBar.inactiveForeground":"#ff0000", // ウィンドウがアクティブでないときのタイトルバーの前景。
"titleBar.border":"#ff0000", // タイトルバーの境界線の色。
```

# メニューバーの色

```
"menubar.selectionForeground":"#ff0000", // メニューバーで選択されたメニュー項目の前景色。
"menubar.selectionBackground":"#ff0000", // メニューバーで選択されたメニュー項目の背景色。
"menubar.selectionBorder":"#ff0000", // メニューバーで選択したメニュー項目の境界線の色。
"menu.foreground":"#ff0000", // メニュー項目の前景色。
"menu.background":"#ff0000", // メニュー項目の背景色。
"menu.selectionForeground":"#ff0000", // メニューで選択されたメニュー項目の前景色。
"menu.selectionBackground":"#ff0000", // メニューで選択されたメニュー項目の背景色。
"menu.selectionBorder":"#ff0000", // メニューで選択されたメニュー項目の境界線の色。
"menu.separatorBackground":"#ff0000", // メニュー内のセパレータメニュー項目の色。
```

# 通知の色
注：以下の色は、VS Codeバージョン1.21以降にのみ適用されます。

通知トーストは、ワークベンチの右下から上にスライドします。

通知センターで開くと、ヘッダー付きのリストに表示されます。

```
"notificationCenter.border":"#ff0000", // 通知センターの境界線の色。
"notificationCenterHeader.foreground":"#ff0000", // 通知センターのヘッダーの前景色。
"notificationCenterHeader.background":"#ff0000", // 通知センターのヘッダーの背景色。
"notificationToast.border":"#ff0000", // 通知トーストの境界線の色。
"notifications.foreground":"#ff0000", // 通知の前景色。
"notifications.background":"#ff0000", // 通知の背景色。
"notifications.border":"#ff0000", // 通知センターの他の通知と区別する通知境界線の色。
"notificationLink.foreground":"#ff0000", // 通知リンクの前景色。
1.21（2018年2月）リリースより前のVS Codeバージョンを対象とする場合、これらは古い（サポートされなくなった）色です。

"notification.background"
"notification.foreground"
"notification.buttonBackground"
"notification.buttonForeground"
"notification.buttonHoverBackground"
"notification.errorBackground"
"notification.errorForeground"
"notification.infoBackground"
"notification.infoForeground"
"notification.warningBackground"
"notification.warningForeground"
```

# 拡張機能

```
"extensionButton.prominentForeground":"#ff0000", // 拡張ビューボタンの前景色（たとえば、インストールボタン）。
"extensionButton.prominentBackground":"#ff0000", // 拡張表示ボタンの背景色。
"extensionButton.prominentHoverBackground":"#ff0000", // 拡張表示ボタンの背景ホバーカラー。
```

# クイックピッカー

```
"pickerGroup.border":"#ff0000", // 境界線をグループ化するためのクイックピッカー（クイックオープン）色。
"pickerGroup.foreground":"#ff0000", // ラベルをグループ化するためのクイックピッカー（クイックオープン）色。
```

# 統合ターミナルの色

```
"terminal.background":"#ff0000", // 統合ターミナルのビューポートの背景。
"terminal.border":"#ff0000", // ターミナル内の分割ペインを区切る境界線の色。デフォルトはpanel.borderです。
"terminal.foreground":"#ff0000", // 統合端末のデフォルトの前景色。
"terminal.ansiBlack":"#ff0000", // 端末の「黒」ANSIカラー。
"terminal.ansiBlue":"#ff0000", // ターミナルの「青色」ANSI色。
"terminal.ansiBrightBlack":"#ff0000", // ターミナルの「BrightBlack」ANSIカラー。
"terminal.ansiBrightBlue":"#ff0000", // ターミナルの「BrightBlue」ANSIカラー。
"terminal.ansiBrightCyan":"#ff0000", // 端末の 'BrightCyan' ANSIカラー。
"terminal.ansiBrightGreen":"#ff0000", // 端末の「BrightGreen」ANSIカラー。
"terminal.ansiBrightMagenta":"#ff0000", // ターミナルの「BrightMagenta」ANSIカラー。
"terminal.ansiBrightRed":"#ff0000", // ターミナルの「BrightRed」ANSIカラー。
"terminal.ansiBrightWhite":"#ff0000", // 端末の 'BrightWhite' ANSIカラー。
"terminal.ansiBrightYellow":"#ff0000", // ターミナルの「明るい黄色」ANSI色。
"terminal.ansiCyan":"#ff0000", // ターミナルの「シアン」ANSIカラー。
"terminal.ansiGreen":"#ff0000", // ターミナルの「グリーン」ANSI色。
"terminal.ansiMagenta":"#ff0000", // ターミナルの「マゼンタ」ANSIカラー。
"terminal.ansiRed":"#ff0000", // ターミナルの「赤」ANSI色。
"terminal.ansiWhite":"#ff0000", // ターミナルの「白」ANSI色。
"terminal.ansiYellow":"#ff0000", // 端末の「黄色」のANSIカラー。
"terminal.selectionBackground":"#ff0000", // ターミナルの選択背景色。
"terminalCursor.background":"#ff0000", // ターミナルカーソルの背景色。ブロックカーソルが重なる文字の色をカスタマイズできます。
"terminalCursor.foreground":"#ff0000", // ターミナルカーソルの前景色。
```

# デバッグ

```
"debugToolBar.background":"#ff0000", // ツールバーの背景色をデバッグします。
"debugToolBar.border":"#ff0000", // ツールバーの境界線の色をデバッグします。
"editor.stackFrameHighlightBackground":"#ff0000", // エディターの一番上のスタックフレームのハイライトの背景色。
"editor.focusedStackFrameHighlightBackground":"#ff0000", // エディター内のフォーカスされたスタックフレームハイライトの背景色。
```

# ようこそページ

```
"welcomePage.background":"#ff0000", // ようこそページの背景色。
"welcomePage.buttonBackground":"#ff0000", // ようこそページのボタンの背景色。
"welcomePage.buttonHoverBackground":"#ff0000", // [ようこそ]ページのボタンの背景色をホバーします。
"walkThrough.embeddedEditorBackground":"#ff0000", // インタラクティブプレイグラウンドの埋め込みエディターの背景色。
```

Gitカラー

```
"gitDecoration.addedResourceForeground":"#ff0000", // 追加されたGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
"gitDecoration.modifiedResourceForeground":"#ff0000", // 変更されたGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
"gitDecoration.deletedResourceForeground":"#ff0000", // 削除されたGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
"gitDecoration.untrackedResourceForeground":"#ff0000", // 追跡されていないGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
"gitDecoration.ignoredResourceForeground":"#ff0000", // 無視されたGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
"gitDecoration.conflictingResourceForeground":"#ff0000", // 競合するGitリソースの色。ファイルラベルとSCMビューレットに使用されます。
"gitDecoration.submoduleResourceForeground":"#ff0000", // サブモジュールリソースの色。
設定エディターの色
注：これらの色は、Preferences: Open Settings (UI)コマンドで開くことができるGUI設定エディター用です。

"settings.headerForeground":"#ff0000", // セクションヘッダーまたはアクティブなタイトルの前景色。
"settings.modifiedItemIndicator":"#ff0000", // 変更された設定を示す行。
"settings.dropdownBackground":"#ff0000", // ドロップダウンの背景。
"settings.dropdownForeground":"#ff0000", // ドロップダウンの前景。
"settings.dropdownBorder":"#ff0000", // ドロップダウンボーダー。
"settings.dropdownListBorder":"#ff0000", // ドロップダウンリストの境界線。
"settings.checkboxBackground":"#ff0000", // チェックボックスの背景。
"settings.checkboxForeground":"#ff0000", // チェックボックスの前景。
"settings.checkboxBorder":"#ff0000", // チェックボックスの境界線。
"settings.textInputBackground":"#ff0000", // テキスト入力ボックスの背景。
"settings.textInputForeground":"#ff0000", // テキスト入力ボックスの前景。
"settings.textInputBorder":"#ff0000", // テキスト入力ボックスの境界線。
"settings.numberInputBackground":"#ff0000", // 数値入力ボックスの背景。
"settings.numberInputForeground":"#ff0000", // 数字入力ボックスの前景。
"settings.numberInputBorder":"#ff0000", // 数値入力ボックスの境界線。
```

# パンくずリスト
パンくずリストナビゲーションのテーマの色：

```
"breadcrumb.foreground":"#ff0000", // パンくずリストのアイテムの色。
"breadcrumb.background":"#ff0000", // パンくずリストの背景色。
"breadcrumb.focusForeground":"#ff0000", // フォーカスされたパンくずリストの色。
"breadcrumb.activeSelectionForeground":"#ff0000", // 選択したパンくずリストの色。
"breadcrumbPicker.background":"#ff0000", // パンくずリストピッカーの背景色。
```

# スニペット
スニペットのテーマの色：

```
"editor.snippetTabstopHighlightBackground":"#ff0000", // スニペットタブストップの背景色を強調表示します。
"editor.snippetTabstopHighlightBorder":"#ff0000", // スニペットタブストップの境界線の色を強調表示します。
"editor.snippetFinalTabstopHighlightBackground":"#ff0000", // スニペットの最後のタブストップの背景色を強調表示します。
"editor.snippetFinalTabstopHighlightBorder":"#ff0000", // スニペットの最後のタブストップの境界線の色を強調表示します。
```
