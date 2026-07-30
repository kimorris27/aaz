# [Command] _interconnect-group subgroup show_

Get the specified subgroup in an interconnect group.

## Versions

### [2025-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2ludGVyY29ubmVjdGdyb3Vwcy97fS9zdWJncm91cHMve30=/2025-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/interconnectgroups/{}/subgroups/{} 2025-07-01 -->

#### examples

- Get subgroup
    ```bash
        network interconnect-group subgroup show --resource-group rg1 --interconnect-group-name test-ig --subgroup-name subgroup0
    ```
