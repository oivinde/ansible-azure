# Ansible playbooks for deploying virtual machines in Microsoft Azure

These playbooks uses the certified Azure Collection. Requirements.yml points to local Private Automation Hub, so adjust for your env.

There are two main playbooks in this repository:
- azure_create_vm.yml 
Deploy a single named vm from image. All needed vars are listed. End of playbook also sets variables used in my workflows. 

- azure_create_vms.yml
Older playbook to just deploy x number of instances from an image. Needs cleaning up.

- azure_delete_demo_env.yml
Just deletes defined Azure resource_group

- azure_upload_and_create_image.yml
Upload and create vm image in Azure.

