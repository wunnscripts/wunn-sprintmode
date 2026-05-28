```txt
██╗    ██╗██╗   ██╗███╗   ██╗███╗   ██╗    ███████╗ ██████╗██████╗ ██╗██████╗ ████████╗███████╗
██║    ██║██║   ██║████╗  ██║████╗  ██║    ██╔════╝██╔════╝██╔══██╗██║██╔══██╗╚══██╔══╝██╔════╝
██║ █╗ ██║██║   ██║██╔██╗ ██║██╔██╗ ██║    ███████╗██║     ██████╔╝██║██████╔╝   ██║   ███████╗
██║███╗██║██║   ██║██║╚██╗██║██║╚██╗██║    ╚════██║██║     ██╔══██╗██║██╔═══╝    ██║   ╚════██║
╚███╔███╔╝╚██████╔╝██║ ╚████║██║ ╚████║    ███████║╚██████╗██║  ██║██║██║        ██║   ███████║
 ╚══╝╚══╝  ╚═════╝ ╚═╝  ╚═══╝╚═╝  ╚═══╝    ╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝╚═╝        ╚═╝   ╚══════╝
```

# 🏃 Wunn Sprint Mode
A lightweight and optimized sprint mode script for FiveM servers using QBCore. This script allows authorized players/admins to toggle enhanced sprint movement with permission-based access control and clean server-side validation.

---

# 📖 OVERVIEW

Welcome to **Wunn Scripts** — premium FiveM development powered by **Hunna of Hunna Mod Haus**.  
Built for serious servers looking for optimized, clean, immersive, and modern experiences.
From advanced systems to quality-of-life features, Wunn Scripts focuses on:
- ⚡ Performance
- 🧩 Compatibility
- 🎨 Clean UI/UX
- 🔒 Reliable functionality
- 🛠️ Easy configuration

---

# 🏠 ABOUT HUNNA MOD HAUS

**Hunna Mod Haus** is your one-stop creative powerhouse for FiveM assets & server customization.

We specialize in:
- 🎨 Custom & Premade Skins
- 🖋️ Tattoos & Color Tattoos
- 👕 Clothing Packs
- 💇 Hair Packs
- 🧰 Skin Tools
- 📦 Props & Prop Packs
- 🔫 Weapons & Custom Assets
- 🧬 Custom Character Development
- 🛠️ Server Enhancements & More

Whether you're building a luxury RP experience, gang server, serious RP community, or content-driven city — Hunna Mod Haus delivers premium-quality assets designed to stand out.

---

# 🔥 LIFETIME MEMBERSHIP

## 💎 ONE TIME PAYMENT — LIFETIME ACCESS
Become a member of the Haus and unlock exclusive perks instantly.

# 🔥 MEMBERSHIP PERKS

## 🎁 10 FREEBIES EVERY MONTH
Custom assets, tools, or exclusive drops — members eat first.
## 🎉 AUTOMATIC GIVEAWAY ENTRIES
Every giveaway. No reactions needed. No extra steps.
## 💸 10% OFF ALL PURCHASES
Applies to skins, tools, classes, packs, and future releases.
## 💬 PRIVATE MEMBER CHAT ACCESS
Direct communication, support, previews, and community talk.
## 🧬 EXCLUSIVE MEMBER-ONLY ITEMS
Assets & tools never released publicly.
## 👀 FIRST LOOK ACCESS
Early previews of:
- New tools
- Upcoming skins
- Sales & discounts
- Limited drops

---

# 📦 SCRIPT INFORMATION

# 🛠️ FEATURES

- ✅ QBCore Support
- ✅ Lightweight & Optimized
- ✅ Admin Permission Checks
- ✅ ACE Permission Fallback
- ✅ Easy Configuration
- ✅ Clean UI Notifications
- ✅ Toggle Sprint Mode
- ✅ Plug & Play Installation
- ✅ Low Resource Usage

---

# 🔗 DEPENDENCIES

- QBCore Framework

## REQUIRED
- ox_lib (for notifications if configured)

---

# 📥 INSTALLATION

# STEP 1
Drag the script folder into your server resources.

# STEP 2
Ensure the script in your `server.cfg`

```cfg
ensure wunn-sprintmode
```

# STEP 3
Configure the script settings inside:
```lua
config.lua
```

# STEP 4
Restart your server.

---

# ⚙️ CONFIGURATION


ACE Permissions

You may optionally use ACE permissions instead.

Example:
add_ace group.admin sprintmode.admin allow
add_ace group.god sprintmode.god allow

OR 

Edit all customizable options inside:
```lua
config.lua
```

Example:
Config = {}

Config.AllowedGroups = {
    'god',
    'admin'
}

Config.SprintMultiplier = 1.35

---

# 🧩 FRAMEWORK SUPPORT

| Framework | Supported |
|-----------|-----------|
| QBCore | ✅ |


---


# 🛒 PURCHASES & SUPPORT

## 🌐 DISCORD
https://discord.gg/4uzyBRuCxs

For:
- Purchases
- Support
- Custom Orders
- Asset Requests
- Membership Access
- Bug Reports
- Updates

---

# 📜 TERMS

- All sales are final.
- Redistribution is prohibited.
- Leaking/reselling is forbidden.
- Support is provided through Discord only.
- Script may not be claimed as your own.

---

# ❤️ THANK YOU

Thank you for supporting **Wunn Scripts** & **Hunna Mod Haus**.

We appreciate every supporter helping us continue creating premium FiveM experiences for the community.