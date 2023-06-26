# [Command] _networkfabric fabric list_

List all Network Fabrics in the provided resource group or subscription.

## Versions

### [2023-02-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5tYW5hZ2VkbmV0d29ya2ZhYnJpYy9uZXR3b3JrZmFicmljcw==/2023-02-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.managednetworkfabric/networkfabrics 2023-02-01-preview -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.managednetworkfabric/networkfabrics 2023-02-01-preview -->

#### examples

- List the Network Fabrics for Resource Group
    ```bash
        networkfabric fabric list --resource-group "example-rg"
    ```

- List the Network Fabrics for Subscription
    ```bash
        networkfabric fabric list --subscription "<subscriptionId>"
    ```