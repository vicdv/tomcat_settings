### Turn off the ehcache Java Web application in tomcat
$ cd <BASE_TOMCAT_FOLDER>

$ vim bin/setenv.sh

Add props to the end of CATALINA_OPTS

-Dnet.sf.ehcache.disabled=true