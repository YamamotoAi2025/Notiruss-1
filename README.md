# Notiruss-1
My mobile office of MD04 (Honda CRZ)

# ノーチラス1号 コンピュータールーム記録

## 📷 起動写真
![Nautilus1起動](https://github.com/YamamotoAi2025/Notiruss-1/blob/main/IMG_20250908_163045.jpg)

![Nautilus1活用](
https://github.com/YamamotoAi2025/Notiruss-1/blob/main/PANO_20250911_112656.jpg)


## 概要
車載研究スペース「ノーチラス1号」にて、新規組み立てPCの初起動を確認。  
BIOS画面まで正常に進み、今後の研究・開発の基盤として運用予定。

## ハードウェア構成
- マザーボード: ASUS PRIME B650M-A II
- CPU: AMD Ryzen 5 7600 (6コア)
- GPU: ASUS GeForce RTX（補助電源不要モデル）
- メモリ: DDR5-5200 32GB
- ケース: MONTECH (白)
- 電源: 車載インバーター経由

## 起動時の問題と解決
- **問題①:** モニターに信号が出なかった  
  → メモリの挿し位置が原因  
- **解決:** マニュアル推奨の黒スロットでは動作せず、グレーのスロットで正常動作  
- **補足:** GPUは補助電源不要モデルのため、PCIeスロット給電のみで動作確認  

## 現状
- BIOS画面を表示  
- メモリ 32768MB (DDR5-5200) を認識  
- ストレージは未設定（OSインストール準備中）

## 今後の予定
- OSインストール（WindowsまたはLinux）  
- ラズパイとの連携によるスタンドアロンAI実験  
- 車載研究室「ノーチラス1号」の完全自立化
