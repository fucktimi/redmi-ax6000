这里是红米ax6000-128M-U-boot固件，基于immortalwrt-24.10，linux内核版本6.6,闭源无线驱动，自带passwall、mosdns、openlist、tailscale，可修改代码增加自己需要的插件，直接fork即可云编译，毫无保留。


2026年10月19日更新：这个项目已经严重过时了，建议使用mt798x-25.12版本，项目源码https://github.com/chasey-dev/immortalwrt-mt798x-rebase。基于linux-6.12内核，可以运行基于ebpf的最新分流软件dae或者honk（建议用honk），在分流的同时，被判定直连的流量可以吃到硬件nat加速，实际使用速度比passwall好太多，内存占用也比passwall低得多(特别是honk基于rust编写)，而且ebpf分流不靠iptables基本不用担心与tailscale冲突。我已经全面转向这套方案并且在本地搭建了适配这套方案的编译环境，这个项目以后没有存在的必要了，有能力的建议自己折腾一下转向。
