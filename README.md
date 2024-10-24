# CRID-usm-Decrypter
## コンパイル
```powershell
# Windows
g++ Source.cpp clCRID.cpp clUTF.cpp clADX.cpp -o Source.exe -fexec-charset=CP932
# macOS
g++ Source.cpp clCRID.cpp clUTF.cpp clADX.cpp -o Source.exe
```
## 使い方  
```
CRID-umd-Decrypter.exe -a <A> -b <B> -o <Output> <Source>
```
### A
HCAキーの下8桁
### B
HCAキーの上8桁
