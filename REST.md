REST - a mapping between HTTP routes and CRUD

CRUD:
-Create
-Read
-Update
-Destroy

RESTful Routes

Name          Path             HTTP Verb          Purpose
================================================================================
Index         /dogs            GET                List all dogs
New           /dogs/new        GET                Show new dog form
Create        /dogs            POST               Create a new dog, then redirect somewhere
Show          /dogs/:id        GET                Show info about one specific dog
Edit          /dogs/:id/edit   GET                Show edit form for one dog
Update        /dogs/:id        PUT                Update a particular dog, then redirect somewhere
Destroy       /dogs/:id        DELETE             Delete a particular dog, then redirect somewhere