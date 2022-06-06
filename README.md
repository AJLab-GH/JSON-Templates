# JSON-Templates

Official Fortinet GitHub parameters file (https://github.com/fortinet/azure-templates) can be used with these JSON files. However, as a part of the clean-up of the JSON templates, "AcceleratedNetworking" was changed from a String, to Bool. The same change should be made in the Parameters File for a successful outcome:

From:

        "acceleratedNetworking": {
            "value": "false"
        },

To:

        "acceleratedNetworking": {
            "value": false
        },