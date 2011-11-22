Liquid is a template engine which was crafted for very specific requirements

* It has to have simple markup and beautiful results. Template engines which
  don't produce good looking results are no fun to use.
* It needs to be non-evaling and secure. Liquid templates are made so that users
  can edit them. You don't want to run code on your server which your users
  wrote.
* It has to be stateless. The compile and render steps have to be separate, so
  that the expensive parsing and compiling can be done once;  later on, you can
  just render it by passing in a hash with local variables and objects.
* It needs to be able to style emails as well as HTML.

## Stuff to read, watch, etc.

* [Class reference](http://rubydoc.info/gems/liquid)
* [[Liquid for Programmers]]
* [[Liquid for Designers]]
* [[Using Liquid without Rails]]

* [Liquid screencast](http://railscasts.com/episodes/118-liquid)

## Who uses Liquid?

* [Shopify](http://www.shopify.com)
* [Mephisto](http://mephistoblog.com/)
* [Chameleon](http://chameleon.wikidot.com/)
* [Cashboard](http://www.getcashboard.com)
* [Edicy](http://www.edicy.com)
* [Workory](http://www.workory.com)
* [Zendesk](http://www.zendesk.com)
* [SandwichBoard](http://www.sandwichboard.com/)
* [YikeSite (CMS)](http://www.yikesite.com/)
* [Simplicant (Applicant Tracking System)](http://www.simplicant.com/)
* [3scale (API Management System)](http://www.3scale.net/)
* [Chaptercore](http://www.chaptercore.com)
* [ScreenSteps Live](http://bluemangolearning.com/screenstepslive)
* [PokerAffiliateSolutions](http://www.pokeraffiliatesolutions.com/)
* [Assistly](http://www.assistly.com)
* [Ronin](http://www.roninapp.com)
* [CrowdVine](http://www.crowdvine.com)
* [AboutOne](http://www.aboutone.com)
* [RightScale](http://support.rightscale.com/15-References/Liquid_Markup_with_RightScale_Widgets)
* [Menumill](http://www.menumill.com)
* [Moxie Software](http://www.moxiesoft.com/)
* [Rusic](http://rusic.com/)
* [Development Seed](http://developmentseed.org/blog/2011/09/09/jekyll-github-pages/)
* [peerTransfer](http://peertransfer.com)
* [NationBuilder](http://nationbuilder.com/)
* [Vendder](http://vendder.com/)
* [tradelr](http://www.tradelr.com)
* [Avenue](http://www.prontoavenue.biz)
* ...Add yours :)

## Why should I use Liquid?

* You want to allow your users to edit the appearance of your application, but
  don't want them to run insecure code on your server.
* You want to render templates directly from the database.
* You like Smarty-style template engines.
* You need a template engine which does HTML just as well as emails.
* You don't like the markup language of your current template engine.