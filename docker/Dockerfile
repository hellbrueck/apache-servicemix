FROM mkroli/servicemix:latest

# This is a command that replaces strings in files 
# RUN   sed -i "s|some-original-string|the-new-string |g" /etc/sysctl.conf

RUN   sed -i "s|http://repo1.maven.org|https://repo1.maven.org|g" /opt/apache-servicemix-7.0.1/etc/org.ops4j.pax.url.mvn.cfg

RUN   sed -i "s|http://repository.springsource.com|https://repository.springsource.com|g" /opt/apache-servicemix-7.0.1/etc/org.ops4j.pax.url.mvn.cfg

RUN   sed -i "s|http://zodiac.springsource.com|https://zodiac.springsource.com|g" /opt/apache-servicemix-7.0.1/etc/org.ops4j.pax.url.mvn.cfg

RUN   sed -i "s|http://repository.apache.org|https://repository.apache.org|g" /opt/apache-servicemix-7.0.1/etc/org.ops4j.pax.url.mvn.cfg

ENTRYPOINT ["/opt/servicemix/bin/servicemix"]
