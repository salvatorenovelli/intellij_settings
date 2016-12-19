#Intellij Settings

With this repo, I'd like to store and share my Intellij Setting

##[live_templates.txt][2]

A collection of [Live Templates][1]

###Available templates

- **deflog**: creates a slf4j logger for the class where is created. Example:  
```java
    private static final Logger logger = LoggerFactory.getLogger(MyWonderfulClass.class);
```
- **unsupp**: Throws an UnsupportedOperationException. 

###How to install 

Copy the following XML in your clipboard (CTRL + C)
In Intellij:

- PRESS: `CTRL + SHIFT + A`
- TYPE: `live templates`
- SELECT the entry that will open the "Live templates" setting pane 
   Paste the previously copied XML in any of the live template group, or create a dedicated one.



[1]:https://www.jetbrains.com/help/idea/2016.3/live-templates.html
[2]:live_templates.txt
