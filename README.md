# Hailstorm Site

This the test application for integration testing of Hailstorm application components.

## AWS Build

**Copy ``setup/vagrant-aws-sample.yml`` to ``setup/vagrant-aws.yml`` and edit the
properties.**

**Install the [Vagrant AWS Plugin](https://github.com/mitchellh/vagrant-aws).**

```bash
➜  hailstorm-site$ vagrant up aws-site --provider=aws
```

## Local DataCenter on Vagrant

```bash
➜  hailstorm-site$ vagrant up /data-center/
```

This will bring up 3 local VMs - one VM acts as the target system and two as load generating agents.
