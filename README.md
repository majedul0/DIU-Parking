# DIU Vehicle Parking System
---

A modern, responsive web-based parking management system built with HTML and CSS.

## Features

### 🎓 **DIU University Branding**
- Official DIU logo integration
- University color scheme (Navy Blue & Blue)
- Professional academic appearance
- Brand-consistent design elements

### 👤 **Demo User Information**
- **Name**: Sahik
- **Student ID**: 0242220005101253
- **Role**: Student
- **Vehicle**: DH-5678-9012 (Car)

### 💰 **Currency**
- **Primary Currency**: Bangladeshi Taka (৳)
- **Parking Rates**: ৳10-৳50 per hour
- **Wallet Balances**: ৳150
- **Transaction Amounts**: ৳20-৳2,500
- **All monetary values** displayed in Taka throughout the system

### 🚗 **Smart Parking Management**
- User registration and authentication
- Vehicle information management
- Multiple vehicle type support
- Secure login system

### 🎨 **Modern UI/UX Design**
- Responsive design for all devices
- Beautiful gradient backgrounds
- Smooth animations and transitions
- Professional color scheme
- Font Awesome icons integration

### 📱 **Responsive Design**
- Mobile-first approach
- Tablet and desktop optimized
- Touch-friendly interface
- Adaptive layouts

## File Structure

```
smart-parking-system/
├── index.html          # Login page
├── signup.html         # Registration page
├── dashboard.html      # Main dashboard
├── book-parking.html   # Book parking spots
├── find-parking.html   # Find parking with map
├── history.html        # Parking history & records
├── payments.html       # Payment & wallet management
├── settings.html       # User settings & preferences
├── styles.css          # Login/Signup styles
├── dashboard.css       # Dashboard & other pages styles
├── find-parking.css    # Enhanced find parking styles
└── README.md           # This file
```

## Pages

### 1. Login Page (`index.html`)
- Email and password authentication
- Remember me functionality
- Forgot password link
- Link to signup page
- Beautiful right-side information panel

### 2. Signup Page (`signup.html`)
- Comprehensive registration form
- Personal information fields
- Vehicle details
- Password confirmation
- Terms and conditions agreement
- Link back to login page

### 3. Dashboard (`dashboard.html`)
- **User Management**: Shows user role (Student/Teacher/Employee)
- **Real-time Stats**: Available parking spots, active parking, monthly sessions, balance
- **Parking Spots**: Live view of available and occupied spots with booking functionality
- **Recent Activity**: Track parking entry/exit, payments, and bookings
- **Quick Actions**: Find spots, extend parking, add balance, download receipts
- **Zone Information**: Detailed view of different parking zones with availability status
- **Responsive Design**: Works perfectly on all devices

### 4. Book Parking (`book-parking.html`)
- **Spot Selection**: Choose from available parking zones and spots
- **Time Booking**: Select date, time, and duration for parking
- **Payment Options**: Multiple payment methods including wallet and cards
- **Real-time Pricing**: Dynamic pricing based on zone and duration
- **Booking Confirmation**: Complete booking process with confirmation

### 5. Find Parking (`find-parking.html`)
- **Interactive Map**: Visual representation of DIU campus parking zones
- **Search & Filters**: Find parking by vehicle type, price, and availability
- **Real-time Availability**: Live updates of parking spot status
- **Zone Information**: Detailed zone descriptions and pricing
- **Quick Actions**: Find nearest spots, get directions, quick booking
- **Enhanced UI**: Beautiful gradients, smooth animations, and responsive design
- **Interactive Elements**: Hover effects, loading states, and visual feedback

### 6. History (`history.html`)
- **Parking Records**: Complete history of all parking sessions
- **Transaction History**: Payment records and receipts
- **Statistics**: Yearly parking statistics and analytics
- **Export Options**: Download history in various formats
- **Filtering**: Search by date, zone, and status

### 7. Payments (`payments.html`)
- **Wallet Management**: Add funds, check balance, view transactions
- **Payment Methods**: Credit cards, UPI, bank transfer, wallet
- **Transaction History**: Complete payment records
- **Auto-recharge**: Set up automatic wallet top-up
- **Receipts**: Download payment receipts and statements

### 8. Settings (`settings.html`)
- **Profile Management**: Update personal information and avatar
- **Preferences**: Language, theme, timezone, and parking preferences
- **Notifications**: Customize notification settings for different events
- **Security**: Password change, 2FA, login history
- **Vehicle Management**: Add, edit, and manage registered vehicles

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation
1. Download or clone the project files
2. Open `index.html` in your web browser
3. Navigate between login and signup pages using the provided links

### Development Setup
For development purposes, you can use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Customization

### Colors
The main color scheme uses DIU university branding:
- Primary: `#1a4b84` (DIU Navy Blue)
- Secondary: `#2c5aa0` (DIU Blue)
- Accent: `#ffd700` (Gold)

### Fonts
The system uses Google Fonts (Poppins). You can change this by:
1. Selecting a different font from [Google Fonts](https://fonts.google.com/)
2. Updating the font-family in the CSS file

### Icons
Font Awesome icons are used throughout. You can:
- Change icon classes in the HTML files
- Visit [Font Awesome](https://fontawesome.com/) for more icon options

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Features in Detail

### Form Validation
- HTML5 form validation
- Required field indicators
- Email format validation
- Password visibility toggle

### Animations
- Smooth fade-in effects for form elements
- Hover animations on buttons and inputs
- Loading states for form submission
- Responsive transitions

### Accessibility
- Semantic HTML structure
- Proper labeling for screen readers
- Keyboard navigation support
- High contrast color scheme

## Future Enhancements

This is a frontend template that can be extended with:
- Backend integration (Node.js, Python, PHP)
- Database connectivity
- User authentication system
- Parking spot management
- Payment integration
- Real-time parking availability
- Mobile app development

## Contributing

Feel free to contribute to this project by:
- Reporting bugs
- Suggesting new features
- Submitting pull requests
- Improving documentation

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help or have questions:
- Create an issue in the project repository
- Contact the development team
- Check the documentation

---

**Built with ❤️ for smart parking solutions**
