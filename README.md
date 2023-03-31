<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 0.12.7 |
| <a name="requirement_volterra"></a> [volterra](#requirement\_volterra) | >=0.11.19 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_volterra"></a> [volterra](#provider\_volterra) | >=0.11.19 |

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
| <a name="input_azure_region"></a> [azure\_region](#input\_azure\_region) | n/a | `string` | n/a | yes |
| <a name="input_hub_vnet_name"></a> [hub\_vnet\_name](#input\_hub\_vnet\_name) | n/a | `string` | n/a | yes |
| <a name="input_instance_suffix"></a> [instance\_suffix](#input\_instance\_suffix) | n/a | `string` | n/a | yes |
| <a name="input_project_prefix"></a> [project\_prefix](#input\_project\_prefix) | n/a | `string` | n/a | yes |
| <a name="input_resource_group"></a> [resource\_group](#input\_resource\_group) | n/a | `string` | n/a | yes |
| <a name="input_ssh_public_key"></a> [ssh\_public\_key](#input\_ssh\_public\_key) | n/a | `string` | n/a | yes |
| <a name="input_volterra_cloud_cred_azure"></a> [volterra\_cloud\_cred\_azure](#input\_volterra\_cloud\_cred\_azure) | n/a | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_site_name"></a> [site\_name](#output\_site\_name) | n/a |
| <a name="output_site_type"></a> [site\_type](#output\_site\_type) | n/a |
<!-- END_TF_DOCS -->