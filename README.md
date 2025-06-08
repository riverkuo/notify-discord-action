# 🚀 Discord notification for Github Actions

- Stable version - [v1.0.3](https://github.com/riverkuo/notify-discord-action/releases/tag/v1.0.3)

<br/>

## 🚀 Quick Start

```
- name: Notify Discord
  uses: riverkuo/notify-discord-action@v1.0.3
  if: always()
  with:
    DISCORD_WEBHOOK_URL: ${{ secrets.DISCORD_WEBHOOK_URL }}
```

<br/>

## ⚙️ Configuration

| Variable | Description | Required |
|-----------|----|-------------|
| DISCORD_WEBHOOK_URL | Discord webhook URL | v |

<br/>

## 📪 What you will see

### ✅ Success message ✅
 <img src="https://github.com/riverkuo/blog/blob/master/images/4_1.png?raw=true" width="500px">

 <br/>
 <br/>

### ❌ Failed message ❌
 <img src="https://github.com/riverkuo/blog/blob/master/images/4_2.png?raw=true" width="500px">
