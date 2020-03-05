Loosely derived from 
https://medium.com/@damesavram/running-airflow-on-heroku-ed1d28f8013d

This requires pushing with `cf v3-push <appname>`; see docs here:
https://docs.cloudfoundry.org/devguide/multiple-processes.html#push-with-multiple-processes
After pushing, scale it up with `cf v3-scale <appname> --process scheduler -i 1`; see docs here:
https://docs.cloudfoundry.org/devguide/multiple-processes.html#scale-a-process