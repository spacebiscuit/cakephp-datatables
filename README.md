# cakephp-datatables

[DataTables](https://www.datatables.net) is a jQuery plugin for intelligent HTML tables. Next to adding dynamic elements to the table, it also has great supports for on-demand data fetching and server-side processing. The _cakephp-datatables_ plugin makes it easy to use the functionality DataTables provides in your CakePHP 3 application. It consists of a helper to add DataTables to your view and a Component to transparently process AJAX requests made by DataTables.

This branch further harnesses CakePHP-DataTables by making use of Angular.js which uses data binding and dependency injection meaning that only minimal HTML mark-up required to generate feature rich DataTables. This implmentation removes any need for CakePHP helpers since Angular.js handles the front-end generation.

DOCUMENTATION IS UNDER DEVELOPMENT AND INCOMPLETE

## Requirements

* CakePHP 3.x
* DataTables 1.10.x
* Angular 1.x
* Angular DataTables - https://l-lin.github.io/angular-datatables/

## Installation and Usage

Please see the [Documentation][doc], esp. the [Quick Start tutorial][quickstart]

[doc]: https://github.com/ypnos-web/cakephp-datatables/wiki
[quickstart]: https://github.com/ypnos-web/cakephp-datatables/wiki/Quick-Start

## Credits

This work is based on the [code by Frank Heider](https://github.com/fheider/cakephp-datatables).
