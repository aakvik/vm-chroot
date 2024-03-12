# vm-transfer

Usage vm-transfer
```
vm-transfer --hypervisor <hypervisor_address> --spath <source_path> --tpath <target_path> --sshkey <path_to_sshkey>

Available options:
  --hypervisor | -H : Specify the hypervisor address.
  --spath      | -S : Specify the source path for the data to be transferred.
  --tpath      | -T : Specify the target path where the data will be transferred.
  --sshkey     | -K : Specify the SSH key path for authentication."
```

syncStatus will exit with code 69 if there is active job running, when completed it will exit with 0.
