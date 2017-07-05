# Micropayment Payment API

micropayment payment API client and demo application.


## Getting Started

### Prerequisites

This is a API client with demo application for PHP. So you need PHP installed on your system.
GIT and Composer will be nice too ...

### Installing

Clone or 'create-project' this package via GIT or Composer.

```
$ composer create-project micropayment/payment-api
or
$ git clone git://github.com/micropayment/payment-api
```

You may also download and unzip the package from https://github.com/micropayment/payment-api/archive/master.zip

## Testing

To run a demo application, start a php server on the /demoapp dir ...
```
$ composer demoserver
or
$ php -S localhost:8000 -t payment-api/demoapp
```

... and explore the possibilities of the API in your browser http://localhost:8000/.

After a few minutes you can find your transaction in our [Demo ControlCenter](https://www.micropayment.de/demologin/auto/)

Use this demo as a start point for your own development, or integrate it in your existing project.

## Documentation

TODO: Coming soon ...

## Going in Production
 
You have to register an account for your organisation on micropayment, and activate the different payment methods.
Here you find the [registration form](https://www.micropayment.de/auth/register).

Until your account is fully activated, and after, you can use all API features in a special sandbox mode. So you will be 
able to work on your next version, while your organisation is doing its business.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Found issues for this package? Raise a new on [Github](https://github.com/micropayment/payment-api/issues/new)
* Problems while installing or developing? Mail or call to [Support](https://www.micropayment.de/about/contact/)
* You could create a much better thing? Maybe you can do ... [Jobs](https://www.micropayment.de/about/jobs/) ;)