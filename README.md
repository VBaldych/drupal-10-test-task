# Drupal Landing Page
## Description
This is pretty simple example of landing page application based on Drupal 10

## Project Structure
- Theme - productive_shop (based on Olivero)
- Content type - Landing Page
- Block Types - Block Hero (for Layout Builder), Button (for Block Layout)

## Installation
1. Clone the repository
```bash
git clone https://github.com/vbaldych/landing_page
```
2. Access to the directory
```bash
cd landing_page
```

3. Run DDEV
```bash
ddev start
```

4. Install dependencies
```bash
ddev composer install
```

5. Import DB dump
```bash
ddev ddev import-db --file=dump.sql.gz
```

6. Generate one time admin link
```bash
ddev drush uli
```

Enjoy!