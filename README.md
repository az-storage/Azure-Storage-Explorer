# Download Azure Storage Explorer

Azure Storage Explorer is a flexible, standalone application designed to simplify the management of your Azure Storage resources. Whether you're dealing with Blob Storage, File Storage, Queues, Tables, or Managed Disks, this tool offers a user-friendly and efficient method for developers and administrators to interact with their storage systems effortlessly.

- [Installation](#installation)
- [System Requirements](#system-requirements)
- [Connecting to Storage](#connecting-to-storage)
   - [Signing in with Azure Active Directory](#signing-in-with-azure-active-directory)
   - [Using Storage Account Name](#using-storage-account-name)
   - [Connecting via Shared Access Signatures (SAS)](#connecting-via-shared-access-signatures-sas)
- [Resources](#resources)

## Installation

To begin using Azure Storage Explorer on Windows, simply download the software and get started by clicking the button below:

[**Download Azure Storage Explorer**](*)

Azure Storage Explorer streamlines cloud storage management with an intuitive interface, offering direct access to your Azure resources. Download the latest version, install it, and use your Azure credentials or access keys to connect. Whether you are managing Blobs, Queues, or Tables, this tool ensures a smooth and efficient workflow.

## System Requirements

### Windows
- **OS:** Windows 10 or newer (64-bit version only)
- **Processor:** 1.4 GHz or greater
- **RAM:** Minimum of 4 GB
- **Disk Space:** At least 500 MB of free space

### macOS
- **OS:** macOS 10.12 (Sierra) or higher
- **Processor:** Intel-based processor
- **RAM:** Minimum of 4 GB
- **Disk Space:** Minimum of 500 MB of free space

### Linux
- **Supported Distributions:** Ubuntu 18.04+, Fedora 30+, CentOS 8+
- **Processor:** 1.4 GHz or faster
- **RAM:** At least 4 GB
- **Disk Space:** Minimum of 500 MB of free space

---

## Connecting to Storage

Azure Storage Explorer provides several methods for connecting to storage accounts, allowing you to choose the most convenient option.

### Signing in with Azure Active Directory
1. Launch Azure Storage Explorer.
2. Select "Add an Account" from the navigation panel.
3. Log in using your Azure Active Directory credentials.
4. After authentication, your subscriptions will be displayed automatically.

### Connecting via Storage Account Name
1. Retrieve your storage account name and access key from the Azure portal.
2. In Storage Explorer, choose "Connect to Azure Storage" and select the "Storage account name and key" option.
3. Enter the required details and choose a display name that is easy to identify.
4. Confirm the settings to finalize the connection.

### Establishing a Connection with Shared Access Signatures (SAS)
1. Create a SAS token in the Azure portal.
2. In Storage Explorer, select "Use a shared access signature (SAS) URI" as the connection method.
3. Paste the SAS URI and verify the connection.
4. You'll now have access to the connected storage resources.

### Local Emulator Integration
- Azure Storage Explorer can also connect to local emulators like Azurite.
- Simply provide the emulator’s URL when setting up the connection.

---

## Managing Your Storage Data

Azure Storage Explorer provides a full suite of tools to efficiently manage different types of storage resources.

### Blob Storage
- **Key Features:** Upload, download, copy, delete, and modify blob data.
- **Common Use Cases:** Storing unstructured data, hosting images, backups.

### File Storage
- **Key Features:** Navigate file systems, upload, download, and organize files.
- **Common Use Cases:** Cloud-based file sharing, effortless data migration.

### Queues
- **Key Features:** Create, modify, and manage message queues.
- **Common Use Cases:** Task scheduling, asynchronous messaging.

### Tables
- **Key Features:** Query, update, and remove table data.
- **Common Use Cases:** Storing semi-structured data, managing key-value pairs.

### Managed Disks
- **Key Features:** View, copy, and manage disk snapshots.
- **Common Use Cases:** Data recovery, backup solutions.

---

## Advanced Features

- **Access Control:** Set up role-based access control (RBAC) and configure shared access policies.
- **Storage Monitoring:** Track performance metrics and view logs.
- **Smooth Integrations:** Seamlessly integrates with Azure Functions, Logic Apps, and more.
- **Customizable Settings:** Adjust network preferences and proxy settings for optimized performance.
