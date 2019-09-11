# GrayLog-JSON-Extractor
going to System -> Input and clicking on the Manage extractors button Next, you need to load a message to extract data from, and select the field containing the JSON document. The following page let you add some extra information to tell Graylog how it should extract the information. Let’s illustrate how a message would be extracted with an example message:
### message
```
{"message":"kambiz kazemi","tag":"kambiz-test"}
```
# Add extractor
```
System -> Input -> Manage Extractor -> Get started -> Load Massage
```
Create JSON extractor for field message
```
Create extractor for field message -> JSON
 ```
