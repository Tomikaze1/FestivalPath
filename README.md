# 🎪 FestivalPath - Smart Pedestrian Navigation for Festivals

**Never get lost at festivals again!** FestivalPath provides crowd-sourced walking navigation specifically designed for vehicle-free events where traditional maps fail.

## 🌟 Key Features

### 🗺️ Festival-Optimized Navigation
- **Walking-only routes** - No more car directions that don't work
- **Real-time crowd updates** from fellow attendees
- **Landmark-based directions** ("Turn left at the main food stall")

### 🚶 Crowd-Sourced Intelligence
- **Share and discover shortcuts** known only to locals
- **Earn rewards** for contributing helpful route tips
- **Heatmaps** show current congestion areas

### 📲 Offline-First Design
- Download festival maps **before you arrive**
- Works **without internet** during the event
- Lightweight to save battery

## 🛠️ Technology Stack

| Component       | Technology |
|----------------|------------|
| Frontend       | Ionic Angular |
| Maps           | Mapbox GL JS |
| Backend        | Firebase (Auth, Firestore) |
| Offline Storage| Capacitor Filesystem |
| CI/CD          | GitHub Actions |

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/Tomikaze1/FestivalPath.git

# Install dependencies
cd festivalpath
npm install

# Run development server
ionic serve
