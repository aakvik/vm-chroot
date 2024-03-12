# vm-sync
A tool for syncing remote disk/image to local disk/image and reset cloud-init config via chroot

Usage vm-transfer
```
vm-transfer -H <hypervisor_address> -S <source_path> -T <target_path> -K <path_to_sshkey>

Available options:
  --hypervisor | -H : Specify the hypervisor address.
  --spath      | -S : Specify the source path for the data to be transferred.
  --tpath      | -T : Specify the target path where the data will be transferred. (defaults to /dev/vdb)
  --sshkey     | -K : Specify the SSH key path for authentication."
```

syncStatus will exit with code 69 if there is active job running, when completed it will exit with 0.
