# Automated-Monitoring-Script
A Bash script that monitors different services, and outputs all information gathered to a basic HTML web page.

Pings all of stackoverflow.com’s IP addresses.

Tests to see if they can query 8.8.8.8 and 8.8.4.4 for DNS results.

Tests to see if the aforementioned DNS servers provide the same IP addresses for stackoverflow.com.

Tests to see if they can query time.nist.gov and pool.ntp.org for time.

Tests to see if the aforementioned NTP servers provide the same time within 1 millisecond.

Tests to see if stackoverflow.com’s web server is online by doing a wget on the site.

Takes all of this information and creates a webpage showing the results of the tests.

Webpage must refresh every minute, and webpage cannot be half-written when it refreshes.

Max 300 lines including comments.

Script must run every 5 minutes, and must fully execute in less than 4 minutes.
