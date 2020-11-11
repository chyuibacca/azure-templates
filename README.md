# Azure Templates
Collection of Azure Resource Manager templates.


## Running Templates
Subscription-scoped templates can be run via the Azure CLI as follows:

```bash
az deployment sub create -n <deploymnet_name> -l <location> -f <template_file> [-p @<parameters_file>]
```

Resource-scoped templates are run via the Azure CLI as follows:

```bash
az deployment group create -n <deployment_name> -g <resource_group> -f <template_file> [-p @<parameters_file>]
```


## Subscription Scope Templates
| Template | Scope | Description |
|----------|-------|-------------|
| [resource-group](./resource-group.json) | Subscription | Creates a new resource group |
