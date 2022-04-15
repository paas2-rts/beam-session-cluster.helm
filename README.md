TODO:

-   Need to clean up savepoints

Stop job with savepoint

upgradeMode: savepoint
state: running -> suspended

Start job after suspending with the latest savepoint

upgradeMode: savepoint
state: suspended -> running

Upgrade job using savepoint

image: gimral/beam-app:1.0.4 -> gimral/beam-app:1.0.5

Update base chart
 helm dependency update
