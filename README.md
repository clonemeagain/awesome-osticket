# Awesome osTicket
[![Build Status](https://travis-ci.org/clonemeagain/awesome-osticket.svg)](https://travis-ci.org/clonemeagain/awesome-osticket/)
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

*A curated list of awesome osTicket resources, plugins, tutorials and other nice things.*


## Official Resources

* [GitHub repo](https://github.com/osTicket/osTicket) - Main repository.
* [Main Website](http://osticket.com) - Main website.
* [Documentation](https://docs.osticket.com/en/latest/) - Main Documentation site.
* [Core Plugins](https://github.com/osTicket/osTicket-plugins) - Plugins written by core developers.
* [Forum](http://www.osticket.com/forum/) - Forum hosted by osTicket.

## Download/Install files
* [Core Software](http://osticket.com/download/) - Get the latest release.
* [FAQ](http://osticket.com/faq) - Technical requirements etc.

## Translations/Language-Packs
*Download into `/include/il8n` folder.*
These are available in the download process now, simply select them when building your download package.

* [Official List](http://osticket.com/download#linguas) - Select "language packs" for latest.
* [Join the efforts](https://crowdin.com/project/osticket-official) - Help us translate osTicket for everyone.

## Plugins
*Installed into `/include/plugins` folder.*

### Core Plugins
*Developed by osTicket core developers.*

* [Authentication :: CAS](https://github.com/osTicket/osTicket-plugins/tree/develop/auth-cas) - Allows use of Client Access Server for authentication.
* [Authentication :: LDAP and Active Directory](https://github.com/osTicket/osTicket-plugins/tree/develop/auth-ldap) - Allows use of LDAP server for authentication.
* [Authentication :: Oauth](https://github.com/osTicket/osTicket-plugins/tree/develop/auth-oauth) - Allows use of an oauth service for authentication.
* [Authentication :: HTTP Pass-Through](https://github.com/osTicket/osTicket-plugins/tree/develop/auth-passthru) - Allows the use of webserver/passthrough authentication.
* [Storage :: Attachments in Amazon S3](https://github.com/osTicket/osTicket-plugins/tree/develop/storage-s3) - Allows attachments to be stored in AWS's S3 instead of the database.
* [Storage :: Attachments on the Filesystem](https://github.com/osTicket/osTicket-plugins/tree/develop/storage-fs) - Allows attachments to be stored on the webserver's filesystem instead of the database.

### Community Plugins
*Modifies how the software works, without changing it.*

* [Archiver](https://github.com/clonemeagain/osticket-plugin-archiver) - Archives tickets before delete, and allows for auto-pruning of old tickets.
* [Attachment Preview](https://github.com/clonemeagain/attachment_preview) - Allows files attached to tickets to be embedded in the thread.
* [Autocloser](https://github.com/clonemeagain/plugin-autocloser) - Automatically closes open tickets.
* [Fetch Note](https://github.com/bkonetzny/osticket-fetch-note) - Automatically fetch additional note content on ticket creation.
* [Field Radio Buttons](https://github.com/Micke1101/OSTicket-plugin-field-radiobuttons) - Enables the use of HTML form element Radio Buttons.
* [File Drive](https://github.com/akshaynikhare/FileDrive) - Integrate file sharing facilities like Google Drive, OneDrive, Dropbox
* [Mentioner](https://github.com/clonemeagain/osticket-plugin-mentioner) - Finds Staff mentions in a thread and add's them as collaborators to the ticket.
* [Multi LDAP Auth](https://github.com/philbertphotos/osticket-multildap-auth) - Plugin for multiple LDAP servers authentication and LDAP Sync.
* [Prevent Autoscroll](https://github.com/clonemeagain/osticket-plugin-preventautoscroll) - Stops the agent view from scrolling down to the last message in the thread.
* [Real Dynamic Lists](https://www.cartmega.com/software/osticket/real-dynamic-lists-for-osticket.html) - Paid plugin that populates Custom Lists with live database items and keeps them updated.
* [Rejection Notifier](https://www.cartmega.com/software/osticket/rejection-notifier-for-osticket.html) - Paid Auto-responder plugin for rejecting tickets, when incoming email is from un-registered users.
* [Reporting](http://software-mods.com/reports.html) - Paid plugin for extensive reporting.
* [Rewriter](https://github.com/clonemeagain/plugin-fwd-rewriter) - An osTicket plugin to rewrite incoming emails.
* [osTicket-telegram](https://github.com/SUNsung/osTicket-telegram) - Telegram notifications about new tickets.
* [osTicket_vk_and_telegram](https://github.com/Vladislav-Shi/osTicket_vk_and_telegram) - Bot for VK and Telegram.


### Third Party Integration Plugins
*Helps osTicket talk to other systems.*

* [Chrome Extension: osTicket Checker](https://chrome.google.com/webstore/detail/osticket-checker/kkcdfipbekoniikpigpklbioladkilig?hl=en) - Checks for new tickets.
* [Jasper Reports](https://github.com/meatballcoder/osticket-jasper-plugin) - A Jasper Reports plugin for osTicket 1.9.
* [Mattermost](https://github.com/Faust13/osticket-mattermost) - A plugin to send notifications to a Mattermost channel.
* [Magento Contact Integration](https://github.com/CopeX/magento-osticket-api) - Plugin for Magento to send contact form details to osTicket via the API.
* [OpenID for Microsoft](https://github.com/cbasolutions/osTicket-Plugins/tree/master/auth-openid-MS) - An osTicket plugin to enable authentication with Microsoft accounts.
* [Trello](https://github.com/kyleladd/OSTicket-Trello-Plugin) - Integrates Trello with osTicket.
* [Slack](https://github.com/clonemeagain/osticket-slack) - Sends notifications of new and updated tickets to a Slack channel.
* [Microsoft Teams](https://github.com/ipavlovi/osTicket-Microsoft-Teams-plugin) - Sends notifications of new and updated tickets to a Microsoft Teams channel.
* [JIRA](https://github.com/2600hz/OSTJiraSync) - Very flexable way to update osTicket in response to JIRA status changes. You just need to be comfortable with JSON
* [Bitfinex osTicket Streamer](https://github.com/bitfinexcom/bfx-ost-streamer) - Allows the creation of data streams to any third-party system.
 

## Themes
*Require modifications to osTicket core.*

* [Bootstrap Free Theme](https://github.com/philbertphotos/osticket-bootstrap-theme) - Unofficial bootstrap theme for osticket 1.10.
* [DMT Free Responsive for 1.9.12](http://osticket.com/forum/discussion/86735/dmt-free-responsive-theme-extended-basic-great-pumpkin-stable-1-0-for-osticket-1-9-12/p1) - Looks good. Awaiting upgrade to 1.10.
* [osTicketAwesome.com](https://osticketawesome.com/) - Commercial theme for client and staff portals.
* [osTicketResponsiveTheme.com](https://www.osticketresponsivetheme.com/) - Commercial theme for client & staff portals.
* [osTicket Themes.com](https://osticketthemes.com/) - Commercial Theme developers.
* [Themedost.com](http://themedost.com/) - Commercial Themes.


## Guides

* [Documentation](https://docs.osticket.com/) - Main documentation site.
* [Search Forums](https://www.google.com.au/search?q=site%3Aosticket.com) - Many questions have already been answered.
* [Youtube Installation Tutorial](https://www.youtube.com/watch?v=mblutpEstZ4) - Step by step demonstration of complete installation for v1.10.

## Development Resources

* [Docker osticket/osticket](https://hub.docker.com/search/?isAutomated=0&isOfficial=0&page=1&pullCount=0&q=osticket&starCount=1) - Docker images.
* [Documentation Repo](https://github.com/osTicket/docs) - Help out with documentation.
* [Repo - Signals Docs](https://github.com/osTicket/osTicket/blob/develop/setup/doc/signals.md) - How signals work.
* [Unofficial Plugin Development Guide](https://github.com/poctob/OSTEquipmentPlugin/wiki/Plugin-Development-Introduction) - Provides reverse-engineered instructions on how to develop an osTicket plugin.
* [Vagrant](https://github.com/clonemeagain/osticket-vagrant) - Provides a development environment for working with osTicket.

## Professional Services

* [Commercial Support](http://osticket.com/commercial-support) - Get the most out of osTicket with tailored plans for your business.
* [Customization](http://osticket.com/customization) - Modify the ticket system to meet your needs.
* [Installation](http://osticket.com/professional-installation) - Implementation, training, migration.
* [Professional Hosting](https://supportsystem.com) - No install necessary.


## @Mentions
* [Linux.com](https://www.linux.com/learn/osticket-help-desk-ticketing-done-right) - osTicket: Help Desk Ticketing Done Right.
* [Test-Driven Conceptual Modelling case-study report](http://upcommons.upc.edu/bitstream/handle/2117/12369/osticket_report11.pdf?sequence=1) - from Universitat Politecnica De Catalulnya (in English).
* [The Next Web - How to Build an Effective Heldesk](https://thenextweb.com/entrepreneur/2011/05/31/how/) - Article.
* [Blog](https://osticket.com/blog/) - Official blog of the creators.


Shout out to [Enhancesoft](http://enhancesoft.com) the makers of osTicket.


## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This page is not affiliated with Enhancesoft, please feel free to submit pull-requests for additions/removals of any of this content. 
If anyone from Enhancesoft wants to be added as a collaborator here, happy to work with you.
