# Actions, Resources, and Condition Keys for AWS IoT Events<a name="list_awsiotevents"></a>

AWS IoT Events \(service prefix: `iotevents`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](https://docs.aws.amazon.com/iotevents/latest/developerguide/)\.
+ View a [list of the API operations available for this service](https://docs.aws.amazon.com/iotevents/latest/apireference/)\.
+ Learn how to protect this service and its resources by [using IAM](https://docs.aws.amazon.com/iotevents/latest/developerguide/auth-and-access-control.html) permission policies\.

**Topics**
+ [Actions Defined by AWS IoT Events](#awsiotevents-actions-as-permissions)
+ [Resources Defined by IoT Events](#awsiotevents-resources-for-iam-policies)
+ [Condition Keys for AWS IoT Events](#awsiotevents-policy-keys)

## Actions Defined by AWS IoT Events<a name="awsiotevents-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. By using policies, you define the permissions for anyone performing an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\. For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  
[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/IAM/latest/UserGuide/list_awsiotevents.html)

## Resources Defined by IoT Events<a name="awsiotevents-resources-for-iam-policies"></a>

The following resource types are defined by this service and can be used in the `Resource` element of IAM permission policy statements\. Each action in the [Actions table](#awsiotevents-actions-as-permissions) identifies the resource types that can be specified with that action\. A resource type can also define which condition keys you can include in a policy\. These keys are displayed in the last column of the table\. For details about the columns in the following table, see [The Resource Types Table](reference_policies_actions-resources-contextkeys.md#resources_table)\.


****  

| Resource Types | ARN | Condition Keys | 
| --- | --- | --- | 
|   [ detectorModel ](https://docs.aws.amazon.com/iotevents/latest/developerguide/iotevents-getting-started.html)  |  arn:$\{Partition\}:iotevents:$\{Region\}:$\{Account\}:detectorModel/$\{DetectorModelName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#awsiotevents-aws_ResourceTag___TagKey_)   | 
|   [ input ](https://docs.aws.amazon.com/iotevents/latest/developerguide/iotevents-getting-started.html)  |  arn:$\{Partition\}:iotevents:$\{Region\}:$\{Account\}:input/$\{inputName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#awsiotevents-aws_ResourceTag___TagKey_)   | 

## Condition Keys for AWS IoT Events<a name="awsiotevents-policy-keys"></a>

AWS IoT Events defines the following condition keys that can be used in the `Condition` element of an IAM policy\. You can use these keys to further refine the conditions under which the policy statement applies\. For details about the columns in the following table, see [The Condition Keys Table](reference_policies_actions-resources-contextkeys.md#context_keys_table)\.

To view the global condition keys that are available to all services, see [Available Global Condition Keys](reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.


****  

| Condition Keys | Description | Type | 
| --- | --- | --- | 
|   aws:RequestTag/$\{TagKey\}  | A tag key that is present in the request that the user makes to IoT Events\. | String | 
|   aws:ResourceTag/$\{TagKey\}  | The tag key by which a tag value is attached to an IoT Events resource\. | String | 
|   aws:TagKeys  | The list of all the tag key names associated with the IoT Events resource in the request\. | String | 