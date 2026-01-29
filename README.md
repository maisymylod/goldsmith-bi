# Goldsmith & Co - Analytics Platform

Premium BI dashboard for executive recruiting analytics with ML-powered insights.

## 🚀 Live Demo

Visit: [https://maisymylod.github.io/goldsmith-bi/](https://maisymylod.github.io/goldsmith-bi/)

## 📁 Files to Upload

Upload these **3 files** to your GitHub repository:

```
goldsmith-bi/
├── index.html              # Main analytics dashboard (82KB)
├── candidate-profile.html  # Detailed candidate profile (21KB)
└── README.md              # Documentation (this file)
```

## ✨ Key Features

### Main Dashboard (index.html)

#### **Interactive Resume Previews** 📄✨
- **Hover over any candidate name** to see instant resume popup
- Biography summary
- Complete work history with dates
- "View Full Profile" link
- Smooth slide-in animation

#### **Smart Tab Navigation** ⚪→🟢🔴
- **Current/Former tabs** start transparent
- Turn **green** (Current) or **red** (Former) when clicked
- Visual indicator of active view

#### **Advanced Filtering**
- Filter by recruiter (Joe, Cliff, Audrey, Will, Marc, Theo, Emily)
- Filter by company within each recruiter
- Toggle between Current and Former assignments

#### **Color-Coded Status Badges**
- 🟢 **Active** - Currently interviewing
- 🟠 **Finalist** - Final round stage
- 🔵 **Screening** - Initial screening
- 🟣 **Offer** - Offer negotiation
- ⚫ **Placed** - Successfully placed (Former)

#### **Analytics Sections**
1. **Overview Stats** - Active candidates, open searches, placements, time to fill
2. **Personnel Analytics** - Recruiter performance charts and metrics
3. **Elevation Trends** - ML-powered insights:
   - Characteristic matching (golf hobby detection example)
   - Success rate by channel
   - Goldsmith vs Elevation comparison
   - Top universities placement tracking
4. **LinkedIn Activity** - Recent profile updates by recruiter

### Candidate Profile Page (candidate-profile.html)

Detailed view including:
- Full biography and background
- Previous employment timeline
- Resume preview/download
- G&Co team members assigned
- Client documents with preview:
  - Job Description
  - One-Pager  
  - Assessment Matrix
  - Client Contract (download only)
- Recent activity timeline

## 🎨 Design System

**Typography:**
- Eczar (serif) - Headings and emphasis
- Instrument Sans - Body text
- JetBrains Mono - Dates and technical data

**Color Palette:**
- Gold (#B8956F) - Primary brand
- Charcoal (#1A1A1A) - Text
- Sage Green (#5F7161) - ML sections
- Status: Green/Orange/Blue/Purple/Gray

**Visual Style:**
- Glassmorphism effects
- Smooth animations (0.3s transitions)
- White-glove aesthetic
- Responsive design

## 📊 Sample Data

All data is **completely fictional** for demonstration:

**Companies:** Acme Corp, Dragon Enterprises, Atlantis Corporation, Zenith Industries, Phoenix Solutions, Stardust Enterprises, Crystal Dynamics

**Candidates:** Sterling Archibald Montgomery, Beatrice Wilhelmina Foxworth, Maximus Theodore Blackwell, Octavia Seraphina Waverly, and more

**Recruiters:** Joe Goldsmith (7 searches), Cliff (5 searches), Audrey (5 searches)

## 🔧 Technical Stack

- **Pure HTML5/CSS3/JavaScript** - No build process needed
- **Chart.js** (CDN) - Data visualizations
- **Google Fonts** (CDN) - Typography
- **100% Static** - Works perfectly with GitHub Pages

## 📝 Deployment Steps

### GitHub Pages Deployment (5 minutes)

1. **Create/Use GitHub Repository**
   ```bash
   # Create new repo at github.com or use existing
   # Repository name: goldsmith-bi (or any name you prefer)
   ```

2. **Upload Files**
   - Go to your repository
   - Click "Add file" → "Upload files"
   - Drag and drop these 3 files:
     - `index.html`
     - `candidate-profile.html`
     - `README.md`
   - Commit changes

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: Select `main` branch
   - Folder: Select `/ (root)`
   - Click Save

4. **Access Your Site**
   - Site will be live at: `https://[username].github.io/[repo-name]/`
   - Example: `https://maisymylod.github.io/goldsmith-bi/`
   - May take 1-2 minutes to deploy

### Local Testing

```bash
# Simply open in browser
open index.html

# Or use a local server
python -m http.server 8000
# Visit http://localhost:8000
```

## 🆕 Recent Updates (Jan 29, 2026)

- ✅ Resume preview popups on candidate name hover
- ✅ Biography data for all candidates with employment history
- ✅ Tab styling updated (transparent → colored when clicked)
- ✅ Current/Former assignment filtering
- ✅ Enhanced status color coding
- ✅ Company-based filtering per recruiter
- ✅ Multiple candidates per company (1-2 each)
- ✅ Complete candidate work history timelines

## 🎯 Usage Tips

1. **Hover over candidate names** in the table to see resume previews
2. **Click Current/Former tabs** to switch between active and completed assignments
3. **Select a recruiter** from the dropdown to filter their candidates
4. **Choose a specific company** to see only those candidates
5. **Click status badges** to see color coding (green=active, orange=finalist, etc.)
6. **Navigate to candidate profile** by clicking "View Full Profile" in resume popup

## 📧 Notes

- All candidate and company data is fictional for demonstration
- Charts and metrics are sample data for visualization purposes
- Resume previews appear on right side of screen when hovering
- Fully responsive design works on desktop, tablet, and mobile

---

**Built with Claude** • White-glove recruiting analytics platform
