FROM cassandra:3

RUN perl -i.bak -pe '$n += s/^enable_user_defined_functions: false/enable_user_defined_functions: true/g; END { exit !$n }' /etc/cassandra/cassandra.yaml

