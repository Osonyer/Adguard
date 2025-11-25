# Allowlist for Gaming Platforms (Steam, PlayStation, Nintendo)

I came across an issue while using the **Ultimate AdGuard block lists** where several gaming platforms **Steam**, **PlayStation**, and **Nintendo** began returning partial or broken site content.

After troubleshooting, Googling, and consistently monitoring my block lists, I created the following **custom allowlist** to restore proper functionality across these platforms.

This repository contains:

* ✔️ A curated **allowlist** for gaming-related domains
* 🎮 Fixes for partial site loading issues
* 🛡️ Compatibility with **AdGuard**, **Pi-hole**, and other DNS-level blockers
* 🔄 Ongoing updates as new domains are identified

## Why This Exists

Certain aggressive block lists unintentionally filter domains required for:

* Game store loading
* Login/authentication
* CDN asset delivery
* Friends lists, images, and profile data
* Game library visibility

This allowlist ensures your gaming platforms operate normally without over-exposing your network.

## How to Use

1. Import the allowlist file into your AdGuard or Pi-hole setup.
2. Restart DNS services.
3. Confirm site functionality on your gaming platforms:

   * Steam Store & Community
   * PlayStation Network
   * Nintendo eShop

## Contributions

Have a domain that should be added? Open an **Issue** or submit a **Pull Request**!
