﻿chgtm tool
===================================

概要
-----------------------------------

ファイルのタイムスタンプを変更するためのツールです。  

アタッシェケースを公開するため、配布するバイナリファイルのすべてのタイムスタンプを揃えておきたいため、自作しました。  

具体的には以下のように指定します。  

chgtm.exe [ファイル名] yyyy mm dd  

日付だけの設定で、時間は指定できません。たとえば、  

chgtm.exe AttacheCase.exe 2012 01 31  

と指定すると、「2012/01/31 00:00:00」と設定されます。  
なお、未来の日付も指定することが可能です（リリース日が決まっている場合に、それに揃えておくことができるようにしてある）。  


著作権
-----------------------------------

Copyright (C) 2012 M.Hibara, All rights reserved.  
http://hibara.org/  


ライセンス
-----------------------------------
GPLv3を適用します。  

http://www.gnu.org/licenses/gpl-3.0.html  


