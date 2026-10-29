### 1. Block Storage (RBD) Stores:

*   **Virtual Machine Disks:** The `.qcow2`, `.raw`, or `.vmdk` files that contain the entire C: drive or root operating system of a virtual cloud server.
*   **Database Storage Engines:** The raw, underlying data directories for relational databases (like **MySQL, PostgreSQL**) and NoSQL databases (like **MongoDB**).
*   **Container Root Volumes:** The persistent storage volumes mounted to **Kubernetes** pods or **Docker** containers to keep their states alive.

### 2. Object Storage (RGW) Stores:

*   **User-Generated Media:** Large collections of **profile pictures, uploaded photos, audio files, and user videos** for mobile or web apps.
*   **Static Website Assets:** The raw **HTML, CSS, JavaScript, and image files** used to serve static web pages.
*   **Cold Backups & Archives:** Large zip files, **database dumps, log files**, and long-term regulatory compliance data.

### 3. File System (CephFS) Stores:

*   **Shared App Code:** Website code or application scripts that **multiple web servers** need to read and execute simultaneously (e.g., a shared `/var/www/` folder).
*   **Corporate Network Shares:** Common office folders (like an **NFS or Samba network drive**) where humans collaborate on Word documents, Excel sheets, and PDFs.
*   **AI/ML Training Data:** Massive datasets of images or text that **multiple GPU cluster nodes** need to read concurrently to train machine learning models.

