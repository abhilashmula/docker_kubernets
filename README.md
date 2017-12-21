# Informatica
Java Code to publish messages to a kafka broker.

If using Intellij import the JAR files add the below additional VM options.

-Djava.security.auth.login.config=/tmp/kafka_client_jaas.conf -Djava.security.krb5.conf=/tmp/krb5.conf -Djavax.security.auth.useSubjectCredsOnly=false

Modify the kafka_client_jaas.conf kerberos keytabs as per your environment.
