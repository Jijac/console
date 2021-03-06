* Generate publics symlinks to access assets stored in the bundles

![Demo video](https://github.com/polyfony-inc/console/blob/master/doc/generate-symlinks.gif)

* Synchronize your Polyfony project to/form a remote production server

![Demo video](https://github.com/polyfony-inc/console/blob/master/doc/sync.gif)

```
projet-directory$ Private/Binaries/Console 
    _           _           
   |_) _  |   _|_ _  ._     
   |  (_) | \/ | (_) | | \/ 
            /            /  

Usage
  command [arguments]

Available commands
  help                  Display this help message
  sync                  Synchronizes your project from or to a remote server via SSH
  check-config          Checks if the configuration of the framework is optimal
  vacuum-database       Executed a vacuum command on the database to free up space
  clean-cache           Empties the Private/Storage/Cache folder and it subdirectories
  generate-symlinks     Generates symlinks from Private/Bundles/{$1}/Assets/{$2} to Public/Assets/{$2}/{$1}
  generate-bundle       Generate a bundle with full CRUD capabilities based on current database tables
  generate-models       Generates all the Private/Models/{Table} based on current database tables
  generate-model        Generates a model file for a given table name
  generate-controllers  Generates all controllers in a bundle based on current database tables
  generate-controller   Generates a controller for a given table name
  generate-views        Generates all views for a given table name
  generate-view         Generates a view for a given table name and action


```
