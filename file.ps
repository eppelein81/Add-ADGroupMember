cls
$username = "Benutzeranmeldename.eingeben"
$gruppenliste = gc "Verzeichnis\Dateiname"

"`n"
"alte Gruppenmitgliedschaften:"
(Get-ADuser -Identity $username -Properties memberof).memberof | Get-ADGroup | Select-Object name | Sort-Object name
"`n"

$gruppenliste | % { `

$gruppe=$_
Add-AdGroupMember -Identity $gruppe -Members $username
}

[System.Windows.Forms.MessageBox]::Show("Neue Gruppen wurden hinzugefügt",0,[System.Windows.Forms.MessageBoxIcon]::None)

pause

"neue Gruppenmitgliedschaften:"
(Get-ADuser -Identity $username -Properties memberof).memberof | Get-ADGroup | Select-Object name | Sort-Object name
