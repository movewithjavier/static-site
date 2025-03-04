# Deployment Instructions

## GitHub Pages Setup
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Set source branch to 'main' and folder to '/' (root)
4. Click Save

## Custom Domain (Optional)
1. Add your domain in GitHub Pages settings
2. Create a CNAME file in your repository root with your domain
3. Configure your DNS provider with the following records:
   - A record: 185.199.108.153
   - A record: 185.199.109.153
   - A record: 185.199.110.153
   - A record: 185.199.111.153
   - CNAME record: www points to yourusername.github.io

## Testing Deployment
1. Wait for GitHub Actions to complete deployment
2. Visit yourusername.github.io/repository-name
3. Verify all pages load correctly
4. Test responsive design on multiple devices

## Development Guidelines
- Use semantic HTML elements
- Follow BEM naming convention for CSS classes
- Keep JavaScript minimal and unobtrusive
- Ensure all pages are mobile-responsive
- Optimize images before adding to the repository

## Deployment
- Site is configured for GitHub Pages deployment
- Push changes to main branch to trigger automatic deployment
- Custom domain can be configured in repository settings 