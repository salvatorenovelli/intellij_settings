# Intellij Settings

With this repo, I'd like to store and share my Intellij Setting

## [live_templates.txt][2]

A collection of [Intellij Live Templates][1]

### Available templates

- **deflog**: creates a slf4j logger for the class where is created. Example:  
```java
    private static final Logger logger = LoggerFactory.getLogger(MyWonderfulClass.class);
```
- **unsupp**: Throws an UnsupportedOperationException. 
```java
    throw new UnsupportedOperationException("Not implemented yet!");
```

### How to install 

Copy the XML inside [live_templates.txt][2] in your clipboard (CTRL + C)

In Intellij:

- PRESS: `CTRL + SHIFT + A`
- TYPE: `live templates`
- CLICK: `+` and then `Template Group...`
- type group name of your choiche then `return`
- with the group selected PRESS `CTRL + V`



[1]:https://www.jetbrains.com/help/idea/2016.3/live-templates.html
[2]:live_templates.txt
