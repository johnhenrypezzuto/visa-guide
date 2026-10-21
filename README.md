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

All 132 destination cards also show:

- Health declaration guidance, including current nationwide forms and route-dependent forms or screening
- Yellow-fever vaccination certificate entry rules, with a country-specific source
- Direct official entry or health authority links and a per-destination “sources checked” date

“No general form listed” means the linked official entry guidance does not list a routine nationwide health declaration; temporary or route-specific measures can still apply. “Check current rule” flags a source that lists a form but does not clearly say whether all arrivals must use it. Yellow-fever certificates are entry rules, separate from vaccine recommendations, and link to CDC Travelers’ Health or the destination health authority. This section covers entry procedures, not personalized medical advice.

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
3. Use the destination’s official immigration or health authority for health-form rules and link the supporting source directly
4. Set each destination’s `lastChecked` date when you review its sources; link CDC Travelers’ Health for country-specific yellow-fever certificate rules
5. Update the "Last Updated" date in the footer
6. Recheck official sources before travel; outbreak measures and entry forms can change quickly

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
