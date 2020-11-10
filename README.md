# Azure Templates
Collection of Azure Resource Manager templates.


## Subscription Scope Templates
| Template | Description |
|----------|-------------|
| [resource-group](./resource-group.json) | Creates a new resource group |


## Running Templates

Subscription-level templates can be run via the Azure CLI as follows:

```
az deployment sub create -n <deploymnet_name> -l <location> -f <template_file> [-p @<parameters_file>]
```
