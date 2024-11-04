# Infographic.css

A modern CSS library for creating beautiful, responsive infographics. This library provides ready-to-use components for building data visualizations and presentations.

## Installation

1. Include the CSS file in your HTML:
```html
<link rel="stylesheet" href="infographic.css">
```

2. Add Font Awesome for icons:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
```

3. Include the Inter font:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;800&display=swap" rel="stylesheet">
```

## Components

### Grid Layouts

Create responsive grid layouts with 2, 3, or 4 columns:

```html
<div class="info-grid grid-2">...</div>
<div class="info-grid grid-3">...</div>
<div class="info-grid grid-4">...</div>
```

### Stat Boxes

Display key statistics with icons:

```html
<div class="stat-box">
    <div class="info-icon theme-blue">
        <i class="fas fa-chart-line"></i>
    </div>
    <div class="stat-number">87%</div>
    <div class="stat-label">Revenue Growth</div>
</div>
```

### Timeline

Create vertical timelines with alternating content:

```html
<div class="timeline">
    <div class="timeline-item">
        <div class="timeline-content">
            <h3>Event Title</h3>
            <p>Event description</p>
        </div>
    </div>
</div>
```

### Progress Bars

Show progress or comparisons:

```html
<div class="compare-card">
    <div class="compare-title">Title</div>
    <div class="progress-bar">
        <div class="progress-fill" style="width: 75%"></div>
    </div>
</div>
```

### Comparison Section

Create side-by-side comparisons:

```html
<div class="comparison-section">
    <h2>Title</h2>
    <div class="comparison-grid">
        <div class="comparison-item">
            <div class="comparison-value">Value 1</div>
            <div class="comparison-label">Label 1</div>
        </div>
        <div class="comparison-item">
            <div class="comparison-value">Value 2</div>
            <div class="comparison-label">Label 2</div>
        </div>
    </div>
</div>
```

### Info Cards

Display information with icons:

```html
<div class="info-card">
    <div class="info-card-icon theme-blue">
        <i class="fas fa-lightbulb"></i>
    </div>
    <div class="info-card-content">
        <h3>Title</h3>
        <p>Description text</p>
    </div>
</div>
```

### Key Points List

Show important points with icons:

```html
<div class="key-points">
    <h2>Title</h2>
    <div class="key-point-item">
        <i class="fas fa-check-circle"></i>
        <span>Point text</span>
    </div>
</div>
```

### Data Highlight Box

Highlight important data or information:

```html
<div class="data-highlight">
    <div class="highlight-header">
        <i class="fas fa-chart-pie"></i>
        <h3>Title</h3>
    </div>
    <div class="highlight-content">
        <p>Content text</p>
    </div>
</div>
```

### Color Themes

Apply different color themes to icons:

- `theme-blue`
- `theme-green`
- `theme-orange`
- `theme-purple`

## Responsive Design

The library is fully responsive and adapts to different screen sizes:

- Grid layouts stack on mobile devices
- Timeline adjusts for better mobile viewing
- Components maintain readability at all sizes

## Browser Support

Supports all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Examples

See `demo.html` for complete usage examples.

## License

MIT License
