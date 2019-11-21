# distro_info

Use distro_info in your scripts when you need a linux command to check distribution (distro) name and version.

Just run
    ./distro_info -e

or -h to get all supported options.

```
$ ./distro_info 
distro_info total information (run with -h to get help):
 Distro name and version (-e): ALTLinux/Sisyphus
        Packaging system (-p): rpm
        CPU Architecture (-a): x86_64
 CPU norm register size  (-b): 64
 System memory size (MB) (-m): 19490
            Base OS name (-o): linux
Build system distro name (-s): alt
Build system vendor name (-n): alt
```

```
$ hostnamectl
   Static hostname: builder64.office.etersoft.ru
         Icon name: computer-vm
           Chassis: vm
        Machine ID: f93eda9fe7e07dae19e7defc493d6e57
           Boot ID: 5753f83f6dfa4fdf949e8e33cde1f2d9
    Virtualization: kvm
  Operating System: ALT Regular
       CPE OS Name: cpe:/o:alt:sisyphus:20191026
            Kernel: Linux 4.19.81-std-def-alt2
      Architecture: x86-64
```
