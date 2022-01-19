# dataverse-dans-metrics

Dataverse DANS metrics aggregates metrics from the DANS DataverseNL installation and visualizes them on a web page. 
It makes use of the DANS extension of the Dataverse Metrics API. This extension allows to aggregate metrics for specific dataverses. 

This DANS metrics page (html+javascript) is hardwired to the verses of the institutions in DataverseNL. Note that this is al client side code and there is no server side scripting or page generation in this version. 

**Tips for testing:**
Open the index.html file in a browser from this project, for instance from within the editor (IntelliJ IDEA). 
Change the strings `DATAVERSE_BASE_URL` and `DOI_PREFIX` to real values for an actual server (like dataverse.nl). 
Then reload the page, or have the editor do it automatically, 
and then you should see a correctly working page. 


