Who is using Cilium?
====================

Sharing experiences and learning from other users is essential. We are
frequently asked who is using a particular feature of Cilium to get in
contact with other users to share experiences and best-practices. While the
[Cilium Slack community](https://cilium.herokuapp.com/) allows users to
get in touch, it can be challenging to find users of a particular feature
quickly.

The following is a directory of users to help identify users of individual
features. The users themselves directly maintain the list.

Adding yourself as a user
-------------------------

If you are using Cilium, please consider adding yourself as a user with a quick
description of your use case by opening a pull request to this file and adding
a section describing your usage of Cilium. If you are open to others contacting
you about your use of Cilium on Slack, add your Slack nick as well.

    N: Name of user (company or individual)
    D: Description
    U: Usage of features
    L: Link with further information (optional)
    Q: Contacts available for questions (optional)

Example entry:

    * N: Cilium Example User Inc.
      D: Cilium Example User Inc. is using Cilium for scientific purposes
      U: ENI networking, DNS policies, ClusterMesh
      Q: @slacknick1, @slacknick2

Requirements to be listed
-------------------------

 * You must represent the user listed. Do *NOT* add entries on behalf of
   other users.
 * There is no minimum deployment size but we request to list permanent
   deployments only, i.e., no demo or trial deployments. Commercial or
   production use is not required. A well-done home lab setup can be equally
   interesting as a large-scale commercial deployment.

Users (Alphabetically)
----------------------

    * N: Adobe, Inc.
      D: Adobe's Project Ethos uses Cilium for multi-tenant, multi-cloud clusters
      U: L3/L4/L7 policies
      L: https://youtu.be/39FLsSc2P-Y

    * N: Datadog
      D: Datadog is using Cilium in AWS (self-hosted k8s)
      U: ENI Networking, Service load-balancing, Encryption
      Q: @lbernail, @roboll

    * N: Palantir Technologies Inc.
      D: Palantir is using Cilium as their main CNI plugin in AWS (self hosted k8s).
      U: ENI networking, L3/L4 policies, FQDN based policy, FQDN filtering
      Q: ungureanuvladvictor

    * N: Sportradar
      D: Sportradar is using Cilium as their main CNI plugin in AWS (using kops)
      U: L3/L4 policies, Hubble, BPF NodePort, CiliumClusterwideNetworkPolicy
      Q: @Eric Bailey, @Ole Markus

    * N: uSwitch
      D: uSwitch is using Cilium in AWS for all their production clusters (self hosted k8s)
      U: ClusterMesh, CNI-Chaining (with amazon-vpc-cni-k8s)
      Q: @jirving
