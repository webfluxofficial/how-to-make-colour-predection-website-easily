# 🎮 Color Prediction Game Setup Guide

## 🌟 What You'll Need
- Domain Name (e.g., from GoDaddy)
- Web Hosting (cPanel recommended)
- Game Script Files
- MySQL Database
- Payment Gateway (for withdrawals)

## 🛠️ Full Setup Steps

### 1. Domain + Hosting Setup
```plaintext
1. Buy domain (example: colorwin.com)
2. Purchase hosting (like Hostinger/Bluehost)
3. Connect domain to hosting in cPanel
4. Wait 24 hours for DNS propagation
 ```  

### 2. Script Preparation

1. Remove all backlinks from script
2. Edit files using:
   • MT Manager (for Android)
   • VS Code (for PC/Mac)

### 3. Database Setup
1. Create MySQL database in cPanel
2. Import SQL file (game_db.sql)
3. Update config.php with:
   • Database name
   • Username
   • Password
   
### 4. File Upload
```bash
# Using cPanel File Manager
1. Compress script folder → game.zip
2. Upload to public_html
3. Right-click → Extract
4. Set permissions:
   - Folders: 755
   - Files: 644
```

### 5. Cron Job Setup
```cron
# Set in cPanel → Cron Jobs
* * * * * php /home/username/public_html/cron.php >/dev/null 2>&1
```

### 6. Payment Gateway

 now its time to set a gateway
 
## ⚠️ Important Notes
```diff
+ Works only for WINGO games
- Doesn't support AVIATOR/CRASH games
! Must configure payment gateway
! Daily maintenance required
```

## 🎥 Video Tutorial

https://www.youtube.com/channel/UCBjBcJFHDtjm5PF6XhMs_8g


## 📞 Contact Support
```plaintext
WhatsApp: +91 9320673248
Telegram: https://t.me/webfluxofficial
Email: webflux77@gmail.com
```

*Note: For educational purposes only. Check local regulations before deployment.*


