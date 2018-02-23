# Camunda contributions and learnings

We are a small group of developers exploring the use of Camunda BPM in our organisation.  In the past we have worked a lot with Microsoft technologies but, like Microsoft, that is changing.

We are investigating a couple of areas which may be useful to others in the same position:

* integrating Camunda with Microsoft's OAuth authentication server (Active Directory Federation Services / ADFS) and passing authentication tokens retrieved by Camunda to underlying REST APIs both from AngularJs embedded forms and the Camunda server-side components.
* Pushing the capabilities of Tasklist forms and the AngularJs integration while trying to reuse code and build maintainable solutions.

For now this will be a mono-repo, holding code for the Authentication plug-ins we have developed as we as samples and solutions for the problems we feel we need to address for our situation. 
