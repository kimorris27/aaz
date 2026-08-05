# [Command] _datadog monitor link-saas_

Links a new SaaS to the Datadog organization of the underlying monitor.

## Versions

### [2025-12-26-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kYXRhZG9nL21vbml0b3JzL3t9L2xpbmtzYWFz/2025-12-26-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.datadog/monitors/{}/linksaas 2025-12-26-preview -->

#### examples

- Monitors_LinkSaaS
    ```bash
        datadog monitor link-saas --monitor-name "myMonitor" --resource-group "myResourceGroup" --saas-resource-id "/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myResourceGroup/providers/Microsoft.SaaS/resources/mySaaSResource"
    ```
