go-junit-docker
===============

Docker container that runs Go tests and produces a jUnit style report file.

## Usage

Run this container with your Go app mounted to /go/src/app

```bash
$ docker run --rm -v $PWD:/go/src/app jfrench/go-junit-report
```

## Output

The jUnit XML report will be written to a file called `report.xml` in your app's folder.
test
test

test webhook (view result in logs to the pod)
