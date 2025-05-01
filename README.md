# office365_deployment

https://config.office.com/

# Need a rollback?
https://support.microsoft.com/en-us/topic/how-to-revert-to-an-earlier-version-of-office-2bd5c457-a917-d57e-35a1-f709e3dda841

### Identify the target version you want:
https://docs.microsoft.com/officeupdates/update-history-office365-proplus-by-date?redirectSourcePath=%252fen-us%252farticle%252fae942449-1fca-4484-898b-a933ea23def7

### Download ODT and extract it
https://www.microsoft.com/download/details.aspx?id=49117

### Edit one of the needed configuration and set the version as needed:
´´´<Configuration>
<Updates Enabled="TRUE" TargetVersion="16.0.xxxxx.yyyyy" />
</Configuration>´´´

### Install
setup.exe /configure config.xml
