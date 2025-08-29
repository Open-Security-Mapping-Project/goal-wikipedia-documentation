# goal-wikipedia-documentation
OSMP Goal: Improving Wikipedia Documentation

Using stub posts and redirects we can make sure that way more of the ICE detention facilities are documented on Wikipedia.

A project of the [Open Security Mapping Project](https://github.com/Open-Security-Mapping-Project). Head there for more info and other goals.

# General approach

Wikipedia recommends "stub posts" for basic content that is below an "encyclopedic" level. We would look to
create either stub posts for each detention center, or modifying posts about sets of county jails to extend
that information to cover the ICE detention mission within their set of buildings.

We want the information to be mapped back to the right OpenStreetMap locations.

Attributes should include ideally:

* Location (postal address)
* Coordinates
* Status Operational
* Security class. Medium or similar
* Population
* Opened

Additional stuff including news events, and certain incidents like the Delaney hall incident
( https://en.wikipedia.org/wiki/Newark_immigration_detention_center_incident ) have their own pages.
It would be best that all these things get cross referenced.

## Good ICE detention facility pages already completed

* The index is on here and we want these links to freaking work: https://en.wikipedia.org/wiki/List_of_immigrant_detention_sites_in_the_United_States -
note it also links to some counties (eg Barnstable County Mass) which does not have info on the ICE prison in the county page.
* They should be on here. https://en.wikipedia.org/wiki/Category:Immigration_detention_centers_and_prisons_in_the_United_States
* https://en.wikipedia.org/wiki/Adelanto_Detention_Center
* https://en.wikipedia.org/wiki/Allegheny_County_Jail
* https://en.wikipedia.org/wiki/Berks_County_Residential_Center

## Examples of Wikipedia prison stubs

* https://en.wikipedia.org/wiki/Northern_State_Correctional_Facility

### example markup

excerpt with the main stuff here.

```
{{Use American English|date=August 2025}}
{{Infobox prison 
| prison_name    = Northern State Correctional Facility
| image          = Seal of the Vermont Department of Corrections.jpg
| caption        = 
| location       = 2559 Glen Road, [[Newport (city), Vermont|Newport]], Orleans County, Vermont, United States
| coordinates    = {{Coord|44.906757|-72.1905832|type:edu_region:US-VT|display=inline}}
| status         = Operational
| classification = Medium
| capacity       = 433
| population     = 417
| populationdate = FY2010<ref name="2010Report">[http://www.doc.state.vt.us/about/reports/ff2008_adobe/view ] {{webarchive |url=https://web.archive.org/web/20090630070803/http://www.doc.state.vt.us/about/reports/ff2008_adobe/view |date=June 30, 2009 }}</ref>
| opened         = 1994
| closed         = 
| former_name    = 
| director       = 
| governor       = 
| warden         = 
| prisoners      =  
}}
The '''Northern State Correctional Facility''' ('''NSCF''') is a state prison in the city of [[Newport (city), Vermont|Newport]], Orleans County, Vermont, United States. It holds up to 433 medium security male prisoners<ref>{{cite web|url=http://www.motoruponline.com/files/MU%20newsletter_fall05.pdf |title=Welcome to |publisher=Motoruponline.com |access-date=2014-01-30}}</ref> and is the largest prison in Vermont.<ref>{{Cite web |url=http://doc.vermont.gov/about/reports/ff-archive/ff2007_adobe |title=Archived copy |access-date=2014-01-30 |archive-url=https://web.archive.org/web/20120722224808/http://doc.vermont.gov/about/reports/ff-archive/ff2007_adobe |archive-date=2012-07-22 |url-status=dead }}</ref> The [[Vermont Department of Corrections]] is responsible for running this prison.
== References ==
{{reflist}}

==External links==
*[http://www.doc.state.vt.us/custody-supervision/facilities/nscf/ Northern State Correctional Facility (Newport)]

{{State prisons in Vermont}}

[[Category:Prisons in Vermont]]
[[Category:Buildings and structures in Newport (city), Vermont]]
[[Category:1994 establishments in Vermont]]

{{US-prison-stub}}
{{Vermont-struct-stub}}

```
##  Example of redirects



```
#REDIRECT [[United Kingdom]]

{{Redirect category shell|1=
{{R printworthy}}
{{R from initialism}}
{{R mentioned in a hatnote}}
}}

```

# Wikipedia specific policies

* https://en.wikipedia.org/wiki/Wikipedia:Stub
* https://en.wikipedia.org/wiki/Category:Stub_categories
* https://en.wikipedia.org/wiki/Wikipedia:Citing_sources
* https://en.wikipedia.org/wiki/Wikipedia:Redirect

## External links

Can be in the info box and in an External Links section. 

* https://en.wikipedia.org/wiki/Wikipedia:External_links

* Can be used as a source -
  * https://www.ice.gov/detain/detention-management#stats

* can link to sister projects. https://en.wikipedia.org/wiki/Wikipedia:Wikimedia_sister_projects
  * wikidata can go via 	[[wikidata:]] 	[[d:]]

## Categories

* https://en.wikipedia.org/wiki/Category:Immigration_detention_centers_and_prisons_in_the_United_States . as of 8/28/25 there are 42 entries.
* https://en.wikipedia.org/wiki/Category:Prisons_in_the_United_States
* https://en.wikipedia.org/wiki/Category:Federal_prisons_in_the_United_States
* https://en.wikipedia.org/wiki/Category:United_States_prison_stubs

* Buildings and structures in (state / city)
  * https://en.wikipedia.org/wiki/Category:Buildings_and_structures_in_Newport_(city),_Vermont

Interesting hidden category flags wikidata issue:
* Category:Infobox mapframe without OSM relation ID on Wikidata

Another hidden one - tracking gizmo for map widget
* https://en.wikipedia.org/wiki/Category:Pages_using_the_Kartographer_extension - the gizmo info lives on mediawiki. - https://www.mediawiki.org/wiki/Extension:Kartographer

# Wikipedia "essays" (non policy items) and other commentary

The essays are users' takes on how to deal with various Wikipedia tasks.

* https://en.wikipedia.org/wiki/Wikipedia:Make_stubs
"""
Even if you don't have the time or the inclination necessary to give that topic a full featured article-style treatment, it's okay to create a stub if you are willing to provide:

    * Enough information to make it clear what the subject of the article is and for other editors to expand upon it.
    * Adequate context, keep in mind that articles with little or no context usually end up being speedily deleted
    * A sorted {{stub}} tag. Try, for example, {{Bio-stub}} or {{US-bio-stub}} for a biography. (You can see a full list of stub categories or browse stub types organized by the stub sorting WikiProject.)
    * At least one good category
    * Consider alerting the appropriate WikiProject of the new article by adding their tags to the talk page.
    * Providing sources, even just a small number, is valuable in preventing the article's deletion. A plain Google search may provide some reliable sources, but they will likely be buried within many more unreliable ones. Google News, Books, and Scholar provide the most reliable sources that are useful for establishing notability. Don't just provide links to these sources, cite them to make it clear where your information came from.

this explains that wikidata is also important for SEO and it is fine for stub posts to be short.
* https://www.legalmorning.com/stub-wikipedia-articles-and-how-to-manage-them/

# more interesting pages

* https://en.wikipedia.org/wiki/Detention_and_deportation_of_American_citizens_in_the_second_Trump_administration
* https://en.wikipedia.org/wiki/2025_United_States_protests_against_mass_deportation
* https://en.wikipedia.org/wiki/Deportation_in_the_second_Trump_administration
* https://en.wikipedia.org/wiki/Immigration_policy_of_the_second_Trump_administration
* https://en.wikipedia.org/wiki/Immigration_detention_in_the_United_States
* https://en.wikipedia.org/wiki/List_of_immigrant_detention_sites_in_the_United_States

----

# Info from the [OSMP front page Readme](https://github.com/Open-Security-Mapping-Project/)

Wikipedia is a world-leading source of information summaries with strong SEO (search engine optimization presence). Many facilities have Wikipedia pages but many do not.
Some are up to date and others are not. Wikipedia pages can link to OSM and to Wikidata "Q" numbers. A good description summary can be seen by millions of people at a
glance all over the internet.

Wikipedia is also multilingual so once there is an English page for a given site it is an easier prospect to add Spanish and other languages.

Wikipedia it seems is a *good location* to add news report links, if they are reliable sources in the internal policy (no Daily Mail!).

I am not familiar yet with adding OSM coordinates into Wikipedia but obviously that seems likely to be helpful.

* https://en.wikipedia.org/wiki/Wikipedia:Reliable_sources
