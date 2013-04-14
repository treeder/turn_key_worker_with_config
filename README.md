turn_key_worker_with_config
===========================

Simple worker for testing the "config" option in IronWorker.

Get an [Iron.io](www.iron.io) account and [create your iron.json file](http://dev.iron.io/worker/reference/configuration/). Then run:

1. gem install iron_worker_ng
1. iron_worker upload turn_key_config --worker-config config.yml
1. iron_worker queue turn_key_config --wait

