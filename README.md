# SPECjvm2008
Custom SPECjvm2008 for JDK&lt;version> > 7 

java -Djava.awt.headless=true --limit-modules java.base,java.desktop,java.sql,java.naming,java.xml --add-exports java.xml/com.sun.org.apache.xerces.internal.parsers=ALL-UNNAMED --add-exports java.xml/com.sun.org.apache.xerces.internal.util=ALL-UNNAMED -Djavax.xml.accessExternalSchema=file -jar SPECjvm2008.jar -wt 60 -it 60 -bt 8 --base -ikv compiler.compiler compiler.sunflow compress crypto.aes crypto.rsa crypto.signverify derby mpegaudio scimark.fft.large scimark.sor.large scimark.lu.small scimark.sparse.small scimark.monte_carlo serial sunflow xml.transform xml.validation

java can be pointing to any of the java -version available on your system.
