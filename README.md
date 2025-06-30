# Innovation Dashboard

A beautiful, production-ready dashboard for tracking innovation submissions across your organization. Built with React, TypeScript, and Tailwind CSS, featuring real-time data synchronization with Google Sheets.

![Innovation Dashboard](https://images.pexels.com/photos/3184291/pexels-photo-3184291.jpeg?auto=compress&cs=tinysrgb&w=1200&h=400&fit=crop)

## 🚀 Features

- **Real-time Analytics**: Track innovation submissions, contributors, and department participation
- **Google Sheets Integration**: Automatic data synchronization every 5 minutes
- **Beautiful Visualizations**: Interactive charts and graphs using Recharts
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Growth Tracking**: Compare current metrics with previous 7-day periods
- **Department Insights**: Detailed breakdown of submissions by department

## 📊 Dashboard Metrics

1. **Innovation Submissions**: Total submissions with 7-day growth comparison
2. **Active Contributors**: Number of people submitting innovations
3. **Department Participation**: Number of departments actively contributing
4. **Department Analytics**: Detailed charts showing submissions and contributor distribution

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Data Source**: Google Sheets API

## 📋 Prerequisites

- Node.js 16+ and npm
- Google Sheets API key
- Google Sheets document with innovation data

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd innovation-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Google Sheets**
   - Update the API key and Sheet ID in `src/services/googleSheets.ts`
   - Ensure your Google Sheet has the following columns:
     - Innovation Title
     - Submitter
     - Department
     - Submission Date
     - Status

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 📊 Google Sheets Setup

Your Google Sheet should have the following structure:

| Innovation Title | Submitter | Department | Submission Date | Status |
|-----------------|-----------|------------|----------------|--------|
| AI-Powered Tool | John Doe  | Engineering| 2024-01-15     | Approved |
| Process Improvement | Jane Smith | Operations | 2024-01-14 | Pending |

### Required Columns:
- **Innovation Title**: Name of the innovation
- **Submitter**: Person who submitted the innovation
- **Department**: Department of the submitter
- **Submission Date**: Date in YYYY-MM-DD format
- **Status**: Current status (Approved, Pending, etc.)

## 🔧 Configuration

### Google Sheets API Setup

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project or select existing one
3. Enable the Google Sheets API
4. Create credentials (API Key)
5. Update the API key in `src/services/googleSheets.ts`

### Environment Variables

For production deployment, consider using environment variables:

```env
VITE_GOOGLE_SHEETS_API_KEY=your_api_key_here
VITE_GOOGLE_SHEETS_ID=your_sheet_id_here
```

## 📱 Responsive Design

The dashboard is fully responsive and optimized for:
- Desktop (1024px+)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## 🎨 Design Features

- **Modern UI**: Clean, professional design with subtle animations
- **Color System**: Consistent color palette with proper contrast ratios
- **Typography**: Optimized font sizes and spacing for readability
- **Interactive Elements**: Hover states and micro-interactions
- **Loading States**: Elegant loading spinners and error handling

## 📈 Data Visualization

- **Bar Charts**: Department submissions and contributor counts
- **Pie Charts**: Distribution of submissions across departments
- **Metric Cards**: Key performance indicators with growth trends
- **Data Tables**: Detailed department statistics

## 🔄 Auto-Refresh

The dashboard automatically refreshes data every 5 minutes to ensure real-time accuracy. Manual refresh is also available via the header button.

## 🚀 Deployment

### Netlify (Recommended)
```bash
npm run build
# Upload dist folder to Netlify
```

### Vercel
```bash
npm run build
# Deploy using Vercel CLI or web interface
```

### GitHub Pages
```bash
npm run build
# Configure GitHub Pages to serve from dist folder
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

If you encounter any issues or have questions:

1. Check the [Issues](../../issues) page
2. Create a new issue with detailed description
3. Include screenshots if applicable

## 🔮 Future Enhancements

- [ ] User authentication and role-based access
- [ ] Email notifications for new submissions
- [ ] Advanced filtering and search capabilities
- [ ] Export functionality (PDF, Excel)
- [ ] Integration with other data sources
- [ ] Mobile app version

## 📊 Sample Data

The application includes mock data generation for demonstration purposes. In production, ensure your Google Sheet is properly configured with real data.

---

**Built with ❤️ using React, TypeScript, and Tailwind CSS**