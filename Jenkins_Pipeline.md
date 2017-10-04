Useful links

https://jenkins.io/doc/book/pipeline/getting-started/

https://jenkins.io/doc/pipeline/examples/

https://jenkins.io/doc/book/pipeline/getting-started/#defining-a-pipeline-in-scm

https://jenkins.io/doc/pipeline/steps/


---
#### Defining a Pipeline in SCM
Pipelines can be written into 'jenkinsfile' and checked into a git repo, which jenkins can load via the pipeline script from SCM option.


When the pipeline is configured with SCM polling trigger, an new build is triggered when ever the repository is updated.

The built-in documentation can be found globally at: localhost:8080/pipeline-syntax/, assuming you have a Jenkins instance running on localhost port 8080. The same documentation is also linked as Pipeline Syntax in the side-bar for any configured Pipeline project.

