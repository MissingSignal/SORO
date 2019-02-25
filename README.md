# CONTRASTING SENTENCES AS ENGAGEMENT STRATEGY
This project proposes an alternative version of the ontology used by Pepper Robots in project CARESSES.
With the aim of study and improve verbal interactions with people this new version of ontology introduces sentences that contrast the user.

In the CKB folder you will find two ontologies:

| Ontology       | Description                                                 |
| -------------  |:-----------------------------------------------------------:| 
| CKB_std        | The standard ontology, the robot is compliant with the user | 
| CKB_dev        | The proposed ontology, the robot tries to contrast the user |    


## How to run 
- Make sure you have [**Java**](https://www.java.com) installed
- From terminal go to the ```CKB``` folder 
- Take one of the two ontologies, copy and rename it as ```CKB.owl```
- Start the conversation with the command ```java -jar CKB.jar -type 1```
- Enjoy the conversation

### Please Note
During the conversation the ontology is updated according to the user's answers. If you want to start from scratch a new conversation you have to delete the actual ```CKB.owl``` file and replace it with a new one.
