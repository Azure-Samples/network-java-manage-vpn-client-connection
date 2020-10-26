---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Network
  platforms: java
---

# Getting Started with Network - Manage Vpn Gateway Point2 Site Connection - in Java #


  Azure Network sample for managing virtual network gateway.
  - Create a virtual network with subnets
  - Create virtual network gateway
  - Update virtual network gateway with Point-to-Site connection configuration
  - Generate and download VPN client configuration package. Now it can be used to create VPN connection to Azure.
  - Revoke a client certificate
  <p>
  Please note: in order to run this sample, you need to have:
  - pre-generated root certificate and public key exported to $CERT_PATH file
  For more details please see https://docs.microsoft.com/azure/vpn-gateway/vpn-gateway-certificates-point-to-site for PowerShell instructions
  and https://docs.microsoft.com/azure/vpn-gateway/vpn-gateway-certificates-point-to-site-makecert for Makecert instructions.
  - client certificate generated for this root certificate installed on your machine.
  Please see: https://docs.microsoft.com/azure/vpn-gateway/point-to-site-how-to-vpn-client-install-azure-cert
  - thumbprint for client certificate saved to $CLIENT_CERT_THUMBPRINT
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-manage-vpn-client-connection.git

    cd network-java-manage-vpn-client-connection

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.