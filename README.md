# stdevopscicdjenkinspipelinemavengradle



## Operational Consideration For Jenkins
### 1 Jenkins Security
configure global security jnlp->java network launch protocol  

some config:
- Security Realm->Jenkins own user database


### Scaling Jenkins
###### 07:20
manage jenkins -> manage nodes ->new node->choose permanent agent.  
For next step
- Use this node as much as possible
- Launch agent via java web start



### Scaling Jenkins (contd.)
Next:
- download jnlp file from master node
