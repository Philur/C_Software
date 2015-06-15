# C_Software

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

Status = GitLab access - OK. Build VS - OK

140612
=========================================
1. Undo of step 10-14 150612 because it is not needed when slave is on the same network
2. Installed Jenkins Tools (copy folder "_Jenkins/Tools")(_Jenkins-Tools.zip)
3. Installed Code Metrics (metrics.exe)
3. Configured job to test Scan Task, Scan compiler errors, Unti Test, Code Coverage and Code Metrics.

Status
GitLab access - OK.
Build VS - OK.
Tasks and Compiler errors - OK.
UT, Code Coverage and Metrics - OK.
