# sails-ajax-form-responses
Modified Sails ajax-form-component which allows to fetch the response code from the server

Replace your current "ajax-form-component" with the one in this repository. Works exactly like "cloudError" except you can now add a "cloudResponse" which allows you to check the response of the server. Very useful for applications that send back a JSON response.

```
<ajax-form action="createProduct" :syncing.sync="syncing"
                   :cloud-error.sync="cloudError" :cloud-response.sync="cloudResponse" @submitted="submittedForm()" :handle-parsing="handleParsingForm">
          
</ajax-form>
```
