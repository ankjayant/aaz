# [Command] _mobile-network site create_

Create a mobile network site.

## Versions

### [2022-11-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5tb2JpbGVuZXR3b3JrL21vYmlsZW5ldHdvcmtzL3t9L3NpdGVzL3t9/2022-11-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.mobilenetwork/mobilenetworks/{}/sites/{} 2022-11-01 -->

#### examples

- Create site
    ```bash
        mobile-network create -n mobile-network-name -g rg --identifier "{mcc:001,mnc:01}"
    ```
