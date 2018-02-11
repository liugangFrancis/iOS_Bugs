MACdeMacBook-Pro:Desktop MAC$ cd /Users/MAC/Desktop/2017.10.15/lianxi
MACdeMacBook-Pro:lianxi MAC$ pod init
-bash: /usr/local/bin/pod: /System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/bin/ruby: bad interpreter: No such file or directory
MACdeMacBook-Pro:lianxi MAC$


1. 升级mac 版本后 ，cocoapod 不可以正常使用,出现问题如下：
-bash: /usr/local/bin/pod: /System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/bin/ruby: bad interpreter: No such file or directory

解决方案:
console:
        sudo gem update --system
        sudo gem install cocoapods -n/usr/local/bin
