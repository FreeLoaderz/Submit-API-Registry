# Submit-API-Registry
Freeloaderz SPOs and their associated submit API URL.

When submitting a pull request please add your information in the following format:

```
"Pool_Ticker": { "links": [ 
        { "url": "https://submit.api.com:port/api/submit/tx", "location": "US - East" },
        { "url": "http://submit.api.com:port/api/submit/tx", "location": "UK" },
        { "url": "https://submit-api.org/api/submit/tx", "location": "Spain" }
      ] }
```

You can add one or many links. At least one tx will be submitted as a test prior to merge.

Don't forget to add a comma to the end of the entry before your addition.

To make the merge process as smooth as possible, please allow for approvers to edit the PR.
