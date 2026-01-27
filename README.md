# 💉 Personal Insulin Dosage Calculator

A mobile-friendly web application for calculating insulin doses based on your doctor's prescribed protocol. Designed for daily diabetes management with Basaglar (long-acting) and Humalog (rapid-acting) insulin.

![Version](https://img.shields.io/badge/version-2.0.0-blue)
![License](https://img.shields.io/badge/license-Personal%20Use-green)

## ✨ Features

- **📱 Mobile-First Design** - Fully responsive, works on phones, tablets, and desktops
- **🔒 PIN-Protected Admin Panel** - Securely update your insulin protocol values
- **💾 Persistent Storage** - Settings saved locally in your browser
- **📊 Complete Protocol Tables** - Visual reference for all dose ranges
- **⚡ Instant Calculations** - Get your dose in seconds
- **🏠 Install as App** - Add to your iPhone home screen for quick access

## 🚀 Quick Start

### Option 1: Use Online
Simply open the `index.html` file in any web browser.

### Option 2: Install on iPhone (Recommended)
1. Download `index.html` to your device
2. Email it to yourself or save to iCloud
3. Open in **Safari** (must be Safari!)
4. Tap **Share** → **Add to Home Screen**
5. Tap the new icon - works like a native app!

## 📖 How to Use

### Calculate a Dose
1. Enter your current blood sugar (mg/dL)
2. Select meal time (Breakfast, Lunch, or Dinner)
3. Tap **Calculate Humalog Dose**
4. Follow the displayed instructions

### Forgotten Dose Scenario
1. Tap **Forgotten Dose** button
2. Enter current blood sugar
3. Select when you realized you forgot:
   - **During meal** → Takes base dose only
   - **>1 hour after** → Uses correction scale

### Update Protocol (Admin Panel)
1. Tap the ⚙️ button (bottom-right)
2. Enter PIN (default: `1234`)
3. Update any values
4. Tap **Save Changes**

## 📋 Protocol Structure

The calculator uses your doctor's insulin table with:

| Component | Description |
|-----------|-------------|
| **Basaglar** | Long-acting daily dose |
| **Breakfast Humalog** | 10 blood sugar ranges (70 to >400) |
| **Lunch Humalog** | 10 blood sugar ranges |
| **Dinner Humalog** | 10 blood sugar ranges |
| **Correction Scale** | 7 ranges for forgotten doses |

## 🔧 Customization

### Changing Default Values
1. Open Admin Panel (⚙️ button)
2. Enter PIN
3. Modify any values
4. Save changes

### Changing PIN
1. Open Admin Panel
2. Scroll to "Change PIN" section
3. Enter new PIN (minimum 4 characters)
4. Click **Update PIN**

### Reset to Defaults
1. Open Admin Panel
2. Click **Reset to Defaults**
3. Confirm the action

## 💾 Data Storage

All data is stored locally in your browser using `localStorage`:
- `insulinCalc_basaglar` - Daily Basaglar dose
- `insulinCalc_humalog` - All Humalog doses
- `insulinCalc_correction` - Correction scale values
- `insulinCalc_pin` - Admin PIN
- `insulinCalc_lastUpdated` - Last update timestamp

**Note:** Clearing browser data will reset all values to defaults.

## 🏗️ Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks, no dependencies
- **Offline Capable** - Works without internet once loaded
- **Responsive Breakpoints**:
  - Desktop: > 768px
  - Tablet: ≤ 768px
  - Phone: ≤ 480px

## ⚠️ Important Medical Disclaimer

This calculator is a **tool to help follow your doctor's prescribed insulin protocol**. It is NOT a replacement for medical advice.

**Always:**
- ✅ Verify doses with your glucose monitor
- ✅ Consult your doctor with any concerns
- ✅ Follow your doctor's specific instructions
- ✅ Seek immediate medical attention for emergencies
- ✅ Update the protocol only when directed by your doctor

**Never:**
- ❌ Use this as your only source of insulin dosing
- ❌ Change your protocol without medical guidance
- ❌ Ignore symptoms of low or high blood sugar

## 📝 Version History

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

## 🤝 Contributing

This is a personal medical tool. If you'd like to adapt it for your own use:
1. Fork the repository
2. Customize for your doctor's protocol
3. Update default values in the JavaScript

## 📄 License

Personal use only. This calculator is customized for specific insulin protocols as prescribed by a healthcare provider.

---

**Stay healthy! 💪**
# insulin-calculator
