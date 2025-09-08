# Social Auto Post

A web application for automating social media posting with webhook integration.

## File Structure

- **`index.html`** - Main homepage with navigation and feature overview
- **`login.html`** - Protected authentication page (hidden from direct access)
- **`dashboard.html`** - Protected main application dashboard (authenticated users only)
- **`robots.txt`** - Search engine indexing rules
- **`.htaccess`** - Server-level access protection (Apache)

## Navigation Flow

1. **Homepage** (`index.html`) - Public landing page with information about the service
2. **Login** (`login.html`) - Protected authentication page (redirects unauthorized access)
3. **Dashboard** (`dashboard.html`) - Protected main functionality (requires authentication)

## Security Features

### Access Protection
- **Direct URL Protection**: Login and dashboard pages redirect unauthorized users to homepage
- **Authentication Validation**: Enhanced session checks with automatic cleanup
- **Referrer Checking**: Pages verify legitimate access patterns
- **Search Engine Protection**: robots.txt prevents indexing of sensitive pages
- **Server-Level Protection**: .htaccess rules for additional security

### Authentication Security
- Traditional username/password with validation
- Telegram login integration
- Secure session management with localStorage
- Automatic logout on invalid sessions
- Activity logging and monitoring

## Features

### Homepage
- Modern, responsive design
- Feature overview
- Clear call-to-action buttons
- Navigation to login page

### Login Page
- Traditional username/password authentication
- Telegram login integration
- Demo credentials provided for testing
- Secure session management

### Dashboard
- Webhook URL configuration
- PIN-based security
- Activity tracking and history
- Real-time status updates
- Responsive design for mobile devices

## Demo Credentials

For testing purposes, use these credentials:
- **Username:** `adi`
- **Password:** `bosi`

## Technical Details

- Pure HTML, CSS, and JavaScript (no frameworks required)
- Local storage for session management
- Responsive design for mobile and desktop
- Modern UI with backdrop filters and animations
- Secure webhook integration with Railway backend

## Webhook Endpoint

The application connects to: `https://primary-production-7003.up.railway.app/webhook-test/social-content`

## Usage

1. Open `index.html` or `home.html` in a web browser
2. Navigate to the login page
3. Enter demo credentials or use Telegram login
4. Configure webhook settings in the dashboard
5. Monitor activity and webhook triggers

## Security Features

- PIN-based webhook authentication
- Session validation
- Input validation and sanitization
- HTTPS-only webhook endpoints
- Activity logging and monitoring
