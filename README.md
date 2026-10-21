# Visa Guide Website

A comprehensive travel visa resource website with official government links for visa applications and digital arrival cards.

**Live website:** [johnhenrypezzuto.github.io/visa-guide](https://johnhenrypezzuto.github.io/visa-guide/)

## 📁 Structure

```
visa-guide/
├── index.html      # Main website (single-page, responsive)
├── health-data.js  # Health declaration and entry-rule sources for all destinations
└── README.md       # This file
```

## 🌍 Coverage

The website includes **132 destination cards** across 7 regions:

### North America (3 countries)
- United States (ESTA, USCIS)
- Canada (eTA)
- Greenland

### Europe (33 countries)
- All Schengen Area countries (Austria, Belgium, France, Germany, Italy, Spain, etc.)
- Non-Schengen European countries (UK, Ireland, Turkey, Russia, Moldova, etc.)
- Includes ETIAS information for 2026 implementation

### Asia (38 countries)
- East Asia (China, Japan, South Korea, Taiwan, Mongolia)
- Southeast Asia (Thailand, Vietnam, Indonesia, Malaysia, Philippines, Singapore, Cambodia, Laos, Myanmar)
- South Asia (India, Pakistan, Bangladesh, Nepal, Sri Lanka)
- Central Asia (Kazakhstan, Kyrgyzstan, Tajikistan, Uzbekistan)
- Middle East (Saudi Arabia, UAE, Qatar, Kuwait, Oman, Bahrain, Jordan, Israel, Iran, Iraq)
- Caucasus (Armenia, Azerbaijan, Georgia)

### Africa (16 countries)
- Southern Africa (South Africa, Botswana, Namibia, Zimbabwe, Zambia)
- East Africa (Kenya, Tanzania, Uganda, Rwanda, Ethiopia)
- West Africa (Nigeria, Ghana, Senegal)
- North Africa (Egypt, Morocco, Tunisia)

### Oceania (7 countries)
- Australia (ETA)
- New Zealand (NZeTA)
- Pacific Islands (Fiji, Papua New Guinea, Samoa, Tonga, Vanuatu)

### Caribbean (13 countries)
- Greater Antilles (Jamaica, Dominican Republic, Cuba)
- Lesser Antilles (Bahamas, Barbados, Saint Lucia, Antigua and Barbuda, Grenada, Dominica, Saint Vincent)
- Dutch Caribbean (Aruba, Curaçao)
- Other (Cayman Islands, Bermuda, Trinidad and Tobago)

### Latin America (18 countries)
- South America (Brazil, Argentina, Chile, Peru, Colombia, Ecuador, Bolivia, Paraguay, Uruguay, Venezuela, Suriname)
- Central America (Mexico, Guatemala, Costa Rica, Panama, Nicaragua, El Salvador, Honduras)

## 🔗 Link Types

Each country card includes up to three types of links:

1. **🏛️ Official Visa Website** (Green) - Government ministry/embassy visa information
2. **💻 E-Visa Portal** (Blue) - Online visa application systems
3. **📱 Digital Arrival Card** (Yellow) - Electronic arrival/departure cards

## 🩺 Health Information

Health rows are added only when a destination authority or current official entry source identifies a form or rule:

- Required and route-dependent declarations, with a direct submission link where available
- Yellow-fever certificates only when the destination requires them for all arrivals or for travel to named risk areas
- A source link and the date that destination’s health entry information was reviewed

The guide does not infer “no form required” from silence on a visa page. A card without a health row is not a claim that no requirement exists. If an official portal lists a form but does not say who must complete it, the card describes that uncertainty and links to the portal. General route-based yellow-fever certificate rules are not repeated on every card; check the linked CDC destination guidance if your itinerary includes a yellow-fever-risk country. This section covers entry procedures, not personalized medical advice.

## 🎨 Features

- **Responsive Design** - Works on desktop, tablet, and mobile
- **Quick Navigation** - Jump links to each region
- **Visual Legend** - Color-coded link types
- **Country Flags** - Easy visual identification
- **Hover Effects** - Interactive card animations
- **External Links** - All links open in new tabs

## 📝 Maintenance

To update the website:

1. Edit `index.html` for layout and `health-data.js` for per-destination health records
2. Update country information, links, or add new countries
3. Search the destination’s health, immigration, aviation, and arrival-form authorities for current rules; do not rely on a visa landing page or search snippet
4. Use destination-government sources for claims about that destination. State exactly who must file, when, and which routes or local areas trigger a rule; do not infer “not required” from silence
5. Before publishing a temporary outbreak rule, check for a later government notice ending or changing it. Do not treat an old directive or an active form portal as proof that the rule remains in force
6. Keep universal arrival requirements separate from uncommon route-only certificate conditions. Do not copy routine vaccine recommendations into entry requirements
7. Set the destination’s `lastChecked` date only after reviewing the linked source; use CDC destination guidance as a cross-check for yellow-fever routes
8. Update the "Last Updated" date in the footer
9. Recheck official sources before travel; outbreak measures and entry forms can change quickly

## 🚀 Deployment

This is a static HTML file. You can:

- Open directly in a browser for local use
- Host on any web server (Apache, Nginx, etc.)
- Deploy to GitHub Pages, Netlify, Vercel, or similar
- Use with any CDN for global distribution

## 📄 License

Free to use and modify for personal or commercial purposes.

---

**Last Updated:** October 2026
