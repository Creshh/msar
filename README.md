### MSAR
Metadata search and retrieval wrapper project


MSAR is an application where images and corresponding json-based metadata can be stored and retrieved based on the additional data. The data will be generated using frameworks like detectron, yolo9000, facerecognition, etc. It is then indexed by the application using elasticsearch and can be retrieved using a free text search and conditional filtering. The application is generic regarding the structure of the indexed metadata.

# ToDo

- [ ] folder upload
- [ ] logfile after upload
- [x] image deletion with search
- [x] metadata format: 1.jpg_objects.json
- [x] batch download / link list
- [ ] image select / unselect
- [ ] save images in folder (hashvalue, rolling number)

- [ ] query search result in pages (1000 results) and add only reference number to result list which is passed to frontend - no passing of documents to frontend

# Overview
![overview](https://raw.githubusercontent.com/tomkretzschmar/msar/master/doc/draft_overview.png)

# Backend
![overview](https://raw.githubusercontent.com/tomkretzschmar/msar/master/doc/backend_draft.png)

# Frontend
![overview](https://raw.githubusercontent.com/tomkretzschmar/msar/master/doc/frontend_draft.png)

