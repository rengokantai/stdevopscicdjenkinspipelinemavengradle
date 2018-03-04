# stdevopscicdjenkinspipelinemavengradle


## CI & CD pipeline With Jenkins, Gradle and Artifactory
### Build CI and CD pipeline with Jenkins and Gradle



## Operational Consideration For Jenkins
### 1 Jenkins Security
configure global security jnlp->java network launch protocol  

some config:
- Security Realm->Jenkins own user database


### 2 Scaling Jenkins
###### 07:20
manage jenkins -> manage nodes ->new node->choose permanent agent.  
For next step
- Use this node as much as possible
- Launch agent via java web start



### 3 Scaling Jenkins (contd.)
Next:
- download jnlp file from master node
