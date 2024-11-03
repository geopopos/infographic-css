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
