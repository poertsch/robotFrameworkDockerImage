## Robot framework docker image
This is the base image for testing with Robot Framework

## Description
This image can be used as base image for testing with robot framework. It contains the necessary python installation and robot framework installation.

## Building the container
Build the container with docker. E.g. `docker build -t robotframework:customBuild .`

## Usage
Run the built container with docker. Mount a folder to `/tests` which contains the tests and a folder to `/output` which will contain the report after the tests have finished. E.g. `docker run -v /path/to/tests:/tests -v /path/to/output:/output robotframework:customBuild`