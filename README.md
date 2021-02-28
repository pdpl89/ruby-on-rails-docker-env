# Ruby on Rails Docker Environment

A simple development and production environment based on Docker and Alpine Linux

Description:

* Ruby 3.0.0

* Rails 6.0.3

* Alpine Linux 3.12


### Extra Tooling

* .npmrc custom setup


### Databases Supported

* MySQL

* PostgreSQL

* SQLite

## Running the Development Environment

In some cases you'll need to allow execution of the shellscript as a program. Run both commands top start the setup:

```console
$ sudo chmod +x run_dev.sh
$ ./run_dev.sh
```

After the setup finishes, you'll be inside the container's prompt. Create new projects with:

```console
$ rails new your_app_name -d postgresql
```


## Running the Production setup


// to-do
