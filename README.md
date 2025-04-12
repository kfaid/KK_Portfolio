# AI Engineer & Data Scientist Portfolio

A modern, responsive portfolio website built with Flask, Bootstrap, and AOS animations. This portfolio showcases professional experience, projects, and blog posts in the field of AI and Data Science.

## Features

- Responsive design that works on all devices
- Modern UI with smooth animations
- Sections for:
  - Home
  - About Me
  - Education
  - Skills
  - Projects
  - Experience
  - Blog
  - Contact
- Contact form with email integration
- Project filtering capabilities
- Blog post categorization
- Social media integration
- Google Maps integration

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory and add your environment variables:
```
SECRET_KEY=your-secret-key-here
EMAIL_USER=your.email@gmail.com
EMAIL_PASS=your-app-specific-password
GOOGLE_MAPS_API_KEY=your-google-maps-api-key
```

## Configuration

1. Update the contact information in `templates/contact.html`
2. Add your profile image to `static/images/profile.jpg`
3. Add project images to `static/images/projects/`
4. Add blog post images to `static/images/blog/`
5. Update the Google Maps embed URL in `templates/contact.html` with your location

## Running the Application

1. Activate the virtual environment (if not already activated):
```bash
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Run the Flask application:
```bash
python app.py
```

3. Open your web browser and navigate to:
```
http://localhost:5000
```

## Customization

### Adding New Projects
1. Add project images to `static/images/projects/`
2. Update the projects section in `templates/projects.html`

### Adding Blog Posts
1. Add blog post images to `static/images/blog/`
2. Update the blog section in `templates/blog.html`

### Styling
- Main styles are in `static/css/style.css`
- Bootstrap classes are used throughout the templates
- AOS animations can be customized in the templates

## Contributing

1. Fork the repository
2. Create a new branch for your feature
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Bootstrap for the UI framework
- AOS (Animate On Scroll) for animations
- Font Awesome for icons
- Flask for the web framework 