# Содержания функции
function Start-MyMorningApps {
    # Вызов всех нужных программ
    Start-Process -FilePath "C:\Users\Desktop\Telegram.lnk"
    Start-Process -FilePath "C:\Users\Public\Desktop\Microsoft Edge.lnk"
    Start-Process -FilePath "C:\Users\Desktop\Obsidian.lnk"
    Start-Process -FilePath "C:\Users\Desktop\Outlook.lnk"
    Start-Process -FilePath "C:\Users\Desktop\Yandex.lnk"
}
# Вызов функции
Start-MyMorningApps
