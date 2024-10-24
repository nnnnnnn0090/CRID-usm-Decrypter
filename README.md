# CRID-usm-Decrypter (Windows / macOS)
## コンパイル
```powershell
# Windows
g++ Source.cpp clCRID.cpp clUTF.cpp clADX.cpp -o CRID-usm-Decrypter-Windows.exe -fexec-charset=CP932
# macOS
g++ Source.cpp clCRID.cpp clUTF.cpp clADX.cpp -o CRID-usm-Decrypter-macOS
```
## 使い方  
```
CRID-umd-Decrypter.exe -a <A> -b <B> -o <Output> <Source>
```
### A
HCAキーの下8桁
### B
HCAキーの上8桁
