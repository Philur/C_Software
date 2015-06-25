# C_Software

Status
GitLab access - OK.
Build VS and Installation package - OK.
Tasks and Compiler errors - OK.
UT, Code Coverage and Metrics - OK.
Statistics - FxCop, StyleCop - OK.

150612
=========================================
1. Installed Visual Studio Ultimate 2013 with Update 4 (vs_ultimate.exe) with all options and default settings.
2. Rebooted
3. Run Windows Updated and installed everything
4. Installed Git 1.9.4 (Git-1.9.4-preview20140929) with all options and default settings.
5. Installed and updated NotePad ++ ( npp.6.7.5.installer) with all options and default settings.
6. Added slave (build_windows_slave) node @jenkins.ldchome.org
7. Created job (build_test_on_windows_slave) to test git and build from slave
8. Installed JAVA (jre-8u45-windows-i586)
9. Created folder c:\_jenkins_ldchome
10. Put putty.exe in this folder
11. Created bat-file for starting Putty to access ldchome.org
12. Downloaded slave .jar file to the folder
13. Created bat-file for starting jenkins slave
14. Configured "ldchome" settings for Putty including ppk-file

150612
=========================================
1. Undo of step 10-14 150612 because it is not needed when slave is on the same network
2. Installed Jenkins Tools (copy folder "_Jenkins/Tools")(_Jenkins-Tools.zip)
3. Installed Code Metrics (metrics.exe)
4. Installed WiX (wix39.exe)
5. Configured job to test Scan Task, Scan compiler errors, installation package, Unti Test, Code Coverage and Code Metrics.

150623
=========================================
1. Moved SmartFocus jobs to build_windows_slave
2. Moved Casco jobs to build_windows_slave

150624
=========================================
1. Installed FxCop (WinSDK_FxCopSetup.exe)
2. Installed StyleCop (StyleCop-4.7.49.0.msi)
3. Fixed Statistics for SmartFocus (smartfocus & mv solution) - 2 jobs
4. Activated Featurs on server - .NET Framework 3.5 Features.
5. Fixed Statistics for Casco

TODO
=========================================
1. Fix copy of installation from slave to Test PC (test01_win7_slave) (maybe Copy Artifact plugin)

