# Angular Login Application

A modern Angular application with authentication functionality featuring a beautiful login page and protected dashboard with customer management features.

## Features

- **Secure Login System**: User authentication with hardcoded credentials
- **Route Protection**: Auth guards to protect private routes
- **Modern UI**: Beautiful, responsive design with smooth animations
- **Session Management**: Persistent login state using localStorage
- **Responsive Design**: Mobile-friendly interface
- **Dashboard Navigation**: Sidebar menu with multiple sections
- **Customer Search**: Search customers by name, email, phone, or city
- **Customer Entry**: Comprehensive form for adding new customers

## Login Credentials

- **User ID**: `admin`
- **Password**: `admin123`

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

1. Start the development server:
   ```bash
   npm start
   ```

2. Open your browser and navigate to `http://localhost:4200`

3. Use the credentials above to log in

4. Navigate through the dashboard using the sidebar menu

### Building for Production

```bash
npm run build
```

## Project Structure

```
src/
├── app/
│   ├── components/
│   │   ├── login/          # Login component
│   │   ├── home/           # Dashboard component with navigation
│   │   ├── customer-search/ # Customer search functionality
│   │   └── customer-entry/  # Customer entry form
│   ├── services/
│   │   ├── auth.service.ts # Authentication service
│   │   └── storage.service.ts # Safe storage service for SSR
│   ├── guards/
│   │   └── auth.guard.ts   # Route protection guard
│   └── app.routes.ts       # Application routing
```

## Dashboard Features

### 1. Dashboard Overview
- Welcome message and user information
- Feature cards highlighting main functionalities
- Quick access to customer management tools

### 2. Customer Search
- **Search Options**: Search by name, email, phone, or city
- **Real-time Results**: Instant search results with mock data
- **Customer Actions**: View and edit customer information
- **Search Tips**: Helpful guidance for effective searching
- **Responsive Table**: Clean results display with action buttons

### 3. Customer Entry
- **Comprehensive Form**: Personal, address, and additional information
- **Form Validation**: Required field validation with error messages
- **State Selection**: Dropdown with all US states
- **Success Feedback**: Confirmation messages and form reset
- **Responsive Layout**: Mobile-friendly form design

## Technologies Used

- Angular 19
- TypeScript
- SCSS
- Angular Router
- Angular Forms
- Server-Side Rendering (SSR) Support

## Security Features

- Route guards for protected routes
- Session persistence
- Input validation
- Secure logout functionality
- SSR-safe localStorage handling

## Mock Data

The application includes sample customer data for demonstration:
- 5 sample customers with complete information
- Searchable by various criteria
- Editable customer records

## Customization

The application can be easily extended with:
- Additional user roles and permissions
- Real backend API integration
- Enhanced security features
- Additional dashboard features
- Customer analytics and reporting
- Data export functionality

## Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- SSR (Server-Side Rendering) support
- Progressive Web App ready
