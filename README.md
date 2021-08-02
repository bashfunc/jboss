# jboss


Jboss bash functions

    #!/bin/bash
    if [ - z "$(pgrep -f jboss)"] then
      echo "JBOSS is NOT running"
    fi
