# MediaMolder

A modern web application for compressing videos and resizing images for social media platforms.

---
## Features

- **Video Compression:** Reduce file sizes while maintaining quality  
- **Image Resizing:** Optimize images for Instagram, Twitter, Facebook, and more  
- **Real-time Previews:** Hover-to-play video previews  
- **Cloud Storage:** Secure media processing via Cloudinary
- **User Authentication:** Secure login powered by Clerk
---

## Tech Stack

- **Frontend:**  Next.js 14, TypeScript, Tailwind CSS
- **Backend:** Next.js API Routes, Prisma, PostgreSQL
- **Media Processing:**  Cloudinary 
- **Authentication:** Clerk

---

## Quick Start

### Clone and install

```bash
clone https://github.com/yourusername/MediaMolder.git
cd MediaMolder
npm install
```

### Environment setup
```bash
envDATABASE_URL="postgresql://username:password@localhost:5432/MediaMolder"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_secret
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
```

### Database setup
```bash
prisma generate
npx prisma migrate dev
```

### Run development server
```bash
npm run dev
```

