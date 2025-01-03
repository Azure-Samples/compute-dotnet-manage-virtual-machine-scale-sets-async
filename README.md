---
page_type: sample
languages:
- csharp
products:
- azure
extensions:
  services: Compute
  platforms: dotnet
---

# Getting started on managing virtual machine scale sets in C# asynchronously #

 Azure Compute sample for managing virtual machine scale sets with un-managed disks -
  - Create a virtual machine scale set behind an Internet facing load balancer
  - Install Apache Web servers in virtual machines in the virtual machine scale set
  - List scale set virtual machine instances and SSH collection string
  - Stop a virtual machine scale set
  - Start a virtual machine scale set
  - Update a virtual machine scale set
    - Double the no. of virtual machines
  - Restart a virtual machine scale set


## Running this Sample ##

To run this sample:

Set the environment variable `CLIENT_ID`,`CLIENT_SECRET`,`TENANT_ID`,`SUBSCRIPTION_ID` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-dotnet-manage-virtual-machine-scale-sets-async.git

    cd compute-dotnet-manage-virtual-machine-scale-sets-async

    dotnet build

    bin\Debug\net452\ManageVirtualMachineScaleSetAsync.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.