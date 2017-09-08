# Contensis HTTP Management API

## Introduction
The Management API allows you to create and manage entries within Contensis. 
Our primary aim with this version of the API is to enable you to easily import/integrate content from other systems.

The API is a RESTful service to ensure maximum compatibility, delivering content as JSON and resource files (assets) as text or binary files. We currently provide a .NET client API wrapper to simplify using the API.

## Key concepts

### Projects

|||
|-|-|
| [Get a project](/key-concepts/projects.md#get-a-project) | <span class="label label--get">GET</span> /api/management/projects/**{projectId}**/ |
| [Create a project](/key-concepts/projects.md#create-a-project) | <span class="label label--post">POST</span> /api/management/projects/ |
| [Update a project](/key-concepts/projects.md#update-a-project) | <span class="label label--post">PUT</span> /api/management/projects/**{projectId}**/ |
| [List projects](/key-concepts/projects.md#list-projects) | <span class="label label--get">GET</span> /api/management/projects/ |
| [Delete a project](/key-concepts/projects.md#delete-a-project) | <span class="label label--delete">DELETE</span> /api/management/projects/**{projectId}**/ |


<!-- ### Content Types

|||
|-|-|
| [Get a content type](/key-concepts/content-types.md#get-a-content-type) | <span class="label label--get">GET</span> /api/management/projects/**{projectId}**/contenttypes/**{contentTypeId}** |
| [Create a content type](/key-concepts/content-types.md#create-a-content-type) | <span class="label label--post">POST</span> /api/management/projects/**{projectId}**/contenttypes/ |
| [Update a content type](/key-concepts/content-types.md#update-a-content-type) | <span class="label label--put">PUT</span> /api/management/projects/**{projectId}**/contenttypes/**{contentTypeId}** |
| [Publish a content type](/key-concepts/content-types.md#publish-a-content-type) | <span class="label label--post">POST</span> /api/management/workflow/ |
| [List content types](/key-concepts/content-types.md#list-content-types) | <span class="label label--get">GET</span> /api/management/projects/**{projectId}**/contenttypes/ |
| [Delete a content type](/key-concepts/content-types.md#delete-a-content-type) | <span class="label label--delete">DELETE</span> /api/management/projects/**{projectId}**/contenttypes/**{contentTypeId}**/ | -->

### Entries

|||
|-|-|
| [Get an entry](/key-concepts/entries.md#get-an-entry) | <span class="label label--get">GET</span> /api/management/projects/**{projectId}**/entries/**{entryId}** |
| [Create an entry](/key-concepts/entries.md#create-an-entry) | <span class="label label--post">POST</span> /api/management/projects/**{projectId}**/entries/ |
| [Update an entry variation](/key-concepts/entries.md#update-an-entry) | <span class="label label--put">PUT</span> /api/management/projects/**{projectId}**/entries/**{entryId}**
| [Publish an entry](/key-concepts/entries.md#publish-an-entry) | <span class="label label--post">POST</span> /api/management/workflow/ |
| [List entries](/key-concepts/entries.md#list-entries) | <span class="label label--get">GET</span> /api/management/projects/**{projectId}**/entries/ |
| [List entries by content type](/key-concepts/entries.md#list-entries-by-content-type) | <span class="label label--get">GET</span> /api/management/projects/**{projectId}**/contenttypes/**{contentTypeId}**/entries/ |
| [Delete an entry](/key-concepts/entries.md#delete-an-entry) | <span class="label label--delete">DELETE</span> /api/management/projects/**{projectId}**/entries/**{entryId}**
| [Delete an entry variation](/key-concepts/entries.md#delete-an-entry-variation) | <span class="label label--delete">DELETE</span> /api/management/projects/**{projectId}**/entries/**{entryId}**/**{language}**/
