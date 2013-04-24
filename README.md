turn_key_worker_with_config
===========================

Simple worker for testing the "config" option in IronWorker.

Get an [Iron.io](www.iron.io) account and [create your iron.json file](http://dev.iron.io/worker/reference/configuration/). Then run:

1. Install the iron_worker cli: `gem install iron_worker_ng`
1. You can add this worker to your account in one of two ways: 
  - Upload directly from GitHub: `iron_worker upload https://github.com/treeder/turn_key_worker_with_config/blob/master/turn_key_config.worker --worker-config config.yml`
  - Or clone this repository and run: `iron_worker upload turn_key_config --worker-config config.yml`
1. Then queue up a task: `iron_worker queue turn_key_config --wait`

