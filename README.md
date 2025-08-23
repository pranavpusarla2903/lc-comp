# 🏆 LeetCode Competition Website

A beautiful, interactive website for tracking weekly LeetCode competitions between friends!

## Features

### 📊 Weekly Input System
- Add multiple participants with custom names
- Input problems solved by difficulty level (Easy, Medium, Hard)
- Automatic points calculation (Easy=1, Medium=2, Hard=3)
- Real-time stats updates as you type

### 📈 Live Statistics
- Total problems solved across all participants
- Total points earned
- Number of participants
- Average problems per participant
- Real-time leaderboard with rankings

### 🏅 Leaderboard System
- Automatic ranking based on points
- Color-coded top 3 positions (Gold, Silver, Bronze)
- Shows individual problem counts by difficulty
- Updates in real-time as you input data

### 📚 Historical Data Tracking
- Save weekly data permanently
- View past weeks' performance
- Compare historical statistics
- Week-by-week leaderboard history

### 💾 Data Persistence
- All data saved locally in your browser
- No server required - works completely offline
- Data persists between sessions
- Option to clear all data if needed

## How to Use

### Getting Started
1. Open `src/index.html` in your web browser
2. The website will automatically load with one participant
3. Add more participants using the "Add Participant" button
4. Rename participants by editing their names in the input fields

### Weekly Input Process
1. **Add Participants**: Click "Add Participant" for each friend joining the competition
2. **Input Problems**: For each participant, enter the number of problems they solved:
   - Easy problems (1 point each)
   - Medium problems (2 points each)
   - Hard problems (3 points each)
3. **Submit Week**: Click "Submit Week" to save the current week's data
4. **View Results**: See the live leaderboard and statistics update automatically

### Viewing Historical Data
1. Go to the "Historical Data" section
2. Select a week from the dropdown menu
3. View that week's complete statistics and leaderboard
4. Compare performance across different weeks

### Data Management
- **Clear Data**: Use the "Clear All Data" button to reset everything
- **Automatic Saving**: All changes are automatically saved to your browser
- **Export Data**: Download a JSON file with all your competition data
- **Import Data**: Upload a previously exported JSON file to restore data
- **Cross-Browser Sync**: Export data and save to GitHub to share across browsers
- **No Account Needed**: Works completely offline with local storage

### Cross-Browser Data Sharing
1. **Export**: Click "Export Data" to download a JSON file with all your competition data
2. **Save to GitHub**: Upload the JSON file to your GitHub repository (e.g., as `competition-data.json`)
3. **Share**: Share the GitHub file link with friends or access it from different browsers
4. **Import**: Use "Import Data" to load the file in any browser or device
5. **Sync**: Repeat export/import whenever you want to update the shared data

**Pro Tip**: Create a GitHub repository for your competition and commit the JSON file after each week's submission for version control!

## Technical Details

### Points System
- **Easy Problems**: 1 point each
- **Medium Problems**: 2 points each  
- **Hard Problems**: 3 points each

### Week Calculation
- Weeks are calculated based on the current date
- Week 1 starts from the beginning of the year
- Automatically determines the current week number

### Browser Compatibility
- Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- Requires JavaScript enabled
- Uses localStorage for data persistence

## Customization

### Adding Features
The website is built with vanilla HTML, CSS, and JavaScript, making it easy to customize:
- Modify the points system in the JavaScript code
- Change colors and styling in the CSS
- Add new statistics or features
- Export data to other formats

### Styling
- Modern gradient design with smooth animations
- Responsive layout that works on mobile and desktop
- Color-coded difficulty levels and rankings
- Hover effects and interactive elements

## File Structure
```
lc-comp/
├── src/
│   └── index.html          # Main website file
└── README.md              # This documentation
```

## Getting Started
Simply open `github.com/username/lc-comp` in your web browser to start using the competition tracker!

---

**Happy coding and good luck with your LeetCode competition! 🚀**
