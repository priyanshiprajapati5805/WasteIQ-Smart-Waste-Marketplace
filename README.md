# WasteIQ — Smart Waste & Resource Exchange Platform

**Turning Waste into a Valuable Resource**

WasteIQ is a web-based platform designed to connect waste suppliers with buyers who can reuse or recycle waste materials. It aims to reduce waste, encourage resource reuse, and support a more sustainable and circular economy.

## Problem Statement

A significant amount of reusable waste is discarded because waste generators and businesses that need those materials often lack a common platform to connect.

This creates several problems:

- **Waste Mismanagement:** Reusable materials may be thrown away instead of being reused or recycled.
- **Lack of Connectivity:** Suppliers and potential buyers struggle to find each other.
- **Limited Visibility:** Information about available waste materials, quantities, prices, and locations is scattered.
- **Resource Wastage:** Useful materials are lost instead of being converted into valuable resources.
- **Inefficient Communication:** Buyers and suppliers need a convenient way to discuss materials and purchase requests.

There is a need for a centralized platform that makes waste materials easier to discover, exchange, and reuse.

## Proposed Solution

WasteIQ provides a common digital marketplace where suppliers can list available waste materials and buyers can browse listings, view material details, and send purchase requests.

The platform aims to make waste exchange more organized, accessible, and convenient while encouraging sustainable resource management.

By connecting suppliers and buyers, WasteIQ helps turn potentially discarded materials into useful resources.

## Key Features

### 1. User Authentication

- Login and Sign Up interface.
- Supplier and Buyer role selection.
- Basic browser-based authentication for the current prototype.
- Login-first navigation to protect access to other pages in the demo.

### 2. Home Page

- Introduction to the WasteIQ platform.
- Overview of the waste exchange concept.
- Navigation to the marketplace and other sections.

### 3. Waste Marketplace

- Browse available waste materials.
- View material names, categories, quantities, prices, and locations.
- Explore listings to identify materials that may be useful.

### 4. Add Waste Listing

- Create a listing for available waste materials.
- Enter material details, quantity, price, location, and description.
- Include supplier information and a product photo when supported by the form.

### 5. Waste Details

- View detailed information about a selected listing.
- Check the material's quantity, price, and supplier information.
- Initiate a purchase request.

### 6. Messaging

- Provide a messaging interface for buyer-supplier communication.
- Demonstrate conversation functionality in the current prototype.

### 7. About Page

- Explain the project's purpose, goals, and sustainability vision.

## User Roles

**Supplier**

- Add available waste materials.
- Provide listing details.
- Make materials visible to potential buyers.

**Buyer**

- Browse marketplace listings.
- View material details.
- Send purchase requests for materials.

*Note: Role-specific permissions and workflows may require further implementation.*

## Technology Stack

- **HTML5** — Website structure.
- **CSS3** — Styling and responsive user interface.
- **JavaScript** — Client-side interactions and application logic.
- **Browser Local Storage** — Demo listing, authentication, and related application data persistence.

## Project Structure

```text
WasteIQ_Hackathon/
│
├── home.html          # Home page
├── index_login.html          # Login and Sign Up
├── marketplace.html    # Waste marketplace
├── add-listing.html    # Add a waste listing
├── waste-details.html  # Waste item details
├── messages.html       # Messaging interface
├── about.html          # About WasteIQ
├── style.css           # Shared website styling
└── app.js              # Main JavaScript functionality
```

## How to Run the Project

1. Clone or download the project repository.
2. Open the project folder in Visual Studio Code.
3. Make sure all HTML, CSS, and JavaScript files are in the correct locations.
4. Open `login.html` using the VS Code Live Server extension.
5. Register a demo account or log in.
6. Explore the home page, marketplace, listings, item details, and messaging interface.

**Important:** Open the pages through the same local server origin when testing, so browser Local Storage remains consistent.

## Expected Impact

- Encourage reuse and recycling of waste materials.
- Help suppliers connect with potential buyers.
- Improve the visibility of reusable resources.
- Support resource efficiency and circular-economy practices.
- Promote awareness of sustainable waste management.

## Future Scope

- Backend integration using a database.
- Secure authentication and password protection.
- Verified supplier and buyer accounts.
- Advanced search and category filters.
- Real-time messaging and notifications.
- Purchase-request tracking and status updates.
- Image uploads and improved listing management.
- Admin dashboard and analytics.
- Integration with recycling organizations and waste-management partners.

## Current Prototype Limitations

WasteIQ currently uses client-side HTML, CSS, JavaScript, and browser Local Storage for its demo functionality. Data is stored locally in the browser rather than in a shared backend database.

The current authentication mechanism is for demonstration purposes and is **not secure enough for production use**. A real deployment should use server-side authentication, secure password hashing, access control, and a backend database.

## Team & Contribution

WasteIQ is developed as a team project focused on sustainable waste management and resource exchange.

Team members can contribute by improving the user interface, developing backend services, enhancing marketplace functionality, and adding new sustainability-focused features.

## Our Vision

**Waste is not just something to dispose of — it can be a resource for someone else.**

WasteIQ aims to make that connection easier, helping build a future where useful materials are reused instead of wasted.
