---
title: Git blobs
shortTitle: Blobs
allowTitleToDifferFromFilename: true
intro: 'The Git blob API lets you create and get a Git blob (binary large object), the object type used to store the contents of each file in a repository.'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
---

## About the Git blob API

A Git blob (binary large object) is the object type used to store the contents of each file in a repository. The file's SHA-1 hash is computed and stored in the blob object. These endpoints allow you to read and write [blob objects](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects)
to your Git database on {% data variables.product.product_name %}. Blobs leverage [these custom media types](#custom-media-types-for-blobs). You can read more about the use of media types in the API [here](/rest/overview/media-types).

### Custom media types for blobs

These are the supported media types for blobs.

    application/json
    application/vnd.github.raw

For more information, see "[Media types](/rest/overview/media-types)."
