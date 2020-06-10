---
layout: project
title: "Apache CouchDB connector for Mule ESB, CloudHub and Anypoint Studio"
subtitle: "Query, add or update CouchDB documents from workflow definitions"
author: "Ruslan Gainutdinov"
header-style: text
tags:
  - Java
  - MuleESB
---

### CouchDB Anypoint Connector

Allows operations in Apache CouchDB (http://couchdb.apache.org).
Uses lightcouch library underneath (http://www.lightcouch.org).

### Supported operations:

- **findById** (find document by CouchDB id)
- **listView** (list documents in view, selecting by key or by range)
- **remove** (removes document by CouchDB id or specified document)
- **findByKey** (finds document in view by key)
- **save** (adds or modifies existing document)

### GitHub releases

This connector is opensource and available on GitHub:

[https://github.com/wizecore/couchdb-connector](https://github.com/wizecore/couchdb-connector)
