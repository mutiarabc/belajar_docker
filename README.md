# Belajar Docker

Hi! I'm Mutiara, 
Checkout how you can get started with sitespeed.io

## Preparation
1. Install Docker
2. Don't forget use code editor to create docker-compose
3. And then "docker-compose up -d"
4. Access http://localhost:3000/ for dashboard grafana
5. Fill username sitespeedio and password hdeAga76VG6ga7plZ1
6. Run on CLI with 
> docker run --rm -v "$(pwd):/sitespeed.io" sitespeedio/sitespeed.io --graphite.host=host.docker.internal https://website --slug testname --graphite.addSlugToKey true
