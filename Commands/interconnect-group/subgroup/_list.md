# [Command] _interconnect-group subgroup list_

List all subgroups in an interconnect group.

## Versions

### [2025-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2ludGVyY29ubmVjdGdyb3Vwcy97fS9zdWJncm91cHM=/2025-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/interconnectgroups/{}/subgroups 2025-07-01 -->

#### examples

- List subgroups
    ```bash
        network interconnect-group subgroup list --resource-group rg1 --interconnect-group-name test-ig
    ```
