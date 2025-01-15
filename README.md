# vm-ware-Issues
 

Error Starting Guest VM in VirtualBox, "VMDK: Inconsistency Between Grain Table And Backup Grain Table.

1. If we are ffacing this on Oracle Virtual Box, we don't have OVM solution, we need to run 

C:\Program Files (x86)\VMware\VMware Workstation>vmware-vdiskmanager.exe -R "D:\VM\ATarget_Terraform_azure_default_1735129888571_17167\box-disk1.vmdk"
The virtual disk, 'D:\VM\ATarget_Terraform_azure_default_1735129888571_17167\box-disk1.vmdk', was corrupted and has been successfully repaired.
