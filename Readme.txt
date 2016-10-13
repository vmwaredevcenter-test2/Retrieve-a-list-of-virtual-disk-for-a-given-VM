This sample code shows how to retrieve a list of virtual disk for a given VM.

How To Run

In order to run this sample code you must provide four arguments:
[1] The server name or IP address
[2] The user name to log in as
[3] The password to use
[4] The virtual machine IP address.

You will need to get the vim25.jar library from the VMware vSphere JDK.  It is in the
VMware-vSphere-SDK-5.5.0\vsphere-ws\java\JAXWS\lib directory.

You can run this sample code by downloading the zip file below, unzipping it and running a command similar to the following:
java -cp vim25.jar com.vmware.sample.GetVMDiskInfo <ip_or_name> <user> <password> <vm_ip>
For example:
java -cp vim25.jar com.vmware.sample.GetVMDiskInfo 10.20.30.40 JoeUser ps$word 10.20.30.44

Output

You will see the output similar to the following when you run the sample:
Here follows the virtual disks that belongs to the Virtual Machine: 10.20.30.41
Hard disk 1 - capacity: 26,214,400 KB
Hard disk 2 - capacity: 104,857,600 KB
