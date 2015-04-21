# lifelines-studydefinition
Proxy classes for the lifelines study definition service

To query the version number, log onto a service that can contact the service and send a [GetVersion](src/test/resources/GetVersionRequest.xml) request:

```
wget https://*server name*/Umcg.Tcc.GenericLayer.StudyDefinitionService-1/StudyDefinitionService.svc --post-file=request.xml --header="Content-Type: text/xml; charset=utf-8" --header="SoapAction: http://hl7.umcg.nl/GenericLayerStudyDefinitionService/GetVersion”

```

Current version: 1.2.4.0