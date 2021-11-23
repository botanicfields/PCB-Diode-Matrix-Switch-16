# PCB-Diode-Matrix-Switch-16

# ダイオードマトリクススイッチ16基板
タクトスイッチで4ビットのデータパターンを生成するダイオードマトリクス基板（未実装）です。
AquesTalk pico LSI のスタンドアロンモードの制御に使用できます。

## 1. 特徴
- タクトスイッチを押すと、ダイオードを実装したデータラインがGNDレベル"0"になります。
- AquesTalk pico LSI のスタンドアロンモードで、15種類の音声をスイッチ操作で再生できます。
- 全てのタクトスイッチにダイオード4本分のランドがあり、データパターンをカスタマイズできます。
- リード線タイプの一般的なスイッチング用ダイオード（1N4148など）を使用できます。
- 6mmサイズの一般的なタクトスイッチを使用できます。

## 2. 組み立て例
別途、部品が必要です。組み立てにはハンダ付けが必要です。  
タクトスイッチの下のシルクの数値に合わせ、"0"にするデータラインにダイオードを実装します。  
※4ビット（16種）のデータパターンのうち、"1111" だけはダイオードもタクトスイッチも不要です。  
<img src="./image/asm.JPG" width=300>

## 3. 内容物
- プリント基板（未実装） 1枚  

※部品、ケーブル、説明書は添付していません。  
表面、裏面  
<img src="./image/front.JPG" width=300> <img src="./image/back.JPG" width=300>

## 4. 使用例
- [GitHub: botanicfields/PCB-MBUS-AquesTalk-pico-LSI](https://github.com/botanicfields/PCB-MBUS-AquesTalk-pico-LSI)
- [GitHub: botanicfields/PCB-Grove-AquesTalk-pico-LSI](https://github.com/botanicfields/PCB-Grove-AquesTalk-pico-LSI)

<img src="./image/socket3.JPG" width=300> <img src="./image/standalone.JPG" width=300>

