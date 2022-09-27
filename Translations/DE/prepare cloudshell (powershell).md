## Cloud Shell zur späteren Nutzung vorbereiten
1. Melden Sie sich mit den folgenden Anmeldeinformationen beim Azure-Portal (+++https://portal.azure.com/?l=de.de-de+++) an:

    |||
    |--|--|
    |Benutzername|+++@lab.CloudPortalCredential(LabUser).Username+++|
    |Kennwort|+++@lab.CloudPortalCredential(LabUser).Password+++|

1. Wählen Sie in der Symbolleiste oben im Azure-Portal das **Cloud Shell**-Symbol aus.

1. Wählen Sie im Willkommensdialog für Azure Cloud Shell **PowerShell** aus.

1. Wählen Sie auf dem Bildschirm „Für Sie wurde kein Speicher bereitgestellt“ die Option **Erweiterte Einstellungen anzeigen** aus.

1. Füllen Sie in den erweiterten Einstellungen die folgenden Felder aus, und klicken Sie auf **Speicher erstellen**:

    |||
    |--|--|
    |Ressourcengruppe|Eine **andere** Ressourcengruppe als „NetworkWatcherRG“|
    |Speicherkonto (Neu erstellen)|+++cloudshell@lab.LabInstance.Id+++|
    |Dateifreigabe (Neu erstellen)|+++shellstorage+++|
    
    >[!KNOWLEDGE] Falls der Fehler „Kontingent für Mandantenbenutzer überschritten“ angezeigt wird, wählen Sie eine andere **Cloud Shell-Region** aus.

1. Warten Sie, bis die Cloud Shell initialisiert wurde und eine Eingabeaufforderung angezeigt wird, und beenden Sie dann die Shell.
