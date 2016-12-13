# share
export CATALINA_HOME=/opt/tomcat8.0.21
export CATALINA_BASE=/home/finance/Domains/dsvariable.msxf.lodev/server1
###JAVA
export JAVA_HOME=/opt/jdk1.7.0_79
export JAVA_BIN=/opt/jdk1.7.0_79/bin
export PATH=/usr/kerberos/sbin:/usr/kerberos/bin:/usr/local/sbin:/usr/local/bin:/sbin:/bin:/usr/sbin:/usr/bin:/root/bin:/bin
export CLASSPATH=.:/lib/dt.jar:/lib/tools.jar
export  JAVA_OPTS="-Djava.library.path=/usr/local/lib -server -Xms512m -Xmx512m -XX:MaxPermSize=256m -Djava.awt.headless=true -Dsun.net.client.defaultConnectTimeout=60000 -Dsun.net.client.defaultReadTimeout=60000 -Djmagick.systemclassloader=no -Dnetworkaddress.cache.ttl=300 -Dsun.net.inetaddr.ttl=300  -Dspring.profiles.active=dev"
export JAVA_HOME JAVA_BIN PATH CLASSPATH JAVA_OPTS
$CATALINA_HOME/bin/startup.sh -config $CATALINA_BASE/conf/server.xml

