# netuitive.packages.aws.elasticache

For detailed information on this package, please refer to the [online documentation](https://help.netuitive.com/Content/Integrations/aws.htm).

## Release History

### Version 2.3.1

* Updated policy description for AWS ElastiCache Memcached - Elevated Swap Usage

### Version 2.3.0

* Updated element details dashboard layout
* Updated summary dashboard for new widget configs

### Version 2.2.0

* Updated dashboard layouts for gridstack

### Version 2.1.0

* Added the following new policies:
 * AWS ElastiCache Memcached - CPU Threshold Exceeded
 * AWS ElastiCache Memcached - Elevated CPU Utilization
 * AWS ElastiCache Memcached - Elevated Swap Usage
 * AWS ElastiCache Redis - Elevated CPU Utilization

### Version 2.0.2

* Set validMax=100 for the Cache Hit Rate.
* Changed the swap usage policy to only look for baseline deviations, since the underlying metric is not correlated.
* Adjusted some of the baseline and correlation settings.

### Version 2.0.1

* Changed the swap usage policy to look for out-of-band deviations as opposed to a static threshold.

### Version 2.0.0

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

### Version 1.0.4

* Updated package compatibilities.

### Version 1.0.3

* Fixed typo on the element detail pages.

### Version 1.0.2

* Bug fix for the multi-metric widgets on the element detail page.

### Version 1.0.1

* Fixed bug on Element Detail page configuration (element type did not include "EC")

### Version 1.0.0

* Initial production release of the package for monitoring AWS ElastiCache resources.  Both Memcached and Redis clusters are supported by this package.
