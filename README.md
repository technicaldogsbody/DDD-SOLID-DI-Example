# DDD-SOLID-DI-Example

I am trying to get to grips with using C# so I thought I would publish my findings, this is very much an adhoc expermintal project, with the only outcome being learning.

## The project specification

This project will take in an XML file, we will call this a source file and convert it to a JSON file, 
this should be refered to as the output file, a mapping file can be used to change the property names returned in the JSON.
The mapping file is expected to follow this format, but could be subject to change.

XMLElementName1|JSONProperty1  
XMLElementName2|JSONProperty2  
XMLElementName3|JSONProperty3

Logging should be done and stored in a seperate JSON file.

