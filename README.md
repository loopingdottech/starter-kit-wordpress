# WordPress Starter Kit.

<p align="center">
  <a href="https://roots.io/sage/">
    <img alt="Sage" src="https://cdn.roots.io/app/uploads/logo-sage.svg" height="100">
  </a>
</p>

<p align="center">
  <strong>WordPress website development with a modern workflow.</strong>
  <br />
  Built with ❤️
</p>

<p align="center">
  <a href="https://looping.tech/" target="_blank">Agency Website</a> | <a href="https://www.looping.tech/work-process" target="_blank">Documentation</a> | <a href="#changelog">Changelog</a>
</p>


## Overview.

This is a starter kit for new WordPress websites with a modern development workflow - utilising Docker Compose to run WP in an isolated environment and bedrock boilerplate to organize WP projects better.


## Requirements for Local Development.

Make sure your local environment have the following installed:

+ [Composer](https://getcomposer.org/) - PHP Dependency Manager
+ [Docker](https://www.docker.com/get-started)
+ [Node.js](https://nodejs.org/en/) >= 8.0.0
+ [Openssl](https://github.com/openssl/openssl) for creating the local SSL certificate. Install using Homebrew or Chocolatey.
+ [PHP](https://www.php.net/manual/en/install.php) >= 7.2.0 (with php-mbstring enabled)
+ [Yarn](https://classic.yarnpkg.com/en/docs/install#mac-stable)


## Setup

### 1. Set up a WordPress environment for local development

► Create a new fork from this repository: [Docker Compose and WordPress](https://github.com/LoopingTech/wordpress-nginx-docker-compose)

### 2. Choose and Install the Appropriate Starter Theme Variant

► [Sage Starter Theme](https://github.com/LoopingTech/sage)

► [Twenty Twenty Child Theme]()

► [Headless Projects]()


## Plugins

coming soon...


## Changelog

### Note

When making changes to the Dockerfile, use:

`docker-compose up -d --force-recreate --build`

#### 2020-06-12
Initial setup