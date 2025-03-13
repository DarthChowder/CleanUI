# CleanUI

A lightweight, modern CSS library inspired by iOS and macOS aesthetics, now packed with advanced features to make it the ultimate UI toolkit. CleanUI offers a vast array of components, smooth animations, and robust JavaScript interactivity, all while supporting light, dark, and high-contrast themes.

## Features

- Responsive and mobile-friendly
- Theme support (light, dark, high-contrast) with a built-in switcher
- Glassmorphism effects and animation library (fade, slide, bounce, pulse)
- Dynamic components: datepicker, charts, modals, sortable tables
- Form validation, lazy loading, advanced tooltips, and toast variants
- Easy customization with CSS variables

## Live Demo
Check out the [CleanUI Showcase](https://darthchowder.github.io/CleanUI/) for a live demo and documentation!

## Components

### Buttons
```
<button class="btn animate-pulse">Primary</button>
<button class="btn btn-secondary">Secondary</button>```
```

### Cards
```
<div class="card animate-slide lazy-load">
  <h2 class="heading">Card Title</h2>
  <p>Content here.</p>
</div>
```

### Inputs
```
<input type="text" class="input" placeholder="Enter text...">
```

### Navigation Bar
```
<nav class="navbar">
  <ul class="nav-list">
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
  </ul>
</nav>
```

### Modal (Variants)
```
<div class="modal" id="modal-confirm">
  <div class="modal-content modal-confirm">
    <h2 class="heading">Confirm</h2>
    <p>Are you sure?</p>
    <button class="btn">Yes</button>
    <button class="btn btn-secondary">No</button>
  </div>
</div>
<button data-modal="modal-confirm" class="btn">Open Modal</button>
```

### Toggle Switch
```
<label class="toggle">
  <input type="checkbox">
  <span class="toggle-slider"></span>
</label>
```

### Slider
```
<input type="range" class="slider" min="0" max="100" value="50">
```

### Alerts
```
<div class="alert alert-success animate-fade">
  Success! <button class="close">×</button>
</div>
```

### Tooltips (Advanced)
```
<div class="tooltip">
  <button class="btn">Hover Me</button>
  <span class="tooltip-text" data-position="right">Rich <em>content</em></span>
</div>
```

### Dropdown
```
<div class="dropdown">
  <button class="dropdown-btn">Dropdown</button>
  <div class="dropdown-content">
    <a href="#">Option 1</a>
    <a href="#">Option 2</a>
  </div>
</div>
```

### Progress Bar
```
<div class="progress">
  <div class="progress-bar" style="width: 50%;"></div>
</div>
```

### Accordion
```
<div class="accordion">
  <div class="accordion-item">
    <div class="accordion-header">Section 1</div>
    <div class="accordion-content">Content here.</div>
  </div>
</div>
```

### Badge
```
<span>Messages <span class="badge">3</span></span>
```

### Tables (Sortable/Filterable)
```
<div class="search-bar">
  <input type="text" class="input table-filter" placeholder="Filter table...">
</div>
<table class="table table-striped table-hover">
  <thead>
    <tr><th class="sortable">Name</th><th class="sortable">Age</th></tr>
  </thead>
  <tbody>
    <tr><td>Alice</td><td>25</td></tr>
    <tr><td>Bob</td><td>30</td></tr>
  </tbody>
</table>
```

### Pagination
```
<div class="pagination">
  <a href="#">1</a>
  <a href="#" class="active">2</a>
  <a href="#">3</a>
</div>
```

### Tabs
```
<div class="tabs">
  <div class="tab-list">
    <button class="tab-btn" data-tab="tab1">Tab 1</button>
    <button class="tab-btn" data-tab="tab2">Tab 2</button>
  </div>
  <div id="tab1" class="tab-content">Content 1</div>
  <div id="tab2" class="tab-content">Content 2</div>
</div>
```

### Breadcrumbs
```
<nav class="breadcrumbs">
  <a href="#">Home</a>
  <span class="separator">/</span>
  <span>Page</span>
</nav>
```

### Spinner
```
<div class="spinner"></div>
```

### Form Group (With Validation)
```
<form class="form-validate">
  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" id="email" class="input" data-validate="email" placeholder="Enter email">
    <span class="form-error">Invalid email</span>
    <span class="form-success">Looks good!</span>
  </div>
  <button class="btn">Submit</button>
</form>
```

### Carousel
```
<div class="carousel">
  <div class="carousel-inner">
    <div class="carousel-item">Slide 1</div>
    <div class="carousel-item">Slide 2</div>
  </div>
  <button class="carousel-btn prev">❮</button>
  <button class="carousel-btn next">❯</button>
</div>
```

### Search Bar
```
<div class="search-bar">
  <input type="text" class="input" placeholder="Search...">
</div>
```

### Sidebar
```
<button class="sidebar-toggle">☰</button>
<div class="sidebar">
  <h2 class="heading">Menu</h2>
  <a href="#">Home</a>
</div>
```

### Toasts (Variants/Stacking)
```
<button class="btn" data-toast="Success!" data-toast-type="success">Success</button>
<button class="btn" data-toast="Error!" data-toast-type="error">Error</button>
```

### Datepicker
```
<div class="datepicker">
  <input type="text" class="input" placeholder="Select date">
  <div class="datepicker-calendar">
    <div class="datepicker-header">
      <button class="datepicker-btn prev">❮</button>
      <span class="datepicker-month-year"></span>
      <button class="datepicker-btn next">❯</button>
    </div>
    <div class="datepicker-days"></div>
  </div>
</div>
```

### Charts
```
<div class="chart">
  <div class="chart-bar"></div>
</div>
<div class="chart">
  <div class="chart-pie"></div>
</div>
```

### Avatar
```
<div class="avatar">JD</div>
<div class="avatar"><img src="user.jpg" alt="User" loading="lazy"></div>
```

### Tag
```
<span class="tag">New</span>
```

### Divider
```
<div class="divider"></div>
```

### File Upload
```
<div class="file-upload">
  <label class="file-upload-label">
    Upload File
    <input type="file">
  </label>
  <span class="file-upload-text">No file selected</span>
</div>
```

### Steps
```
<div class="steps">
  <div class="step active">
    <div class="step-circle">1</div>
    <span>Step 1</span>
    <div class="step-line"></div>
  </div>
  <div class="step">
    <div class="step-circle">2</div>
    <span>Step 2</span>
  </div>
</div>
```

### Tree View
```
<div class="tree-view">
  <ul>
    <li><span class="tree-toggle">Folder</span>
      <ul>
        <li>File 1</li>
      </ul>
    </li>
  </ul>
</div>
```

### Context Menu
```
<div class="context-menu">
  <a href="#">Edit</a>
  <a href="#">Delete</a>
</div>
```

### Autocomplete
```
<div class="autocomplete">
  <input type="text" class="input" placeholder="Type to search...">
  <div class="autocomplete-list"></div>
</div>
```

### Rating Stars
```
<div class="rating">
  <span class="rating-star">★</span>
  <span class="rating-star">★</span>
  <span class="rating-star">★</span>
  <span class="rating-star">★</span>
  <span class="rating-star">★</span>
</div>
```

### Image Gallery
```
<div class="image-gallery animate-fade lazy-load">
  <div class="gallery-item">
    <img src="https://via.placeholder.com/200" alt="Image" loading="lazy">
    <div class="gallery-overlay"><span>View</span></div>
  </div>
</div>
```

## Installation
Download CleanUI.css and CleanUI.js.
Link them in your HTML:
```
<link rel="stylesheet" href="CleanUI.css">
<script src="CleanUI.js"></script>
```

## How to Use

### Basic Setup
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CleanUI App</title>
  <link rel="stylesheet" href="CleanUI.css">
</head>
<body>
  <div class="container">
    <h1 class="heading animate-fade">Hello, CleanUI!</h1>
  </div>
  <script src="CleanUI.js"></script>
</body>
</html>
```

## Customizing Themes

### Modify CSS variables or use the theme switcher:
```
:root {
  --primary: #ff9500;
  --background: #f0f0f0;
}
```
## Contributing
Submit issues or pull requests to enhance CleanUI!

## License
MIT License - free to use and modify.
