MyStuffHub
==========

Teaching resource sharing web app. Well, the start of one - rudiments only(!).

There's a whiteboard shot of some brainstorming. The code that's here relates to a Data Import Handler (DIH) for Apache SOLR to import 
Open Library records into the system and be searchable. OL was going to be used as an initial seed of titles/authors of works to be used
to provide faster data entry for teachers when establishing and publishing their resource collections. There's a unit test for 
it with mocking but, it's been tested against a solr instance and it works. Naive implementation though - the OL dumps to import
are multi-Gb files so some kind of buffered approach to processing them in chunks would be required and to allow stopping/starting
the process.
