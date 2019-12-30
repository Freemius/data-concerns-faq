## Does Freemius usage-tracking impact performance?
The SDK is optimized to only use the minimum required resources it needs and we keep making it more performance as we go. Like any additional PHP code, of course, it requires some processing resources. The usage-tracking for opted-in users is executed once a day via a WP Cron, and only if there have been changes in the tracked data points, which means that the usage-tracking doesn't impact the performance of the site itself.

## [Next →](faq-12.md)