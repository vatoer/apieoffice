# apieoffice

## Persiapan

### membuat repository di github 

```
https://github.com/vatoer/apieoffice
```

### tambahkan sebagai submodule 

```
$ git submodule add https://github.com/vatoer/apieoffice.git
```

### install symfony

- create ```composer.json``` , bisa dari copy dari composernya skeleton ```composer create-project symfony/skeleton```
- install symfony 
  ```
  composer install
  ```
- Install the API Platform's server component in this skeleton
  ```
  symfony composer require api
  ```
- ikuti petunjuk instalasi [installing api platform](https://api-platform.com/docs/distribution/#installing-the-framework)

### mengatur koneksi database 
- Modify DATABASE_URL config di .env
