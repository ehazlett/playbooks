# Mesos
Playbook for installing Mesos on Ubuntu.

# Variables

## zk_mesos
This is the host of the Mesos master.  To override via the command line, use the following:
`--extra-vars "zk_mesos=1.2.3.4:2181/mesos"`

## master_attributes
This allows specifying Mesos master attributes.  To override via the command line use the following:
`--extra-vars '{"master_attributes": [{"name": "zone", "value": "master"}, {"name": "region", "value": "us-east-1"}]}'`

## slave_attributes
This allows specifying Mesos slave attributes.  To override via the command line use the following:
`--extra-vars '{"slave_attributes": [{"name": "zone", "value": "slave"}, {"name": "region", "value": "us-east-1"}]}'`
