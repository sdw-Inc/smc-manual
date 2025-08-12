---
layout: default
title: OCR図面アップロード
parent: 機能：管理者向け
grand_parent: 品質管理
nav_order: 7
has_children: false
---

# OCR図面アップロードを行う

### 新規登録

1. [品質管理システム]トップ画面から「OCR図面アップロード」を選択します。
    
    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/1.png" width="70%">
    </td></tr></table>

1. [OCR図面一覧]画面右上の「新規登録」を選択します。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/2.png" width="85%">
    </td></tr></table>

1. 必須項目を入力して「登録」を選択して完了です。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/3.png" width="80%">
    </td></tr></table>

    {: .note }
    階数は図面登録チェック画面での製品の検索範囲に使用されます。

    {: .warning }
    枚数が多いと登録に時間がかかります。

1. 登録が完了した図面は[OCR図面一覧]画面に表示されます。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/4.png" width="85%">
    </td></tr></table>

<br>

### OCR読取

{: .warning }
OCR読取はMacもしくはiPadのみで使用できる機能です。

1. [OCR図面一覧]画面でOCR読取を行いたい図面の「OCR読取」を選択します。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/5.png" width="85%">
    </td></tr></table>

1. OCR読取を行いたい図面を選択します。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/17.png" width="75%">
    </td></tr></table>

    {: .warning }
    読取箇所が違う図面は分けてOCR読取を行なってください。

1. 読み取りたい範囲を四角枠で囲います。読取範囲を指定したら、「次へ」を選択します。

    - <span style="color: red; ">赤枠</span>：部材名（製品番号）  
    - <span style="color: blue; ">青枠</span>：図面番号

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/6.png" width="85%">
    </td></tr></table>

    {: .note }
    選択した図面の一枚目が表示されます。

1. OCR読取結果が表示されます。内容を確認したら「OCR保存」選択でOCR読取を完了します。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/7.png" width="75%">
    </td></tr></table>

    {: .note }
    読み取った部材名と図面番号はこの画面上でも後からでも修正が可能です。

    {: .note }
    OCR読取を分けて行う場合は、読取図面選択画面まで戻って図面を選択し直してください。

    {: .warning }
    「OCR保存」を行うとOCR読取をやり直すことができなくなります。

<br>

### 図面内容編集

1. [OCR図面一覧]画面で編集を行いたい図面の「編集」を選択します。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/8.png" width="85%">
    </td></tr></table>

1. OCR読取を行なった部材名と図面番号の手動修正を行います。確認したら「次へ」を選択します。

    - 入力例

    | 入力部材名                       | 対象製品番号                                           | 
    | -------------------------------- | ------------------------------------------------------ | 
    | 37C-19                           | 37C-19                                                 | 
    | 37C~41C-19                       | 37C-19、38C-19、39C-19、40C-19、41C-19                 | 
    | 30C-20<br>40~41C-20<br>50~53C-20 | 30C-20、40C-20、41C-20、50C-20、51C-20、52C-20、53C-20 | 


    {: .warning }
    記号や英数字は半角で入力してください。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/9.png" width="75%">
    </td></tr></table>

1. 物件名や図面タイプなど、間違いがあれば手動修正を行います。確認したら「次へ」を選択します。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/10.png" width="95%">
    </td></tr></table>

    {: .warning }
    図面アップロードを行う前に階数の入力をしてください。

1. 入力した図面番号と部材名が一覧で表示されます。  
    変更図として登録し日付を入力した場合は、日付付き図面番号が表示されます。

    - 「詳細」  
    クリックで各図面を登録する対象の製品番号が表示されます。
    - 「確認欄」  
    チェックをつけると、確認者名と確認日時が登録されます。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/11.png" width="75%">
    </td></tr></table>

1. 図面をアップする対象の製品番号が一覧で表示されます。アップする図面IDや対象製品を変更することが可能です。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/12.png" width="100%">
    </td></tr></table>

    図面番号は、基幹システム＞製品マスタにも自動で入力されます。
    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/13.png" width="70%">
    </td></tr></table>

<br>

### 図面アップロード

1. [出図・変更図一覧]画面の右上にある「アップロード」を選択して完了です。アップロード後は参照画面に切り替わります。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/14.png" width="75%">
    </td></tr></table>

    {: .warning }
    確認欄①,②にチェックをつけることで図面のアップロードが可能となります。

    {: .warning }
    階数が未入力の場合は、図面情報変更画面にて階数の入力を行ってからアップロードしてください。

1. アップロードが完了した図面は編集不可となり、参照のみ可能となります。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/15.png" width="85%">
    </td></tr></table>

<br>

### 図面登録チェック

1. 図面一覧画面の「参照」ボタンから[出図or変更図一覧 参照]画面に移動します。  
    画面右上にある「図面登録チェック」を選択し、[図面登録チェック]画面に遷移します。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/18.png" width="75%">
    </td></tr></table>

    {: .warning }
    対象製品の件数が多いと、表示に時間がかかります。

1. 物件と設定した階数の範囲で絞り込まれた製品情報が一覧で表示されます。

    ○絞り込み条件詳細
    - 「図面有無」  
    1枚でも図面データが登録されている製品を、図面有りと判定します。
    - 「未登録図面有無」  
    図面番号が入力されていて図面データが登録されていない製品を、図面未登録有りと判定します。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/19.png" width="100%">
    </td></tr></table>

    {: .note }
    デフォルトで、図面有りの製品で絞り込まれます。

<br>

### ○補足

1. 図面の削除は[OCR図面一覧]画面から行うことができます。

    <table><tr><td>
    <img src="../../../../assets/images/quality-control/administrator/ocr-draw/16.png" width="85%">
    </td></tr></table>

    {: .warning }
    アップロード済みの図面は削除不可となります。
