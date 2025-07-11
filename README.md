# iCOMcept WinGet manifests

This repository is home to the manifests that are consumed by the [iCOMcept WinGet REST source](https://github.com/iCOMcept/custom-winget-poc).

Manifests are created using the official [Windows Package Manager Manifest Creator](https://github.com/microsoft/winget-create).

The folder structure is modeled after the [Windows Package Manager Community Repository](https://github.com/microsoft/winget-pkgs) to ensure compatibility with the WinGet client.

The underlying installers are served via [Microsoft Azure blob storage](https://portal.azure.com/#view/Microsoft_Azure_Storage/ContainerMenuBlade/~/overview/storageAccountId/%2Fsubscriptions%2F5377ba0d-5397-42b9-a42e-259120b9366b%2FresourceGroups%2FDevPackages%2Fproviders%2FMicrosoft.Storage%2FstorageAccounts%2Fdevpackagesicomcept/path/installers/etag/%220x8DDBDFEB781C4E5%22/defaultId//publicAccessVal/Blob). For simplicity's sake, the storage directory structure mirrors that of the manifests.

> ### This repo is currently stale, as the manifests are now contained in the Azure blob storage as well.
