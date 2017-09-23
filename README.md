# ubuntu-partition
#ubuntu necessary 4 partitiom
#以下针对UEFI
目录      大小      格式       描述
/         10-20G    ext4      根目录(主分区)
swap      <2G       swap      none（主分区）
/boot     200M      ext4      引导文件（主分区；grub安装在boot分区，可以单独启动，和windows没关系，删除boot，激活windows分区，windows也能启动）
/home     剩下的     ext4      用户工作目录；个人配置文件，如个人环境变量等；所有账号分配一个工作目录（主分区）




