##################
Uberspace 7 manual
##################

.. image:: _static/images/big-rocket.svg

Uberspace is a hosting platform targeted at people who want to look behind the scenes, do things we didn’t anticipate and generally prefer working with a text-based console. Our objective is to not only host the content you’d like to see on the web, but also to introduce you to Linux and basic shell usage.

----

.. rst-class:: noclear
.. tip:: If you're looking for guides and how to install certain tools like `WordPress <https://lab.uberspace.de/en/guide_wordpress.html>`_ check out the `⚛️ Uberlab <https://lab.uberspace.de/en/>`_!

#########
Changelog
#########

Latest Version: **{{ newest_changelog_entry.version }}** ({{ newest_changelog_entry.date }})

{{ newest_changelog_entry.text }}

For more information see the :doc:`full changelog <changelog>`.

.. include:: includes/hotfix-version.rst

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Your first day

   for newbies <firstday-newbies>
   for Ubernauts from U6 <firstday-ubernauts>
   for nerds <firstday-nerds>

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Basics

   SSH <basics-ssh>
   SFTP <basics-sftp>
   backup <basics-backup>
   resources <basics-resources>
   home directory <basics-home>
   shell <basics-shell>
   firewall ports <basics-ports>

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Web

   DocumentRoot <web-documentroot>
   domains <web-domains>
   https <web-https>
   security headers <web-security-headers>
   web backends <web-backends>
   web headers <web-headers>
   web errorpage <web-errorpage>
   logs <web-logs>
   Tor <web-tor>

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Mail

   access <mail-access>
   domains <mail-domains>
   mailboxes <mail-mailboxes>
   forwarding <mail-forwarding>
   spam handling <mail-spam>
   filters & rules <mail-filters>

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Database

   MySQL <database-mysql>
   PostgreSQL <database-postgresql>
   MongoDB <database-mongodb>
   CouchDB <database-couchdb>
   redis <database-redis>
   InfluxDB <database-influxdb>
   SQLite <database-sqlite>

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Programming languages

   PHP <lang-php>
   Python <lang-python>
   NodeJS <lang-nodejs>
   deno <lang-deno>
   Ruby <lang-ruby>
   golang <lang-golang>
   Rust <lang-rust>
   .NET Core <lang-dotnet>
   Erlang/OTP <lang-erlang>
   Perl <lang-perl>
   Clojure <lang-clojure>
   Java <lang-java>
   Prolog <lang-prolog>
   GCC / C(++) <lang-gcc>

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Daemons

   supervisord <daemons-supervisord>
   Cron jobs <daemons-cron>

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Background

   Network <background-network>
   HTTP Stack <background-http-stack>

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Billing

   General <billing-general>

.. toctree::
   :hidden:
   :titlesonly:
   :maxdepth: 1
   :caption: Meta

   Changelog <changelog>
   Changelog Archive <changelog_archive>
   ⚛️ Uberlab <https://lab.uberspace.de/en/>
   Policy <policy>
   Legal Notice <https://uberspace.de/imprint>
   Privacy <https://uberspace.de/privacy>
