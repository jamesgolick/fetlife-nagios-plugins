FetLife Nagios Plugins
======================

Some nagios plugins we're using at FetLife.

Services include:
  
  * Resque 
    * check_resque: Monitor resque queue sizes to get alerted if queues are backing up.
    * check_resque_failed: Monitor the number of failures in the queue.
