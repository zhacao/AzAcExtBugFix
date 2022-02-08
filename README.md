# AzAcExtBugFix
Fix VSCode Azure Automation extension does not support Azure China and directory structure issue.

Suitable for v1.0.14 

Copy and replace the modules directory to extension installation directory


25/01/2022
Bug Fix:
1. Support Azure China Cloud
2. Fix local runbook directory structure issue and let runbook file save under VScode workspace directory. 


08/02/2022

Bug Fix:
1. Remove System workgroup from workergroup list, becasue system workgroup is only for automation patch update feature, not suitable for normal runbook running.

Add new feature
1. Add PowerShell workflow runbook support.

