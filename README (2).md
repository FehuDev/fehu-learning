# Fehu Learning Platform Deployment

This is the deployment package for the Fehu Learning Platform educational app.

## Quick Deploy to Coolify

### Method 1: Upload to GitHub (Recommended)

1. Create a new repository on GitHub (e.g., `fehu-learning`)
2. Upload all these files to the repository
3. In Coolify, choose "Public Repository"
4. Enter your GitHub repository URL
5. Set domain to: `fehusoftwaredevelopment.co.uk`
6. Deploy!

### Method 2: Docker Registry

Build and push to a registry, then deploy from Coolify.

## Files Included

- `index.html` - The complete learning platform (130+ animals, 80+ plants, 8 subjects)
- `Dockerfile` - Container configuration
- `nginx.conf` - Web server configuration
- `README.md` - This file

## Local Testing

To test locally before deploying:

```bash
docker build -t fehu-learning .
docker run -p 8080:80 fehu-learning
```

Then visit: http://localhost:8080

## Features

- 6 Interactive Biomes (Desert, Rainforest, Ocean, Arctic, Grassland, Mountain)
- 8 Complete Subject Areas (Maths, English, Science, Nature, Geography, Wellbeing, Creative Arts, Life Skills)
- Parent Dashboard with Progress Tracking
- 130+ Animals with Facts and Roles
- 80+ Plants with Uses and Healing Properties
- Age-appropriate Content (4-7 years)
- Milestone Tracking for Homeschooling

## Support

For issues or updates, contact the developer.
