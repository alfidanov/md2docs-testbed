---
title: Markdown List
csh:
    id: "vr-2015"
    title: "CSH title"
    description: "CSH description"
---

# Markdown List Use Cases

## Unordered Lists

Unordered list with -

- First item 11111
- Second item 22222
- Third item 33333
- Fourth item 44444

Unordered list with *

* First item
* Second item
* Third item
* Fourth item

Unordered list with * and -

* First item
* Second item
* Third item
    - Indented item
    - Indented item
* Fourth item

## Ordered Lists

Ordered list with 1. 2. 3. 4.

1. First item
2. Second item
3. Third item
4. Fourth item

Ordered list with 1. 1. 1. 1.

1. First item
1. Second item
1. Third item
1. Fourth item

## Mixed Lists

1. First item
1. Second item
1. Third item
    - Indented item
    - Indented item
1. Fourth item


To create a new Kubernetes cluster configured with VM&nbsp;extensions:

1. Create a VM&nbsp;extensions configuration file. For more information, see [Create a Cluster Configuration File for BOSH VM Extensions](#create-configuration) below.  
1. To create a cluster using a VM&nbsp;extensions file:  

    ```
    tkgi create-cluster CLUSTER-NAME --config-file CONFIG-FILENAME
    ```
    Where:

    * `CLUSTER-NAME` is the name of the cluster to create. 
    * `CONFIG-FILENAME` is the name of the VM extension configuration file created above. 

To configure an existing Kubernetes cluster with VM&nbsp;extensions:

1. Create a VM&nbsp;extensions configuration file. For more information, see [Create a Cluster Configuration File for BOSH VM Extensions](#create-configuration) below.  
1. To modify a cluster using a VM&nbsp;extensions file:  

    ```
    tkgi update-cluster CLUSTER-NAME --config-file CONFIG-FILENAME
    ```
    Where:

    
    * `CLUSTER-NAME` is the name of the cluster to modify. 
    * `CONFIG-FILENAME` is the name of the VM extension configuration file created above. 

   