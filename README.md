This is a place for sharing useful ElasticSearch queries on [the ProtoCollection/Protokollen database](http://www.protokollen.net).

 * [`queries.json`](https://github.com/jplusplus/protokollen-queries/blob/master/queries.json) contains query snippets. Please add a short description, and the API endpoint to each snippet. This makes it easy to copy-paste and run the snippets in the [Google Chrome Sense extension](https://chrome.google.com/webstore/detail/sense-beta/lhjgkmllcaadmopgmanpapmpjgmfcfig?utm_source=chrome-app-launcher-info-dialog)

 * [`municipalities.md`](https://github.com/jplusplus/protokollen-queries/blob/master/municipalities.md) contains useful selections of municipalities.

Database layout
---------------

The database consists of two indexes: `files` and `documents`. Files contains an index of, well, files. Documents are extracted from files. A document is typically an agenda, an attachment, or the meeting minutes from a meeting.

There can be multiple documents from one meeting.