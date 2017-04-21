# alfresco-simple-action
Sandbox example of a simple Alfresco action created with generator-alfresco and some share configuration.

The generator-alfresco (https://github.com/binduwavell/generator-alfresco) project was used to generate the repository side of 
the action. The share side of things had to be made manually.

(see details on how to use the generator-alfresco project on the link above)

The repo side of the action was created by the command
`$ yo alfresco:action` and this generated the action files found in the repo-amp folder. On the share side it was only necessary 
to create the file `share-repo/src/main/resources/META_INF/share-config-custom.xml`. and edit this. See more comment in this file 
about which changes were necessary.
