# Optics_VLab

Key Features Implemented:
Physics Engine
Gaussian thin lens formula: 1/f = 1/u + 1/v for precise image calculations
Analytical ray tracing: All ray intersections calculated mathematically, not approximated
Support for both convex and concave lenses with correct behavior
Interactive Elements
Drag the candle horizontally to change object distance
Drag focal points (marked with ×) to adjust focal length
Sliders for precise parameter control
One-Click Demo animates the object from 4f to 0.6f and back, showing all imaging cases
Visual Design
Dark technical aesthetic with cyan accent color
Clear visual distinction between:
Incident rays (gold/yellow)
Refracted rays (green)
Virtual ray extensions (gray dashed)
Real images (solid cyan) vs virtual images (dashed cyan)
Real-time Data Panel
Image distance (v)
Magnification (M)
Image height
Dynamic property badges showing real/virtual, upright/inverted, magnified/reduced
Ray Drawing Rules
Convex Lens:

Parallel ray → through focal point
Central ray → straight through
Focal ray → exits parallel (when u > f)
Concave Lens:

Parallel ray → diverges from virtual focal point
Central ray → straight through
