# Follow the steps to install and run Ghidra on Windows

## Install Java SDK:
   1. download from https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/downloads-list.html
   2. add path of JDK dir (e.g., C:\Program File\java\bin) to environment variable PATH
   3. add environment variable named JAVA_HOME, its value is the install path of JDK
   4. verify java by running "java -v" in cmd.
   
## Install Gradle: 
   1. download from https://gradle.org/releases/
   2. unpack the distribution to the distination folder. For example, unpack the zip file into C:\Gradle. 
   3. add gradle destination path (e.g., C:\Gradle\gradle-7.3.3\bin) to environment variable PATH.
   4. verify gradle by running "gradle -v"
 
## Install Ghidra:
   1. download from https://github.com/NationalSecurityAgency/ghidra/releases
   2. unpack the distribution to the distination folder. For example, unpack the zip file into C:\Ghidra.
   3. build the native binaries for your current platform, execute the following script:
      <GhidraInstallDir>/support/buildNatives.bat    
	  
## Run Ghidra (GUI Mode)
   1. Navigate to <GhidraInstallDir>
   2. Run ghidraRun.bat