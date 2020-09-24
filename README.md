# sonicwall-filter-logstash
Sonicwall filter to logstash(elastic)

This filter was created according to my needs.
Feel free to modify, use only as a knowledge base.
This filter was used in production.

This filter was developed to be used with logstash.

<b>past the sonicwall-filter.conf into the logstash/config/</b>

Use the <b>logstash</b> binary with the string <b>"-f"</b> to signal the configuration file that
will be used.
<b>./path/to/logstash/bin/logstash -f /path/to/logstash/config/sonicwall-filter.conf </b>
