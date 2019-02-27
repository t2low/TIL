# Material Design

## リップル

### 簡単に実装する

クリックするViewの `foreground` に以下の設定をする
 
- `?attr/selectableItemBackground` - 波紋はみ出さない
- `?attr/selectableItemBackgroundBorderless` - 波紋はみ出す

#### 罠

xmlではエラーなく設定できるが、コードからはAndroid M以上が必要
https://qiita.com/kuwapp/items/598ce3eeea60cb79d9e4

