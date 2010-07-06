
Feeds Fusion Tables
===================

Upload data through Drupal to Google Fusion Tables.

Technically speaking, Feeds Fusion Tables is a Feeds [1] processor that allows
for using Drupal as an upload interface to Google Fusion Tables [2].

USAGE
=====

1. Install Feeds, Feeds UI, Google Fusion API, Feeds Fusion Tables [3].
2. Go to Google and register your domain [4], you will obtain an OAuth consumer
   key and an OAuth consumer secret.
3. Go to your site's admin/settings/gdata/oauth and enter the key and secret.
4. Go to your Drupal user account, click on the "Google" tab and request and
   authorize a token.
5. Go to admin/build/feeds and create a Feeds Importer and pick Fusion Table
   Processor as the Importer's  processor. See Feeds documentation [5] for
   details on how to create a Feeds Importer.
6. Use the Feeds Importer like any other one.

[1] http://drupal.org/project/feeds, use latest CVS HEAD
[2] http://tables.googlelabs.com/
[3] https://devseed.svn.cvsdude.com/sandbox/jose/gftables/
[4] http://code.google.com/apis/accounts/docs/RegistrationForWebAppsAuto.html#new
[5] http://drupal.org/node/622696
