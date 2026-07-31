# [Command] _datadog monitor manage-sre-agent-connector_

Manages Datadog MCP connectors to add/remove for the SRE Agent.

## Versions

### [2025-12-26-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kYXRhZG9nL21vbml0b3JzL3t9L21hbmFnZXNyZWFnZW50Y29ubmVjdG9ycw==/2025-12-26-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.datadog/monitors/{}/managesreagentconnectors 2025-12-26-preview -->

#### examples

- Monitors_ManageSreAgentConnectors
    ```bash
        datadog monitor manage-sre-agent-connector --monitor-name "myMonitor" --resource-group "myResourceGroup" --action "Add" --mcp-connector-resource-id-list "/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myResourceGroup/providers/Microsoft.Datadog/monitors/myMonitor/mcpConnectors/myConnector"
    ```
