# SKO26 Seating Chart - README

## Overview

This is a professional, Appian-branded seating assignment system for the **SKO26 (Sales Kickoff 2026)** event. The system provides an alphabetical directory of all 127 attendees with their table assignments, optimized for diversity across theater regions and industry verticals.

## Features

✅ **Alphabetical Directory** - Complete list of all attendees sorted by last name  
✅ **Real-time Search** - Find attendees by name, theater, industry, or table number  
✅ **Appian Branding** - Official Appian colors (#00A6E0, #212B35, #FF7A00) and Open Sans typography  
✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices  
✅ **Print-Friendly** - Optimized for printing with clean formatting  
✅ **Self-Contained** - Single HTML file with no external dependencies (except Google Fonts)  
✅ **No Installation Required** - Works immediately when opened in any modern browser

## Files Included

```
├── seating_list.html          # Main seating directory (alphabetical)
├── appian_seating_chart.html  # Alternative view (grouped by tables)
├── seating_chart.txt          # Plain text version for reference
├── attendees_clean.csv        # Raw data (CSV format)
└── README.md                  # This file
```

## Quick Start

### Option 1: Open Locally
1. Download `seating_list.html`
2. Double-click to open in your web browser
3. That's it! The seating chart is ready to use

### Option 2: Host on a Web Server
To make it accessible via a URL, upload to any hosting service:

#### GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload `seating_list.html` and rename it to `index.html`
3. Enable GitHub Pages in repository settings
4. Access at: `https://yourusername.github.io/repository-name`

#### Netlify (Free)
1. Visit [netlify.com](https://netlify.com)
2. Drag and drop `seating_list.html` into the deploy area
3. Get instant public URL

#### Vercel (Free)
1. Visit [vercel.com](https://vercel.com)
2. Deploy the HTML file
3. Get instant public URL

#### Company Web Server
1. Upload `seating_list.html` to your company's web server
2. Share the URL with event attendees

## Event Details

- **Total Attendees:** 127
- **Tables:** 18 tables (8 seats each)
- **Theater Distribution:** North America, EMEA, US Public Sector, APJ, Global, CNA, Public Sector
- **Industry Verticals:** Financial Services, Global Public Sector, Broad Markets, Insurance, Life Sciences, No Industry Alignment
- **Diversity Optimization:** 
  - Average 4.2 unique theaters per table
  - Average 5.0 unique industries per table

## Using the Search Feature

The search box allows you to instantly filter attendees:

- **By Name:** Type "Smith" to find all Smiths
- **By Theater:** Type "EMEA" to see all EMEA attendees
- **By Industry:** Type "Financial" to see Financial Services attendees
- **By Table:** Type "5" to see all attendees at Table 5

Search is case-insensitive and searches across all fields simultaneously.

## Customization

### Updating Attendee Data

To modify the attendee list, open `seating_list.html` and locate the `attendees` array in the JavaScript section (around line 250). Each attendee follows this format:

```javascript
{name: "Last, First", table: 1, theater: "Theater Name", industry: "Industry Name"}
```

### Changing Colors

Appian brand colors are defined in the CSS section. To customize:

```css
Primary Blue: #00A6E0
Navy Gray: #212B35
Orange Accent: #FF7A00
Background: #F4F4F4
```

### Modifying Layout

The grid layout can be adjusted in the CSS:

```css
.attendee-row {
    grid-template-columns: 3fr 1fr 2fr 2.5fr;
}
```

## Browser Compatibility

Works in all modern browsers:
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Printing Guidelines

For best printing results:
1. Use **Print to PDF** or a color printer
2. Set orientation to **Portrait**
3. Enable **Background Graphics** for colors
4. Use margins: **0.5 inches** on all sides

The design automatically optimizes for print, hiding the search box and adjusting colors.

## File Versions

### seating_list.html (Recommended)
- Alphabetical directory of all attendees
- Search functionality
- Best for registration desks and attendee self-service

### appian_seating_chart.html
- Grouped by table numbers
- Shows diversity mix for each table
- Best for event planning and table setup

### seating_chart.txt
- Plain text format
- Quick reference without a browser
- Easy to email or share via text

## Technical Details

- **File Size:** ~22 KB (seating_list.html)
- **Load Time:** <1 second on any connection
- **Dependencies:** Google Fonts (Open Sans) - loads from CDN
- **Framework:** Pure HTML/CSS/JavaScript (no libraries required)

## Support & Questions

For questions or modifications:
- Review the inline code comments in the HTML file
- All data is in plain JavaScript arrays for easy editing
- No build process or compilation required

## Version History

- **v1.0** (January 2026) - Initial release
  - Alphabetical seating directory
  - Search functionality
  - Appian branding
  - Responsive design

## License

© 2026 Appian Corporation. All rights reserved.

This seating chart is for internal Appian use at the SKO26 event.

---

**Need Help?** Open the HTML file in a text editor to view the source code and comments.
