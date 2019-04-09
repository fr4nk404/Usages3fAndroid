## Collection of System Information
Android获取手机配置信息，这里使用Build类用来简单获取，常用的记录一下。
android.os.Build.BOARD: 设备基板名称

android.os.Build.BOOTLOADER: 获取设备引导程序版本号

android.os.Build.BRAND: 获取设备品牌

android.os.Build.CPU_ABI: 获取设备指令集名称（CPU的类型）

android.os.Build.CPU_ABI2: 获取第二个指令集名称

android.os.Build.DEVICE: 获取设备驱动名称

android.os.Build.DISPLAY: 获取设备显示的版本包（在系统设置中显示为版本号）和ID一样

android.os.Build.FINGERPRINT: 设备的唯一标识。由设备的多个信息拼接合成。

android.os.Build.HARDWARE: 设备硬件名称,一般和基板名称一样（BOARD）

android.os.Build.HOST: 设备主机地址

android.os.Build.ID: 设备版本号

android.os.Build.MODEL: 获取手机的型号 设备名称。

android.os.Build.MANUFACTURER: 获取设备制造商

android:os.Build.PRODUCT: 整个产品的名称

android:os.Build.RADIO: 无线电固件版本号

android.os.Build.TAGS: 设备标签。如release-keys

android.os.Build.TIME: 时间

android.os.Build.TYPE: 设备版本类型, 主要为"user" 或"eng".

android.os.Build.USER: 设备用户名 基本上都为android-build

android.os.Build.VERSION.RELEASE：获取系统版本字符串。如4.1.2 或2.2 或2.3等

android.os.Build.VERSION.CODENAME：设备当前的系统开发代号，一般使用REL代替

android.os.Build.VERSION.INCREMENTAL：系统源代码控制值，一个数字或者git hash值

android.os.Build.VERSION.SDK：系统的API级别 一般使用下面大的SDK_INT 来查看

android.os.Build.VERSION.SDK_INT：系统的API级别 数字表示
