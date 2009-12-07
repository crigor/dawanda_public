important note for passenger_memory_stats and passenger_status:

you need to allow the munin user to call the passenger-* scripts:

> sudo visudo
add the following line at the bottom
> munin ALL=(ALL) NOPASSWD:/usr/bin/passenger-status, /usr/bin/passenger-memory-stats

and do not forget to restart munin-node

based on: http://www.dcmanges.com/blog/rails-application-visualization-with-munin



INSTALL SCRIPT RUBY

