# cjar 0.2.0

* added auth_s2s() and overall auth support for Server to Server OAuth authentication support which 
replaces JWT authentication which ends on June 30, 2025. See the Adobe documenttion for more details 
https://developer.adobe.com/developer-console/docs/guides/authentication/ServerToServerAuthentication/migration/
* added changes to the endpoints to pull dimensions and metrics

# cjar 0.1.2

* hotfix: fixing a bug round the custom component id naming conflict which prevented the 
'metrics/' suffix from being added to the metric id

# cjar 0.1.1

* hotfix: calculated metrics as metrics in cja_freeform_table() is now handled  properly

# cjar 0.1.0

* Initial CRAN Submission Version
* added cja_auth() and other JWT authorization enabling functions
* added cja_get_me() which pulled the information for the JWT authorized user
* added cja_get_dataviews() to pull a list of all data views available
* added cja_freeform_table() function to pull data as in workspace
* added cja_get_audit_logs() function to pull audit logs
* added cja_get_metrics(), cja_get_dimensions(), cja_get_calculatedmetrics(), cja_get_filters() and other functions to pull elements data relating to available data in specific data views
* added filter function such as filter_build() to enable the development, validation, and creation of filters in CJA
* added cja_get_projects() to pull all projects available in a specified dataviewId

# cjar 0.0.0.9008

* Added a `NEWS.md` file to track changes to the package.
* Set version number for dev version of the package
* Added initial functions
