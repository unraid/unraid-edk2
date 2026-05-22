# edk2 - OVMF Firmware Repository for Unraid

This repository provides the necessary tools to build edk2 for Unraid including the compiled packages.

## Package contents:
**OVMF_CODE-pure-efi-tpm.fd** - OVMF Firmware with TPM and secure boot enabled  
**OVMF_VARS-pure-efi-tpm.fd** - Configuration file for OVMF Firmware with TPM and secure boot enabled  

**OVMF_CODE-pure-efi.fd** - Default OVMF Firmware  
**OVMF_VARS-pure-efi.fd** - Configuration file for default OVMF Firmware

If a new tag is released in the [tianocore/edk2](https://github.com/tianocore/edk2) repository, a new package will be built and pushed to the [Releases](https://github.com/unraid/unraid-edk2/releases).

Note: The legacy EFI memory attribute revert patch is archived under archive/, and CI now applies the minimal compatibility patch from patches/disable_efi_mem_attr_proto_minimal.patch.

---

**Source Code:** Access the source code for edk2 [here](https://github.com/tianocore/edk2).  
**Older Releases:** For older versions of edk2-unraid, please visit [this link](https://github.com/ich777/edk2-unraid/releases).
