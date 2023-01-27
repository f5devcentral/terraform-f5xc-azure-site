<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 0.12.7 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | >= 2.24 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_volterra"></a> [volterra](#provider\_volterra) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [volterra_azure_vnet_site.azure-site](https://registry.terraform.io/providers/volterraedge/volterra/latest/docs/resources/azure_vnet_site) | resource |
| [volterra_cloud_site_labels.labels](https://registry.terraform.io/providers/volterraedge/volterra/latest/docs/resources/cloud_site_labels) | resource |
| [volterra_tf_params_action.azure-site](https://registry.terraform.io/providers/volterraedge/volterra/latest/docs/resources/tf_params_action) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_azureRegion"></a> [azureRegion](#input\_azureRegion) | n/a | `any` | n/a | yes |
| <a name="input_hubVnetName"></a> [hubVnetName](#input\_hubVnetName) | n/a | `any` | n/a | yes |
| <a name="input_instanceSuffix"></a> [instanceSuffix](#input\_instanceSuffix) | n/a | `any` | n/a | yes |
| <a name="input_projectPrefix"></a> [projectPrefix](#input\_projectPrefix) | n/a | `any` | n/a | yes |
| <a name="input_resourceGroup"></a> [resourceGroup](#input\_resourceGroup) | n/a | `any` | n/a | yes |
| <a name="input_ssh_public_key"></a> [ssh\_public\_key](#input\_ssh\_public\_key) | n/a | `any` | n/a | yes |
| <a name="input_volterraCloudCredAzure"></a> [volterraCloudCredAzure](#input\_volterraCloudCredAzure) | n/a | `any` | n/a | yes |

## Outputs

No outputs.
<!-- END_TF_DOCS -->