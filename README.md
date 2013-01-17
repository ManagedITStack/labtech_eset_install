labtech_eset_install
====================

**Original Author:** umarillian, ##labtech IRC channel on FreeNode

**Description:**

Install ESET silently and ignore existing Antivirus products or those that were not uninstalled properly.

Usage
----------
    %windir%\LTSvc\packages\eset\eavbe_nt32_enu.msi IGNORE_CONFLICTS=1 ADMINCFG=%windir%\ltsvc\packages\eset\esetconfig.xml /qn REBOOT=ReallySuppress
