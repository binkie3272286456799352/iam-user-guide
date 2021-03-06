# Actions, Resources, and Condition Keys for AWS IoT 1\-Click<a name="list_awsiot1-click"></a>

AWS IoT 1\-Click \(service prefix: `iot1click`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](https://docs.aws.amazon.com/iot-1-click/latest/developerguide/)\.
+ View a [list of the API operations available for this service](https://docs.aws.amazon.com/iot-1-click/latest/projects-apireference/)\.
+ Learn how to protect this service and its resources by [using IAM](https://docs.aws.amazon.com/iot-1-click/latest/developerguide/authentication.html) permission policies\.

**Topics**
+ [Actions Defined by AWS IoT 1\-Click](#awsiot1-click-actions-as-permissions)
+ [Resources Defined by IoT 1\-Click](#awsiot1-click-resources-for-iam-policies)
+ [Condition Keys for AWS IoT 1\-Click](#awsiot1-click-policy-keys)

## Actions Defined by AWS IoT 1\-Click<a name="awsiot1-click-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. By using policies, you define the permissions for anyone performing an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\. For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  
[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/IAM/latest/UserGuide/list_awsiot1-click.html)

## Resources Defined by IoT 1\-Click<a name="awsiot1-click-resources-for-iam-policies"></a>

The following resource types are defined by this service and can be used in the `Resource` element of IAM permission policy statements\. Each action in the [Actions table](#awsiot1-click-actions-as-permissions) identifies the resource types that can be specified with that action\. A resource type can also define which condition keys you can include in a policy\. These keys are displayed in the last column of the table\. For details about the columns in the following table, see [The Resource Types Table](reference_policies_actions-resources-contextkeys.md#resources_table)\.


****  

| Resource Types | ARN | Condition Keys | 
| --- | --- | --- | 
|   [ device ](https://docs.aws.amazon.com/iot-1-click/1.0/devices-apireference/resources.html)  |  arn:$\{Partition\}:iot1click:$\{Region\}:$\{Account\}:devices/$\{DeviceId\}  |   [ aws:ResourceTag/$\{TagKey\} ](#awsiot1-click-aws_ResourceTag___TagKey_)   | 
|   [ project ](https://docs.aws.amazon.com/iot-1-click/latest/projects-apireference/API_Operations.html)  |  arn:$\{Partition\}:iot1click:$\{Region\}:$\{Account\}:projects/$\{ProjectName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#awsiot1-click-aws_ResourceTag___TagKey_)   | 

## Condition Keys for AWS IoT 1\-Click<a name="awsiot1-click-policy-keys"></a>

AWS IoT 1\-Click defines the following condition keys that can be used in the `Condition` element of an IAM policy\. You can use these keys to further refine the conditions under which the policy statement applies\. For details about the columns in the following table, see [The Condition Keys Table](reference_policies_actions-resources-contextkeys.md#context_keys_table)\.

To view the global condition keys that are available to all services, see [Available Global Condition Keys](reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.


****  

| Condition Keys | Description | Type | 
| --- | --- | --- | 
|   [ aws:RequestTag/$\{TagKey\} ](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_condition-keys.html#condition-keys-requesttag)  | A tag key that is present in the request that the user makes to IoT 1\-Click\. | String | 
|   [ aws:ResourceTag/$\{TagKey\} ](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_condition-keys.html#condition-keys-resourcetag)  | The preface string for a tag key and value pair attached to an IoT 1\-Click resource\. | String | 
|   [ aws:TagKeys ](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_condition-keys.html#condition-keys-tagkeys)  | The list of all the tag key names associated with the IoT 1\-Click resource in the request\. | String | 