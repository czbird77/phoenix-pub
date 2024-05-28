Phoenix dependecies:
---------------------------
1. Local user must have local admin rights (Phoenix was not tested without them, so there might be unforseen consequences)

2. Oracle client 64-bit must be present

    Option (A) - FULL CLIENT

      Download and install full Oracle Client (min. v19 64-bit).
      Follow instructions provided in the installation procedure.
      Reboot the computer after the installation is complete.

    Option (B) - INSTANT CLIENT

      Following Oracle Instant Client binaries are provided in addons subfolder:
       - ora19.zip [recommended]
       - ora21.zip
      Choose client version you want to use.
      Create \ora subfolder in your local Phoenix folder (where phoenix.exe is).
      Download the archive and unpack it into the created \ora subfolder.
      Phoenix will automatically use Oracle client located in \ora subfolder, if there is one.

    NOTES:

      Do not use Oracle Client v11 or older (neither full nor instant).

Optional Tibco JMS support:
---------------------------
If you want to use JMS calls from Phoenix to Tibco EMS, 
download tibco.zip archive from addons subfolder,
and unpack it into your local Phoenix folder (where phoenix.exe is).
Restart Phoenix if already running.
