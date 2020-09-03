# Getting started with Terraform on Alibaba Cloud

## Terraform Configuration
This Terraform configuration will create a VPC with 3 subnets as shown below.
![alibabacloud-setup-diagram](https://github.com/nvinod-net/terraform-alibabacloud-gettingstarted/blob/master/alibabacloud-setup.png)

## Terraform Cloud Environment Varialbles
When using Terraform cloud, set the below environment variables under the workspace:  
ALICLOUD_REGION  
ALICLOUD_ACCESS_KEY  
ALICLOUD_SECRET_KEY  

For Singapore, the region is ap-southeast-1  
[Alibaba Cloud Regions and Zones](https://www.alibabacloud.com/help/doc-detail/40654.htm)

Instruction on how to create the Access Key and Secret Key on Alibaba Cloud refer [article](https://www.alibabacloud.com/help/doc-detail/53045.htm)

## References
[Alibaba Cloud Terraform Provider Documentation](https://registry.terraform.io/providers/aliyun/alicloud/latest/docs)  
[Examples on GitHub](https://github.com/aliyun/terraform-provider-alicloud)
