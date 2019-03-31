---
sidebar: auto
---

# Laravue

[Laravue](https://laravue.dev) is a beautiful dashboard for Laravel inspired by [vue-element-admin](http://panjiachen.github.io/vue-element-admin) but beyond that. With the powerful Laravel framework as backend, Laravue appears to be a full-stack solution for an enterprise administrative application.

## Screenshot
<p align="center">
  <img width="900" src="http://doc.laravue.cipherpols.com/assets/screenshot.png">
</p>

## Getting started

### Prerequisites

 * Laravue is positioned as an enterprise management solution, it is highly recommended to use it to start a project. 
 * If you want to integrate Laravue to existing Laravel project, you may need to check [Laravue Core](https://github.com/tuandm/laravue-core) instead
 * Your machine need to be ready for latest [Laravel](https://laravel.com/docs/5.8/installation) and [Node.js](https://nodejs.org)

### Installing
```bash
# Clone the project and run composer
composer create-project tuandm/laravue
cd laravue

# Migration and DB seeder (after changing your DB settings in .env)
php artisan migrate --seed

# Generate JWT secret key
php artisan jwt:secret

# install dependency
npm install

# develop
npm run dev # or npm run watch

# Build on production
npm run production
```

## Running the tests
* Tests system is under development

## Deployment and/or CI/CD
This project uses [Envoy](https://laravel.com/docs/5.8/envoy) for deployment, and [GitLab CI/CD](https://about.gitlab.com/product/continuous-integration/). Please check `Envoy.blade.php` and `.gitlab-ci.yml` for more detail.

## Built with
* [Laravel](https://laravel.com/) - The PHP Framework For Web Artisans
* [VueJS](https://vuejs.org/) - The Progressive JavaScript Framework
* [Element](https://element.eleme.io/) - A  Vue 2.0 based component library for developers, designers and product managers
* [Vue Admin Template](https://github.com/PanJiaChen/vue-admin-template) - A minimal vue admin template with Element UI

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/tuandm/laravue-core/tags). 

## Authors

* **Tuan Duong** - *Initial work* - [tuandm](https://github.com/tuandm)
* **Tony Tin Nguyen** - *Frontend and Designer* - [nguyenquangtin](https://github.com/nguyenquangtin)

See also the list of [contributors](https://github.com/tuandm/laravue/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Acknowledgements

* [Laravue-core](https://github.com/tuandm/laravue-core) - Laravel package which provides core functionalities of Laravue
* [vue-element-admin](https://panjiachen.github.io/vue-element-admin/#/) A magical vue admin which insprited Laravue project
* [tui.editor](https://github.com/nhnent/tui.editor) - Markdown WYSIWYG Editor
* [Echarts](http://echarts.apache.org/) - A powerful, interactive charting and visualization library for browser