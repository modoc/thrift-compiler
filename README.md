# thrift-exec

This project collect the thrift executables files for some platform, now including:

* linux-x86_64
* windows-x86_64
* windows-x86_32 (download from [apache](http://thrift.apache.org/download), same with x86_64)

If the target executable file you need is not in my project, you can contribute it to my repository. 
Maybe you need to compile by yourself because I only have the windows and linux environment.

**When do configuration, only nodejs is excluded (--with-nodejs=no), but this project best support Java, others like python should do local install**

The system name and arch reference to os-maven-plugin: [trustin/os-maven-plugin](https://github.com/trustin/os-maven-plugin)

The following is the overview of the available name and arch. 

#### Attention

**The version of this project is same with thrift. New arch or system name will be added for every version. So only SNAPSHOT will used for this project.**

#### name

value | description
---|---
aix | if the system name starts with aix
hpux | if the system name starts with hpux
os400 | if the system name starts with os400 and its following character is not a digit (e.g. os4000)
linux | if the system name starts with linux
osx | if the value system name with macosx or osx
freebsd | if the system name starts with freebsd
openbsd | if the system name starts with openbsd
netbsd | if the system name starts with netbsd
sunos | if the system name starts with solaris or sunos
windows | if the system name starts with windows

#### arch

value | description
---|---
x86_64 | if the arch is one of: x8664, amd64, ia32e, em64t, x64
x86_32 | if the arch is one of: x8632, x86, i386, i486, i586, i686, ia32, x32
itanium_64 | if the arch is one of: ia64, itanium64
sparc_32 | if the arch is one of: sparc, sparc32
sparc_64 | if the arch is one of: sparcv9, sparc64
arm_32 | if the arch is one of: arm, arm32
aarch_64 | if the arch is aarch64
ppc_32 | if the arch is one of: ppc, ppc32
ppc_64 | if the arch is ppc64
ppcle_64 | if the arch is ppc64le
s390_32 | if the arch is s390
s390_64 | if the arch is s390x

## Reference

* [protoc-artifacts](https://github.com/google/protobuf/tree/master/protoc-artifacts)
* [trustin/os-maven-plugin](https://github.com/trustin/os-maven-plugin)

## Contact

mailto: zhfchdev@gmail.com
