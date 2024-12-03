# Learn PySpark with me

## Get Started
```bash
$ git clone https://github.com/rungrodkspeed/apache-pySpark
$ docker build -f Dockerfile.workspace -t workspace .
$ docker run -it --rm --name=workspace -v $(pwd):/workspace -p8080:8080 -p4040:4040 workspace bash
$ jupyter lab --ip="*" --port=8080 --no-browser --allow-root
```