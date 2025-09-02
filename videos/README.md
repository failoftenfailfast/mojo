# Video Assets for MOJO Real Estate

This folder contains video assets for the MOJO real estate website.

## 📁 Folder Structure

### `/hero/`
Hero section background videos

**Required Files:**
- `portugal-main.mp4` - Primary hero video (1920x1080, 10-30s loop)
- `portugal-mobile.mp4` - Mobile optimized version (720x1280, 10-30s loop)
- `portugal-fallback.jpg` - Fallback image for slow connections

**Recommended Content:**
- Sweeping aerial shots of Portuguese landscapes
- Beautiful coastal views (Algarve, Porto coastline)
- Historic architecture (Lisbon, Porto old town)
- Lifestyle shots (cafes, markets, daily Portuguese life)

## 🎥 Video Specifications

### Hero Videos
- **Format**: MP4 (H.264 codec)
- **Desktop**: 1920x1080 @ 30fps, 10-30 second seamless loop
- **Mobile**: 720x1280 @ 30fps, 10-30 second seamless loop
- **Size**: Keep under 5MB for fast loading
- **Audio**: No audio required (will be muted)

### Optimization Tips
1. Use tools like HandBrake or FFmpeg for compression
2. Ensure seamless looping (first and last frames should match)
3. Test on slow connections
4. Consider lazy loading for performance

## 📐 Recommended Aspect Ratios
- **Desktop Hero**: 16:9 (landscape)
- **Mobile Hero**: 9:16 (portrait) or 16:9 adapted

## 🎬 Content Suggestions

### Portugal Lifestyle Videos
- Morning coffee at a traditional pastelaria
- Sunset over Douro River with port wine
- Beach scenes from Algarve golden coast
- Historic tram rides through Lisbon
- Vineyard tours in Douro Valley
- Traditional Portuguese markets and daily life

### Property-Focused Videos
- Elegant apartment interiors with Portuguese tiles
- Renovation before/after timelapses
- Outdoor terraces with city/ocean views
- Traditional Portuguese architecture details

## 🚀 Usage in Code
Videos are automatically used in the hero section when present. The website will:
1. Try to load `portugal-main.mp4` for desktop
2. Fall back to `portugal-mobile.mp4` for mobile
3. Use `portugal-fallback.jpg` if video fails to load
4. Default to static background image if no videos present

Replace the placeholder files in this folder with your actual video content.
