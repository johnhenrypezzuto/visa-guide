# Visa Guide Website

A comprehensive travel visa resource website with official government links for visa applications and digital arrival cards.

**Live website:** https://johnhenrypezzuto.github.io/visa-guide/

## 📁 Structure

```
visa-guide/
├── index.html      # Main website (single-page, responsive)
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

Each destination card also shows:

- Health declaration form status
- Health-related entry requirements, including route-dependent rules where verified
- Destination-government source links and a per-destination review date; unverified items link to an official travel or immigration page for confirmation

Information without a current supporting government source is labeled **Not verified**. Travelers should confirm current requirements with the linked authority before departure.

## 🎨 Features

- **Responsive Design** - Works on desktop, tablet, and mobile
- **Quick Navigation** - Jump links to each region
- **Visual Legend** - Color-coded link types
- **Country Flags** - Easy visual identification
- **Health Filter** - Find destinations with required, conditional, or unverified health information
- **Hover Effects** - Interactive card animations
- **External Links** - All links open in new tabs

## 📝 Maintenance

To update the website:

1. Edit `index.html` directly
2. Update country information, links, or add new countries
3. Update the country's health declaration and entry-rule record using destination-government sources; leave unsupported details marked "Not verified"
4. Set a country-specific `lastChecked` date in `healthRecords` when you verify its sources; unverified records use `healthCheckedDate` as the fallback date
5. Update the "Last Updated" date in the footer
6. Test all links periodically

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
