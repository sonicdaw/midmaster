# midmaster
'89 RPG for MSX
  
Play  
MSX1  
https://webmsx.org/?MACHINE=MSX1J&DISK=https://entaflip.com/msx/midmaster.dsk  
  
MSX2  
https://webmsx.org/?MACHINE=MSX1J&DISK=https://entaflip.com/msx/midmaster.dsk  

  
How to execute each dsk files  
  
1. Load Disk Images で midmaster_list1.dsk を読み込む  (または MSXPen にコードをはりつけて run)
load "AUTOEXEC.BAS"  
run  
  
2. Load Disk Images で midmaster_list2.dsk を読み込む  
load "AUTOEXEC.BAS"  
run  
  
  
How to create midmaster.dsk  
  
1. テキストをmsxpen のテキストにlist1 を入れて、run して読み込んだ後 Save Disk Image  -> midmaster_list1.dsk とする  
2. テキストをmsxpen のテキストにlist2 を入れて、run して読み込んだ後 Save Disk Image  -> midmaster_list2.dsk とする  
3. msxpen のディスクアイコン Drive A - Load Disk Images -> midmaster_list2.dsk を選択  
4. load "AUTOEXEC.BAS"  
5. msxpen のディスクアイコン Drive A - Load Disk Images -> midmaster_list1.dsk を選択  
6. save "MM.BAS"   (list2 が保存される)  
7. msxpen のディスクアイコン Drive A - Save disk image -> midmaster.dsk とする  