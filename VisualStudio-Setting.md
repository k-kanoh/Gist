# Visual Studio 設定

## 拡張機能
- XAML Styler
- CodeMaid

## CodeMaid設定
- Cleaning
    - General
        - ☐ Automatically run cleanup on file save (保存時に勝手に自動整形するか)
    - Visual Studio
        - ☐ ~~Skip during automatic cleanup on save (保存時に勝手にusing整理するか)~~ (整理できなくなった?)
    - Insert
        - ☑ Insert end of file trailing new line (EOFの前に改行入れるか)
        - `Insert explicit access modifiers on` ~~properties~~ (requiredが消される対策)
- Collapsing
    - ☐ Collapse solutions when they are opened (ソリューションを勝手に折りたたんだ状態にするか)
- Progressing
    - ☐ Show build progress window when a build starts (ビルド時にCodeMaidの進行状況モニタを使うか)
- Third Party
    - ☑ Run XAML Styler cleanup

### メモ
- Automatically save and close documents opened by cleanup  
ソリューションエクスプローラの右クリックからCodeMaidした時に勝手に閉じるか
- Reorganizing  
コードのクラスをアルファベット順に並べるか

## 設定
定義へ移動をオフ
![image](https://user-images.githubusercontent.com/97450450/244451043-269d0e9d-5b93-4c18-9a6b-2bd3bdb7c9b6.png)

継承の余白をオフ
![image](https://user-images.githubusercontent.com/97450450/244451307-b69bbc9b-b1dd-4a0d-834c-34147daa4a28.png)

アプリ内ツールバーを無効
![image](https://user-images.githubusercontent.com/97450450/244451448-c6a9903b-bb3e-4359-b7f8-f949550adb91.png)

CodeLensをオフ
![image](https://user-images.githubusercontent.com/97450450/244451565-37f52cfa-9ec5-4733-8b24-440d047b6755.png)
