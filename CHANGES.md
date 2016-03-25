### 0.3.3 / 2016-03-25

* Fixed lock refresher not calling `redis_pool` properly so it wouldn't actually run

### 0.3.2 / 2016-03-10

* Fixed lock refresher failing to lock properly for exclusive runs
* Added debug logs for lock refresher 

### 0.3.1 / 2016-02-17

* Fixed lock refresh checking timeout rather than expiration for finding eligible jobs

### 0.3.0 / 2016-01-25

* Added lock refresh to maintain exclusive locks until long running jobs finish

### 0.2.2 / 2015-11-11

* Support ERB in job schedules
* Handle exceptions more gracefully in lock acquisition

### 0.2.0 / 2015-04-18

* Add KillSwitch middleware
* Cleanup

### 0.1.4 / 2015-03-26

* Initial release
