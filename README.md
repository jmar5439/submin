# submin
submin

yum install python-devel

yum install neon-devel

yum install mod_dav_svn


wget http://opensource.wandisco.com/centos/5/svn-1.7/RPMS/i386/mod_dav_svn-1.7.20-1.i386.rpm

rpm -ivh mod_dav_svn-1.7.20-1.i386.rpm

yum install pysvn

submin2-admin /var/lib/submin apacheconf create all

ln -s /var/lib/submin/conf/apache-svn.conf /etc/apache2/conf.d/
