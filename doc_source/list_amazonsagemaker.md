# Actions, Resources, and Condition Keys for Amazon SageMaker<a name="list_amazonsagemaker"></a>

Amazon SageMaker \(service prefix: `sagemaker`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](http://docs.aws.amazon.com/sagemaker/latest/dg/)\.
+ View a [list of the API operations available for this service](http://docs.aws.amazon.com/sagemaker/latest/dg)\.
+ Learn how to protect this service and its resources by [using IAM](http://docs.aws.amazon.com/sagemaker/latest/dg/authentication-and-access-control.html) permission policies\.

**Topics**
+ [Actions Defined by Amazon SageMaker](#amazonsagemaker-actions-as-permissions)
+ [Resources Defined by SageMaker](#amazonsagemaker-resources-for-iam-policies)
+ [Condition Keys for Amazon SageMaker](#amazonsagemaker-policy-keys)

## Actions Defined by Amazon SageMaker<a name="amazonsagemaker-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. By using policies, you define the permissions for anyone performing an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\. For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  
[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html)

## Resources Defined by SageMaker<a name="amazonsagemaker-resources-for-iam-policies"></a>

The following resource types are defined by this service and can be used in the `Resource` element of IAM permission policy statements\. Each action in the [Actions table](#amazonsagemaker-actions-as-permissions) identifies the resource types that can be specified with that action\. A resource type can also define which condition keys you can include in a policy\. These keys are displayed in the last column of the table\. For details about the columns in the following table, see [The Resource Types Table](reference_policies_actions-resources-contextkeys.md#resources_table)\.


****  

| Resource Types | ARN | Condition Keys | 
| --- | --- | --- | 
| endpoint | arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:endpoint/$\{EndpointName\} |  | 
| endpoint\-config | arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:endpoint\-config/$\{EndpointConfigName\} |  | 
| hyper\-parameter\-tuning\-job | arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:hyper\-parameter\-tuning\-job/$\{HyperParameterTuningJobName\} |  | 
| model | arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:model/$\{ModelName\} |  | 
| notebook\-instance | arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:notebook\-instance/$\{NotebookInstanceName\} |  | 
| notebook\-instance\-lifecycle\-config | arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:notebook\-instance\-lifecycle\-config/$\{NotebookInstanceLifecycleConfigName\} |  | 
| training\-job | arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:training\-job/$\{TrainingJobName\} |  | 

## Condition Keys for Amazon SageMaker<a name="amazonsagemaker-policy-keys"></a>

SageMaker has no service\-specific context keys that can be used in the `Condition` element of policy statements\. For the list of the global context keys that are available to all services, see [Available Keys for Conditions](http://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.