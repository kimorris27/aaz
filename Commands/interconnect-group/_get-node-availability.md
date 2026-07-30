# [Command] _interconnect-group get-node-availability_

Gets node availability for all subgroups in the specified interconnect group.

## Versions

### [2025-07-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2ludGVyY29ubmVjdGdyb3Vwcy97fS9ub2RlYXZhaWxhYmlsaXR5/2025-07-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/interconnectgroups/{}/nodeavailability 2025-07-01 -->

#### examples

- Get interconnect group node availability
    ```bash
        network interconnect-group get-node-availability --resource-group rg1 --interconnect-group-name test-ig
    ```
