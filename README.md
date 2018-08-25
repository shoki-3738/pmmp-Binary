# pmmp-Binary
PocketMine-MP のbinフォルダ  <br>
* **Windows PHP-7.2.9** <br>
* **MacOS PHO-7.2** <br>
* **Linux PHP-7.2** <br>

MCBE-JPN版はpocketmine.icoがMCBE-JPN仕様になってます<br>

中身的には[pmmpさんのもの](https://ci.appveyor.com/project/pmmp/php-build-scripts/history)と同じになりますが <br>
以下のライブラリを使用可能にしています。<br>

* **php_gd2.dll <br>**
* **php_mysqli.dll <br>**
* **php_sqlite3.dll <br>**


# 対応 start.cmdファイル
[こちら](https://github.com/shoki-3738/pmmp-Binary/blob/master/start.cmd)のstart.cmdファイル(windows限定)を使用することにより、pocketmine.icoが使用可能となります。



# Binフォルダの構成  
bin/  
  -php/  
  -composer.bat  
  -composer.phar  
  -cygwin1.dll  
  -cygwin-console-helper.exe  
  -mintty.exe  
  -pocketmine.ico  
