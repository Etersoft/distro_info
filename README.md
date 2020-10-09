# distro_info

Use distro_info in your scripts when you need a linux command to check distribution (distro) name and version.

Just run
    ./distro_info -e

or -h to get all supported options.

```
$ ./distro_info
distro_info v20201010 : Copyright © 2007-2020 Etersoft
==== Total system information:
Pretty distro name (--pretty): ALT Sisyphus Sisyphus (unstable) (sisyphus)
 Distro name and version (-e): ALTLinux/Sisyphus
        Packaging system (-p): rpm
 Running service manager (-y): sysvinit
          Virtualization (-i): kvm
               CPU Cores (-c): 16
        CPU Architecture (-a): x86_64
 CPU norm register size  (-b): 64
 System memory size (MB) (-m): 23659
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

## Simular projects ##

* /etc/os-release (systemd)
* # lsb_release -a (lsb-release)

## Links ##

* https://github.com/LibreTime/libretime/issues/173
* https://unix.stackexchange.com/questions/35183/how-do-i-identify-which-linux-distro-is-running
* https://riptutorial.com/linux/topic/872/detecting-linux-distribution-name-and-version
* https://superuser.com/questions/929741/how-does-one-identify-the-linux-distro-in-use/929744#929744
* https://unix.stackexchange.com/questions/6345/how-can-i-get-distribution-name-and-version-number-in-a-simple-shell-script
* https://www.cyberciti.biz/faq/find-linux-distribution-name-version-number/
* https://www.howtoforge.com/how_to_find_out_about_your_linux_distribution
* https://linuxize.com/post/how-to-check-linux-version/
