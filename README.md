#netuitive.packages.aws.elasticache 2.0.1

For detailed information on this package, please refer to the [online documentation](https://help.app.netuitive.com/Content/Misc/Datasources/AWS/new_aws_datasource.htm).

##Release History

###Version 2.0.1

* Changed the swap usage policy to look for out-of-band deviations as opposed to a static threshold.

###Version 2.0.0

* Introduced a new computed metric for Redis: _netuitive.elasticache.cachehitratio_
* Added a gauge for the Cache Hit Ratio on the element detail page.
* Improved the correlation settings for Redis nodes.
* Introduced new policies for Redis:
 * AWS ElastiCache Redis - Elevated Command Executions
 * AWS ElastiCache Redis - Elevated Network Activity
 * AWS ElastiCache Redis - Elevated Number of New Connections
 * AWS ElastiCache Redis - Elevated Replication Lag
 * AWS ElastiCache Redis - Extended Period of Evictions
 * AWS ElastiCache Redis - Extended Period of Swap Usage
 * AWS ElastiCache Redis - Low Cache Hit Rate

###Version 1.0.4

* Updated package compatibilities.

###Version 1.0.3

* Fixed typo on the element detail pages.

###Version 1.0.2

* Bug fix for the multi-metric widgets on the element detail page.

###Version 1.0.1

* Fixed bug on Element Detail page configuration (element type did not include "EC")

###Version 1.0.0

* Initial production release of the package for monitoring AWS ElastiCache resources.  Both Memcached and Redis clusters are supported by this package.