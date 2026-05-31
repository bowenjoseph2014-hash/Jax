# UsedHub - Buy & Sell Used Items Website

A modern, responsive website for buying and selling used items including gaming consoles, electronics, furniture, and books.

## 🌐 Live Website

**View the website:** [https://rawcdn.githack.com/bowenjoseph2014-hash/Jax/main/index.html](https://rawcdn.githack.com/bowenjoseph2014-hash/Jax/main/index.html)

Or download and open `index.html` directly in your browser to get started!

## Features

- **Multiple Categories**: Gaming, Electronics, Furniture, and Books
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Item Listings**: Browse featured items with prices, conditions, and seller contact information
- **Sell Form**: Easy-to-use form to list your items for sale
- **Navigation Tabs**: Quick navigation between different product categories
- **Item Cards**: Clean, interactive item cards with hover effects
- **Modern UI**: Professional design with smooth animations and transitions

## File Structure

```
├── index.html       # Main HTML structure
├── styles.css       # Styling and responsive design
├── script.js        # JavaScript functionality
└── README.md        # This file
```

## How to Use

1. **Clone or Download** the repository files
2. **Open** `index.html` in a web browser
3. **Browse Items**: Click on navigation tabs to view items by category
4. **View Details**: Click on any item card to see more information
5. **Sell Items**: Click the "Sell Item" tab to list your used items

## Categories

- **Gaming**: Gaming consoles, controllers, headsets, and accessories
- **Electronics**: Laptops, tablets, cameras, and tech gadgets
- **Furniture**: Desks, chairs, shelves, and home furnishings
- **Books**: Textbooks, novels, and reference books

## Features Included

### Navigation
- Sticky navigation bar with category tabs
- Active tab highlighting
- Responsive mobile menu

### Item Cards
- Clean, modern card design
- Item emoji representation
- Price display
- Condition information
- Seller contact email

### Sell Form
- Title, category, price inputs
- Condition selection
- Detailed description field
- Contact email validation
- Form submission with success notification

### Responsive Design
- Mobile-first approach
- Works on all screen sizes
- Touch-friendly interface
- Optimized for tablets and phones

## Customization

### Adding Items
Edit the `itemsData` object in `script.js` to add more items:
```javascript
gaming: [
    { title: 'Your Item', price: 100, condition: 'Excellent', contact: 'email@example.com', emoji: '🎮' }
]
```

### Changing Colors
Modify the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
}
```

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- No external dependencies required

## Browser Support

- Chrome
- Firefox
- Safari
- Edge
- Mobile browsers

## Future Enhancements

- User authentication
- Database integration for persistent listings
- Image upload functionality
- Search and filter options
- User ratings and reviews
- Payment integration
- Admin dashboard

## License

This project is open source and available for personal and commercial use.

---

**Made with ❤️ for the used items marketplace community**
