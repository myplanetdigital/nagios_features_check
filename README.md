## Nagios Features Check module

This Drupal module add a check that will raise a CRITICAL Nagios warning
via the Nagios module if any features are in a non-clean state. This
includes the following error states:

  * Overridden
  * Needs review

You may run a quick check like so:

    drush @mysite.env nagios features_check

### Dependencies

  * [Features module][features]
  * [Nagios module][nagios]

<!-- Links -->
   [features]: https://drupal.org/project/features
   [nagios]:   https://drupal.org/project/nagios


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/myplanetdigital/nagios_features_check/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

