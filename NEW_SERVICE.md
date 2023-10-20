# Creating a New Service

WIP

## Is a new service needed?
TODO

## Checklist in creating a new service

1. git clone this repository to a new one.  Set useful repo description.
2. rename all the pointofdelivery pieces to your new service name. (TODO where are all those?)
3. update readme to reflect what this service is about
3. change README sections to be links to README in pointofdelivery (if you don't want to modify those sections, linking to
them in template service means we can update in one repo)
4. create the Jenkin's jobs
  * build
  * contract test?
  * sonar
  * ERD
  * deploy to test
  * deploy to sonar
5. Publish the Service to DockerHub.  Set the description to describe the service's role and link to the GitHub repository.
6. add Service in the Reference Distribution
7. update Read The Docs
8. add Scalyr monitoring/notifications
9. add any desired Slack notifications (such as Github and Jenkins build alerts)
