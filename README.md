# rosa-hcp-terraform

Terraform sample scripts for ROSA HCP based on official document

## How to use:
 1. set RHCS_TOKEN variable after rosa login
 ```
 export RHCS_TOKEN="$(jq -r .refresh_token ~/.config/ocm/ocm.json)" 
 ```

 2. run terraform 

## Changes from the original: 

Default Machine CIDR is 10.1.0.0/16

