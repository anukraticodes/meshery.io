---
layout: single-page-model
item-type: model
name: Azure Data Protection
subtitle: Collaborative and visual infrastructure as design for Azure Data Protection
colorIcon: /assets/images/integration/azure-data-protection/icons/color/azure-data-protection-color.svg
whiteIcon: /assets/images/integration/azure-data-protection/icons/white/azure-data-protection-white.svg
docURL: https://docs.meshery.io/extensibility/integrations/azure-data-protection
description: 
category: Provisioning
subcategory: Automation & Configuration
registrant: GitHub
components: 
- name: backup-vault
  colorIcon: assets/images/integration/azure-data-protection/components/backup-vault/icons/color/backup-vault-color.svg
  whiteIcon: assets/images/integration/azure-data-protection/components/backup-vault/icons/white/backup-vault-white.svg
  description: 
- name: backup-vaults-backup-instance
  colorIcon: assets/images/integration/azure-data-protection/components/backup-vaults-backup-instance/icons/color/backup-vaults-backup-instance-color.svg
  whiteIcon: assets/images/integration/azure-data-protection/components/backup-vaults-backup-instance/icons/white/backup-vaults-backup-instance-white.svg
  description: 
- name: backup-vaults-backup-policy
  colorIcon: assets/images/integration/azure-data-protection/components/backup-vaults-backup-policy/icons/color/backup-vaults-backup-policy-color.svg
  whiteIcon: assets/images/integration/azure-data-protection/components/backup-vaults-backup-policy/icons/white/backup-vaults-backup-policy-white.svg
  description: 
componentsCount: 3
relationships: 
- type: "Parent"
  kind: "Hierarchical"
  description: "A hierarchical inventory relationship in which the configuration of (parent component) is patched with the configuration of (child component). "
- type: "Parent"
  kind: "Hierarchical"
  description: "A hierarchical inventory relationship in which the configuration of (parent component) is patched with the configuration of (child component). "
- type: "Non Binding"
  kind: "Edge"
  description: "An edge relationship between BackupVaultsBackupInstance and ManagedCluster(azure-container-service)"
- type: "Non Binding"
  kind: "Edge"
  description: "An edge relationship between BackupVaultsBackupInstance and BackupVaultsBackupPolicy(azure-data-protection)"
relationshipsCount: 4
featureList: [
  "Drag-n-drop cloud native infrastructure designer to configure, model, and deploy your workloads.",
  "Invite anyone to review and make changes to your private designs.",
  "Ongoing synchronization of Kubernetes configuration and changes across any number of clusters."
]
howItWorks: "Collaborative Infrastructure as Design"
howItWorksDetails: "Collaboratively manage infrastructure with your coworkers synchronously sharing the same designs."
---
