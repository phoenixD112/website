# Papi Digital OctoberCMS Theme

## Local Development
TODO

### Updating the Papi Digital Theme
The theme lives in `/themes/papidigital`. It's using custom layouts
for the blog, and carries some static assets with it for some of the  
pages.

## Production Deployment
The project is deployed to [cloudways.com](https://cloudways.com).

### Config
It is setup to utilize Cloudways' Git integration. This works using a
pull-based system that is not automatic. You can find the controls for
this [here](https://platform.cloudways.com/apps/1630163/deployment).

This project uses environments, and is configured using a `.env` file
that should always be left out of the git repository.

If changes are needed, you can refer to the `.env` already in production.

### Deployment Instructions
1. To properly deploy, make sure to commit/merge your changes to the
`master` branch
2. Use the ["Pull" button in Cloudways](https://platform.cloudways.com/apps/1630163/deployment)
to finish the deployment
3. Run `npm update` and `yarn install` for any node dependencies
4. Run `composer install` for any composer depedency changes

## SCSS / CSS Compilation
This project uses `npm` to compile SCSS files to CSS and watch changes.

To use this functionality, run `npm run dev` in the terminal.

Check the `package.json` file for more configuration.

## Theming/Templating

### OctoberCMS Themes
To learn how to configure this theme, check the [official OctoberCMS documentation](https://octobercms.com/docs/themes/development#customization).

### Twig Templating
OctoberCMS uses Twig for templating. Visit the [official Twig documentation](https://twig.symfony.com/doc/3.x/templates.html) for more info.
