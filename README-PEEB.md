# Changes and Build

Create a new branch off of this one (v0.5.1-peeb at last writing).

Make the change.

Establish a docker-machine env with a local docker machine.

```bash
rm .dapper
```

Then just run "make".  This will use the docker machine entirely for building.  When it is done:

```bash
tar zcvf convoy.tar.gz bin
```

Then check everything in and push -u origin.  Go to github.com/peebles/convoy, releases and make a new release.  Choose
the branch and create a tag w/ same name as branch.  Upload the convoy.tar.gz.

Follow the instructions in open-source-projects/convoy-backups.

