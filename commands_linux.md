# Comandos Linux


```sh
$ df -l				// Listar espaço em disco
$ ls -al     		// formatted listing with files
$ mkdir 			// Make directory
$ pwd				// Print working directory
$ blkid 			// listar as partições
$ nano /etc/fstab	// editar aquivo para montar particão automaticamente

// após a última linha do arquivo fstab, insira a linha com a UUID
// <file system> <mount point>   <type>  <options>       <dump>  <pass>
UUID=36C8ECCB11EC2D26 /home/eric/files ntfs defaults,user.rw,auto 0 0

```

$  upower -i /org/freedesktop/UPower/devices/battery_BAT0	//battery
