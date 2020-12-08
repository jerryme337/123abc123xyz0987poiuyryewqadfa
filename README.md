Start-Process "$home\downloads\anydesk.exe" -ArgumentList "--install 'C:\Program Files(x86)\AnyDesk' --start-with-win"
echo abc123xyz| anydesk.exe --set-password
