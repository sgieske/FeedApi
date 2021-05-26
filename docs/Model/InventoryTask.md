# # InventoryTask

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**task_id** | **string** | The ID of the task. This ID is generated when the task was created by the createInventoryTask method. | [optional]
**status** | **string** | The status of the task. Users must wait until status is complete before moving on to the next step (such as uploading/downloading a file). For implementation help, refer to &lt;a href&#x3D;&#39;https://developer.ebay.com/api-docs/sell/feed/types/api:FeedStatusEnum&#39;&gt;eBay API documentation&lt;/a&gt; | [optional]
**feed_type** | **string** | The feed type associated with the inventory task. | [optional]
**creation_date** | **string** | The date the task was created. | [optional]
**completion_date** | **string** | The timestamp when the task status went into the COMPLETED, COMPLETED_WITH_ERROR, or PARTIALLY_PROCESSED state. This field is only returned if the status is one of the three completed values. | [optional]
**schema_version** | **string** | The schema version number associated with the task. | [optional]
**detail_href** | **string** | The path to the call URI used to retrieve the task. This field points to the getInventoryTask URI. | [optional]
**upload_summary** | [**\OpenAPI\Client\Model\UploadSummary**](UploadSummary.md) |  | [optional]
**filter_criteria** | [**\OpenAPI\Client\Model\InventoryFilterCriteria**](InventoryFilterCriteria.md) |  | [optional]
**inventory_file_template** | **string** | The inventory file template used to return specific types of inventory tasks, if set in the createInventoryTask method. This field does not apply to LMS_ACTIVE_INVENTORY_REPORT feed types. For implementation help, refer to &lt;a href&#x3D;&#39;https://developer.ebay.com/api-docs/sell/feed/types/api:InventoryFileTemplateEnum&#39;&gt;eBay API documentation&lt;/a&gt; | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
