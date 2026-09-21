# Cloud Storage Types Research

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks similar to a hard drive. | Virtual machines, databases, and operating systems. | AWS EBS |
| File Storage | Stores data as files and folders that can be shared over a network. | Shared files, documents, and applications. | AWS EFS |
| Object Storage | Stores data as objects with metadata inside containers called buckets. | Images, videos, backups, and other unstructured data. | AWS S3 |

## Why Object Storage?

Object Storage is a good choice for storing millions of user-uploaded images
because it is designed for large amounts of unstructured data. It can
store and organize many images using buckets and allows applications to
access the files easily.
