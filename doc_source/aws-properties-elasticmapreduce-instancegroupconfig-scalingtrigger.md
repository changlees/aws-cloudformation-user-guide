# Amazon EMR InstanceGroupConfig ScalingTrigger<a name="aws-properties-elasticmapreduce-instancegroupconfig-scalingtrigger"></a>

The `ScalingTrigger` property type specifies the conditions that trigger an automatic scaling activity\. `ScalingTrigger` is the property type for the `Trigger` subproperty of the [Amazon EMR InstanceGroupConfig ScalingRule](aws-properties-elasticmapreduce-instancegroupconfig-scalingrule.md) property type\.

## Syntax<a name="w4ab1c21c14e1290b5"></a>

### JSON<a name="aws-properties-elasticmapreduce-instancegroupconfig-scalingtrigger-syntax.json"></a>

```
{
  "[CloudWatchAlarmDefinition](#cfn-elasticmapreduce-instancegroupconfig-scalingtrigger-cloudwatchalarmdefinition)" : CloudWatchAlarmDefinition
}
```

### YAML<a name="aws-properties-elasticmapreduce-instancegroupconfig-scalingtrigger-syntax.yaml"></a>

```
  [CloudWatchAlarmDefinition](#cfn-elasticmapreduce-instancegroupconfig-scalingtrigger-cloudwatchalarmdefinition): CloudWatchAlarmDefinition
```

## Properties<a name="w4ab1c21c14e1290b7"></a>

`CloudWatchAlarmDefinition`  <a name="cfn-elasticmapreduce-instancegroupconfig-scalingtrigger-cloudwatchalarmdefinition"></a>
The definition of a CloudWatch metric alarm\. When the defined alarm conditions are met along with other trigger parameters, scaling activity begins\.  
*Required*: Yes  
*Type*: [Amazon EMR InstanceGroupConfig CloudWatchAlarmDefinition](aws-properties-elasticmapreduce-instancegroupconfig-cloudwatchalarmdefinition.md)