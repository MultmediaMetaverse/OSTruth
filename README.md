# OSTruth
OS Truth reback

常用命令：
  dd if=./mbr.bin of=hd60M.img bs=512 count=1 conv=notrunc
  dd if=./loader.bin of=hd60M.img bs=512 count=1 seek=2 conv=notrunc
  bochs -f bochsrc.disk 
  nasm -I include/ -o mbr.bin mbr.S 
  nasm -I include/ -o loader.bin loader.S 

注意事项：
 对于代码，一定要仔细对比，仔细查看，错误总在不经意间。
