# VisualBrainstorming
Simple prototype for an automated visual brainstorming system

Mostly a modification of Google's [sample code](https://github.com/GoogleCloudPlatform/python-docs-samples/tree/master/speech/cloud-client) for Google Speech API.

Does the following.
- Google Speech API to convert spoken phrases during brainstorming to text
- Google Custom Search API to search images related to those keywords
- Sends keyword and image URL via UDP to other visualizing softwares such as Unity
