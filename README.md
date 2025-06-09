# Содержания функции
function Start-MyMorningApps {
    # Вызов всех нужных программ
    Start-Process -FilePath "C:\Users\G.Kudriashov\Desktop\Telegram.lnk"
    Start-Process -FilePath "C:\Users\Public\Desktop\Microsoft Edge.lnk"
    Start-Process -FilePath "C:\Users\G.Kudriashov\Desktop\KeePass(Kappa)_in.rdp"
    Start-Process -FilePath "C:\Users\G.Kudriashov\Desktop\Obsidian.lnk"
    Start-Process -FilePath "C:\Users\G.Kudriashov\Desktop\Outlook.lnk"
    Start-Process -FilePath "C:\Users\G.Kudriashov\Desktop\Yandex.lnk"
}

# Вызов функции
Start-MyMorningApps
