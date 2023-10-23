---
title: 'Cloud Storage-FUSE'
---

Cloud Storage-FUSE
===

## Cloud Storage-FUSE
--- 
FUSE(Filesystem in Userspace) : an interface used to export a filesystem to the Linux kernel. 

Cloud Storage FUSE allows you to mount GCS buckets as a file system so that applications can access the objects in a bucket using common File IO operations (e.g. open, read, write, close) rather than using cloud-specific APIs.

The Cloud Storage FUSE CSI driver lets you use the Kubernetes API to consume pre-existing GCS buckets as volumes. Your applications can upload and download objects using Cloud Storage FUSE file system semantics. The Cloud Storage FUSE CSI driver provides a fully-managed experience powered by the open source Google Cloud Storage FUSE CSI driver.

The driver natively supports the following ways for you to configure your Cloud Storage-backed volumes:

- CSI ephemeral volumes: You specify the Cloud Storage bucket in-line with the Pod specification. To learn more about this volume type, see the CSI ephemeral volumes overview in the open source Kubernetes documentation.

-  The Cloud Storage FUSE CSI driver lets you use the Kubernetes API to consume pre-existing GCS buckets as volumes. Your applications can upload and download objects using Cloud Storage FUSE file system semantics. The Cloud Storage FUSE CSI driver provides a fully-managed experience powered by the open source Google Cloud Storage FUSE CSI driver.
