# Images Folder

This folder is for storing your portfolio images.

## Folder Structure

```
/assets/images/
├── profile/          # Your profile photo
├── projects/         # Project screenshots
└── research/         # Research-related images
```

## How to Use Images

### Option 1: Upload to Image Hosting Service (Recommended)
For Figma Make deployments, it's recommended to use image hosting services:
- **Imgur**: https://imgur.com
- **Cloudinary**: https://cloudinary.com
- **ImgBB**: https://imgbb.com
- **GitHub**: Upload to a GitHub repo and use raw URLs

Upload your images and use the direct URLs in your code.

### Option 2: Use Images from This Folder
If you place images here, reference them in your code like:

```tsx
import profilePhoto from './assets/images/profile/my-photo.jpg';

const profileData = {
  name: 'Mohammad Fleity',
  profileImage: profilePhoto,
};
```

## Image Recommendations

### Profile Photo
- **Recommended size**: 400x400px or 800x800px
- **Format**: JPG or PNG
- **File name**: `profile-photo.jpg` or `profile-photo.png`

### Project Images
- **Recommended size**: 1200x800px or 1920x1080px
- **Format**: JPG or PNG
- **File names**: Use descriptive names like `ai-dashboard-project.jpg`

### Research Report Cover
- **Recommended size**: 800x1000px (portrait)
- **Format**: JPG or PNG
- **File name**: `research-report-cover.jpg`

## Current Images Needed

Based on your portfolio, you need:
1. **Profile photo** (line 19 in App.tsx)
2. **12 project images** (lines 28, 36, 44, 52, 60, 68, 76, 84, 92, 100, 108, 116 in App.tsx)
3. **Research report cover** (line 136 in App.tsx)

Total: 14 images
