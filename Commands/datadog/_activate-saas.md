# [Command] _datadog activate-saas_

Resolve the token to get the SaaS resource ID and activate the SaaS resource

## Versions

### [2025-12-26-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5kYXRhZG9nL2FjdGl2YXRlc2Fhcw==/2025-12-26-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.datadog/activatesaas 2025-12-26-preview -->

#### examples

- SaaS_ActivateResource
    ```bash
        datadog activate-saas --saas-resource-id "/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myResourceGroup/providers/Microsoft.SaaS/resources/mySaaSResource" --user-info name="Alice" email-address="alice@microsoft.com" phone-number="123-456-7890"
    ```
