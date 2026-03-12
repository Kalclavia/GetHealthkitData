# Get Healthkit Data (Entitlement)
A very quick bodge forked from [HugeBlack's GetMoreRam Tool](https://github.com/hugeBlack/GetMoreRam). Works the exact same way, but instead enables the [com.apple.developer.healthkit](https://developer.apple.com/documentation/bundleresources/entitlements/com.apple.developer.healthkit) entitlement. This does NOT grant the HealthKit Capabilities entitlement, which is required for access to health records - AFAIK, HealthKit on its own grants everything else (calories, steps, nutrition, etc.).

# How to use
1. Sideload this app
2. Go to settings, sign in your account that you used to sign the app you want to enable "Increased Memory Limit"
3. Go to "App IDs" page
4. Tap Refresh
5. Tap the app you want to enable "Increased Memory Limit"
6. Tap "Add Increased Memory Limit"
7. Reinstall the app from SideStore/AltStore
8. Check if you have "Increased Memory Limit"

# Credits
Stossy11 - For StosSign.
SideStore - Anisette Data fetching codes are stolen from SideStore
HugeBlack - For GetMoreRam, and myriad other projects I use and love <3
