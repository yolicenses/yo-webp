# Yo WebP - VSCode Extension

Convert ALL images in Folder to WebP format with a simple right-click!

## ✨ New: Pro Version Available!

**Upgrade to Pro for unlimited conversions and batch processing!**

- 🆓 **Free**: 30 conversions/day
- 💡 **Starter (USD $1)**: 100 conversions/day
- ⭐ **Pro**: Unlimited conversions + batch processing ($9.99/month)

[Learn more about Pro →](https://yo-license.pro)

## Features

### Free Tier 🆓

- 🖱️ **Right-click conversion**: Convert images to WebP directly from the VSCode Explorer
- 📁 **Bulk folder conversion**: Convert all images in a folder (including subfolders) to WebP
- ⚙️ **Customizable settings**: Choose quality, compression level, and whether to delete originals
- ⚡ **Fast**: Powered by a Rust backend for high-performance conversion
- 🔒 **Secure**: Built with security best practices, including path validation and input sanitization
- 🌍 **Cross-platform**: Works on macOS, Windows, and Linux
- 📦 **Supported formats**: PNG, JPG, JPEG, GIF, BMP, TIFF
- 📊 **Daily limits**: 100 single conversions, 3 bulk conversions

### Pro Tier ⭐ ($6.99/month)

- ✨ **Unlimited conversions**: No daily limits
- 🚀 **Batch processing**: Select and convert multiple files/folders at once
- ⚡ **Parallel conversion**: 5x faster processing
- 💼 **Priority support**: Get help within 24 hours
- 🎯 **All Free features included**

### ~~Enterprise Tier~~ 💎 ($49.99/month)

_Currently for display purposes only - not yet available_

- ✨ All Pro features
- 🔥 API access
- 🕵🏼‍♂️ Team management
- 🌏 Custom integrations
- 🔑 SLA guarantee

[Upgrade to Pro →](https://yo-license.pro)

## Usage

### Free Tier Workflow

#### Convert Single Image to WebP

1. In the VSCode Explorer, right-click on any supported image file
2. Select **"Convert to WebP"** from the context menu
3. The converted file will be saved in the same directory with a `.webp` extension

#### Convert ALL images in Folder to WebP (Default Settings)

1. In the VSCode Explorer, right-click on any folder
2. Select **"Convert ALL images in Folder to WebP"** from the context menu
3. All images in the folder and subfolders will be converted using default settings:
   - Quality: 75 (0-100, higher = better quality)
   - Compression: 6 (0-6, higher = better compression)
   - Original files are preserved

#### Convert ALL images in Folder to WebP (Delete Original)

1. In the VSCode Explorer, right-click on any folder
2. Select **"Convert ALL images in Folder to WebP (Delete Original)"** from the context menu
3. Confirm the deletion warning
4. All images in the folder and subfolders will be converted using default settings and original files will be deleted:
   - Quality: 75 (0-100, higher = better quality)
   - Compression: 6 (0-6, higher = better compression)
   - **Original files are deleted after successful conversion**

#### Convert ALL images in Folder to WebP (Custom Settings)

1. In the VSCode Explorer, right-click on any folder
2. Select **"Convert ALL images in Folder to WebP (Custom Settings)"** from the context menu
3. Enter your preferred settings:
   - **Quality**: 0-100 (higher = better quality)
   - **Compression Level**: 0-6 (higher = better compression)
   - **Delete Originals**: Choose whether to delete original files after conversion
4. All images in the folder and subfolders will be converted with your settings

### ⭐ Pro Tier Workflow

#### Batch Convert Multiple Files/Folders

1. **Select multiple items** in Explorer:
   - Hold `Ctrl` (Windows/Linux) or `Cmd` (Mac)
   - Click each file or folder you want to convert
2. Right-click on selection
3. Select **"Convert to WebP (Batch) ⭐"**
4. Watch as all items convert simultaneously!

**Example**: Convert 20 folders at once, or mix 50 files and 10 folders - all in one action!

## Pro Version

### How to Activate Pro

Get the License key on [Go To Dashboard Detail Subscriptions](https://yo-license.pro/dashboard/subscriptions)

1. **Command Palette** method:

   - Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
   - Type "Yo WebP: Activate License"
   - Enter your license key & email address

2. **Settings** method:
   - Open Settings (`File > Preferences > Settings`)
   - Search for "Yo WebP"
   - Enter your license key

### Check License Status

- Command Palette → "Yo WebP: Show License Status"
- View your tier, usage stats, and expiration date

### Pricing

- **Pro**: $6.99/month - Unlimited conversions, batch processing
- **Starter**: $1 +70 conversions/day, 5 bulk/day
- **Free**: 30 conversions/day, 3 bulk/day

### Trial & Refund Policy

- 14-day money-back guarantee
- Cancel anytime, keep Pro access until end of billing period

[Complete Pro Guide →](https://yo-license.pro/dashboard/documentation) | [Privacy Policy →](https://yo-license.pro/privacy-policy) | [Terms of Service →](https://yo-license.pro/terms-of-service)

## Installation

### From Marketplace

_(Coming soon)_

## Commands

- `Yo WebP: Convert to WebP` - Convert single file
- `Yo WebP: Convert ALL images in Folder to WebP` - Convert ALL images in Folder with default settings
- `Yo WebP: Convert ALL images in Folder to WebP (Custom Settings)` - Convert with custom settings
- `Yo WebP: Convert ALL images in Folder to WebP (Delete Original)` - Convert and delete originals
- `Yo WebP: Convert to WebP (Batch) ⭐` - Batch convert (Pro only)
- `Yo WebP: Activate License` - Activate Pro license
- `Yo WebP: Show License Status` - View license and usage info

## Security

This extension implements several security measures:

- ✅ File path validation to prevent directory traversal attacks
- ✅ File extension validation to ensure only supported image formats are processed
- ✅ Input sanitization in both TypeScript and Rust layers
- ✅ No execution of arbitrary commands
- ✅ Minimal dependencies to reduce attack surface

## License

See [LICENSE](https://yo-license.pro/license) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request after Open Ticket with subject Request Github invitation.

## Support

If you encounter any issues or have questions, please file an issue on the [Open Ticket](https://yo-license.pro/dashboard/tickets).
