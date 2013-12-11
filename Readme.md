测试smtp客户端

    1.环境
        [kimffy@kimffy sendmail]$ uname -a
        Linux kimffy.localdomain 2.6.32-358.23.2.el6.centos.plus.x86_64 #1 SMP Thu Oct 17 00:31:29 UTC 2013 x86_64 x86_64 x86_64 GNU/Linux
	[kimffy@kimffy sendmail]$ gcc -v
	使用内建 specs。
	目标：x86_64-redhat-linux
	配置为：../configure --prefix=/usr --mandir=/usr/share/man --infodir=/usr/share/info --with-bugurl=http://bugzilla.redhat.com/bugzilla --enable-bootstrap --enable-shared --enable-threads=posix --enable-checking=release --with-system-zlib --enable-__cxa_atexit --disable-libunwind-exceptions --enable-gnu-unique-object --enable-languages=c,c++,objc,obj-c++,java,fortran,ada --enable-java-awt=gtk --disable-dssi --with-java-home=/usr/lib/jvm/java-1.5.0-gcj-1.5.0.0/jre --enable-libgcj-multifile --enable-java-maintainer-mode --with-ecj-jar=/usr/share/java/eclipse-ecj.jar --disable-libjava-multilib --with-ppl --with-cloog --with-tune=generic --with-arch_32=i686 --build=x86_64-redhat-linux
	线程模型：posix
	gcc 版本 4.4.7 20120313 (Red Hat 4.4.7-3) (GCC) 
	[kimffy@kimffy sendmail]$ cat /etc/redhat-release 
	CentOS release 6.4 (Final)


/*
 **注意
 **仅作研究
 */
