# Professional E-Portfolio

A beautifully designed, responsive professional portfolio built with React, TypeScript, and Tailwind CSS.

## Features

- Professional profile section with photo and downloadable resume
- Video showcase for presentations
- Project portfolio gallery with filterable categories
- Contact form with social media integration
- Responsive design for all devices
- Dark/light mode toggle
- Animated section transitions

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:

```bash
npm install
# or
yarn
```

3. Start the development server:

```bash
npm run dev
# or
yarn dev
```

## Customization

### 1. Personal Information

Update your personal information in the components:

- `src/components/About.tsx` - Bio and skills
- `src/components/Hero.tsx` - Name and headline
- `src/components/Contact.tsx` - Contact details

### 2. Media Files

Replace placeholder files with your actual content:

- Add your profile photo as `public/assets/profile.jpg`
- Add your resume as `public/assets/Yougesh_Kumar_Resume.pdf`
- Add your videos to `public/assets/videos/`

### 3. Projects

Update project information in `src/components/Projects.tsx`

## Deployment

Build the project for production:

```bash
npm run build
# or
yarn build
```

The built files will be in the `dist` directory, ready to be deployed to your hosting service.

## License

This project is open source and available under the MIT License.