

# PatchDocument

A JSONPatch document as defined by RFC 6902
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**op** | [**OpEnum**](#OpEnum) | The operation to be performed | 
**path** | **String** | JSONPath | 
**from** | **String** | A string containing a JSON Pointer value. |  [optional]
**value** | [**Object**](.md) | The value to be used within the operations. |  [optional]



## Enum: OpEnum

Name | Value
---- | -----
ADD | &quot;add&quot;
REMOVE | &quot;remove&quot;
REPLACE | &quot;replace&quot;



