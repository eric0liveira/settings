# Comandos Linux

- Listar espaço em disco

```sh
$ df -l
```

- listar as partições

```sh
$ sudo blkid
```

- montar particão automaticamente

```sh
$ sudo nano /etc/fstab
```

- após a última linha do arquivo fstab, insira a linha com a UUID

```sh
// <file system> <mount point>   <type>  <options>       <dump>  <pass>
UUID=36C8ECCB11EC2D26 /home/eric/files ntfs defaults,user.rw,auto 0 0
```
