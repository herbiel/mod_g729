
这是一个基于 linphone 与 mod_bcg729 开源项目开发的 FreeSWITCH 的 G.729 模块，支持转码和录音

### Install tutorial

	$ git clone https://github.com/typefo/mod_g729.git
	$ cd mod_g729
    $ make
    $ make install

### freeswitch configuration

Edit /usr/local/freeswitch/conf/autoload_configs/modules.conf.xml

    <!-- Codec Interfaces -->
    <!-- <load module="mod_spandsp"/> -->
    <!-- <load module="mod_g723_1"/> -->
    <load module="mod_g729"/>
    <!-- <load module="mod_amr"/> -->
    ......

Remove the `<load module="mod_g729"/>` annotation

### 赞助商 4bit

[![](https://typefo.com/assets/img/ad.jpg)](https://item.taobao.com/item.htm?ft=t&id=637600633789)
