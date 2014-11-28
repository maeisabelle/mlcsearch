mlcsearch
=========

MLC Search Engine

Extract to your Tomcat webapps directory and edit mlcsearch/WEB-INF/web.xml:

<env-entry>
    <env-entry-name>solr/home</env-entry-name>
    <env-entry-value>/usr/share/apache-tomcat-7.0.57/webapps/mlcsearch</env-entry-value>
    <env-entry-type>java.lang.String</env-entry-type>
</env-entry>

Make sure to replace env-entry-value with the correct tomcat webapps directory.

