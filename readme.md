  ./gradlew cloudNativeDeveloperDistributedSystemDeployment \
      -PregistrationServerUrl=https://registration-pal-t5.apps.evans.pal.pivotal.io \
      -PbacklogServerUrl=https://backlog-pal-t5.apps.evans.pal.pivotal.io \
      -PallocationsServerUrl=https://allocations-pal-t5.apps.evans.pal.pivotal.io \
      -PtimesheetsServerUrl=https://timesheets-pal-t5.apps.evans.pal.pivotal.io

curl https://spring-cloud-broker.apps.evans.pal.pivotal.io/info

Dalston.SR1