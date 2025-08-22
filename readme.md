# Abstract Help Center

A responsive help center webpage inspired by Abstract's design, featuring a clean layout with a search functionality and organized topic sections.

## Features

- **Responsive Design**: Mobile-friendly layout that adapts to different screen sizes
- **Interactive Search Bar**: Functional search input with an integrated arrow button
- **Topic Grid**: Organized help topics displayed in a 2-column grid layout on desktop, single column on mobile
- **Clean Navigation**: Header with company branding and action buttons
- **Comprehensive Footer**: Multi-column footer with links and company information

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and CSS Grid
- **Responsive Design**: Media queries for mobile optimization

## Project Structure

```
helppage/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with responsive design
├── images/             # Directory for topic icons
│   ├── icon1.png
│   ├── icon2.png
│   ├── icon3.png
│   ├── icon4.png
│   ├── icon5.png
│   └── icon6.png
└── README.md           # Project documentation
```

## Sections

### Header
- Company logo/title: "Abstract | Help Center"
- Action buttons: "Submit a request" and "Sign in"
- Responsive navigation that stacks vertically on mobile

### Help Section
- Prominent heading: "How can we help?"
- Search bar with integrated arrow button
- Responsive design optimizes search bar for mobile devices

### Topics Section
- Six help topics with icons and descriptions:
  - Using Abstract
  - Manage your account
  - Manage organizations, teams, and projects
  - Manage billing
  - Authenticate to abstract
  - Abstract support
- Grid layout: 2 columns on desktop, 1 column on mobile

### Footer
- Four main columns: Abstract, Resources, Community, Company
- Contact information
- Copyright notice with Abstract logo
- Responsive design stacks columns vertically on mobile

## Responsive Breakpoints

- **Desktop**: Default styles (>768px)
- **Mobile**: Media query adjustments (≤768px)

### Mobile Optimizations
- Header elements stack vertically
- Buttons display in a column layout
- Search bar adjusts padding and font size
- Topic grid becomes single column
- Footer columns stack vertically
- Copyright section repositions for better mobile layout

## Color Scheme

- **Background Colors**:
  - Header/Footer: Black (#000000)
  - Help Section: Light purple (#dadbf1)
- **Text Colors**:
  - Primary: Black (#000000)
  - Header/Footer: White (#fff)
- **Accent Colors**:
  - Sign-in button: Blue (#4C5FD5)

## Typography

- **Primary Font**: 'Roboto', sans-serif (header)
- **Secondary Font**: 'GT America Standard', sans-serif (body/footer)
- **Responsive Font Sizes**: Adjusted for mobile viewing

## Installation & Usage

1. Clone or download the project files
2. Ensure all image files are in the `images/` directory
3. Open `index.html` in a web browser
4. The page is fully responsive and works on all device sizes

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

- Add JavaScript functionality for search
- Implement topic filtering
- Add hover animations
- Include actual search backend integration
- Add accessibility improvements (ARIA labels, keyboard navigation)

## License

This project is for educational/practice purposes. The Abstract branding and design inspiration belongs to Abstract Studio Design, Inc.