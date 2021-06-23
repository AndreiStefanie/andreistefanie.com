**_The blazing fast way to get WordPress up and running._**

## What's included

- **WordPress** - the latest version based on FPM and PHP 7.4 (you can change that of course)
- **MySQL** - again, latest version by default
- **NGinx** - probably the fastest way to serve WordPress
- **Let's Encrypt** - at this point we kinda assume TLS is a given for any website

## Getting Started

- Install [Docker](https://docs.docker.com/engine/install/) and [docker-compose](https://docs.docker.com/compose/install/)
- `cp .env.template .env`
- Fill in the details
- `docker-compose up -d`

## Hosting

You can run this anywhere you can run Docker.

Start on your own computer and, if you like your website, host it on

- [Upcloud](https://upcloud.com/signup/?promo=4798BD) (they offer 100% availability; [my personal](https://andreistefanie.com/) website using this repo runs on it; referral link)
- [Linode](https://www.linode.com/?r=ac62cb2c286de6957e6681648b09ec514192b800) (parts of [CharityDiscount](https://charitydiscount.ro/shops) run on it; again, referral link)
- DigitalOcean, or any cloud provider that fits your preferences and budget.

You really don't need a huge VM to run this unless we are talking about millions of visitors. 1 vCPU and 1 GB of RAM should be more than enough at the beginning.
