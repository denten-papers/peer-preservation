---
title: Book Piracy as Peer Preservation
author: \@dennistenen w/ thanks to Max Foxman and \@bodobalazs
bibliography: bib.bib
---

# Intros 
> Literature is the secretion of civilization, poetry of the ideal. That is why literature is one of the wants of societies. That is why poetry is a hunger of the soul. That is why poets are the first instructors of the people. That is why Shakespeare must be translated in France. That is why Molière must be translated in England. That is why comments must be made on them. That is why there must be a vast public literary domain. That is why all poets, all philosophers, all thinkers, all the producers of the greatness of the mind must be translated, commented on, published, printed, reprinted, stereotyped, distributed, explained, recited, spread abroad, given to all, given cheaply, given at cost price, given for nothing.
[@hugo_works_1907, p. 230]

<div class="notes">
    Introduce myself: my research happens at the intersection of texts, people, and technology. Recent reseach on book sharing. How I became intersted in book piracy.

    The big money (and the bandwidth) in online piracy is in film, music, and software. Text is less profitable for copyright holders; it is cheaper to duplicate and easier to share. Consequently, the issues surrounding the unsanctioned sharing of print material receive less press and scant academic attention. And yet the establishment of the "vast public literary domain" is an ideal that transcends piracy. Writers, librarians, and political activists from Victor Hugo to Leo Tolstoy and Andrew Carnegie have long argued for unrestricted access to information as a form of a public good essential to civic engagement. In that sense, people participating in online book exchanges enact the role closer to that of a public librarian than that of a bootlegger or a plagiarist. Book piracy cannot then be dismissed as mere search for free entertainment. Under the conditions of "digital disruption,"^[http://web.archive.org/web/20140110160431/http://go.proquest.com/libraries-at-the-center-of-the-digital-disruption] when the traditional institutions of knowledge sharing—the library, the university, the newspaper, and the publishing house—feel themselves challenged and transformed by the internet, we look to online book sharing communities for lessons in participatory governance, technological innovation, and economic sustainability.
Academic literature tends to view piracy on the continuum between free culture and copyright. On the one side, the argument is for redressing the global imbalance of access to information and in support of an informed reading public as a prerequisite for sustainable, democratic deliberation. On the other side, the argument is often made for the long-term conservancy of the cultural sphere, which (according to this view) must offer proper economic incentive to content creators in order to thrive.

    It is my contention that grassroots file sharing practices cannot be understood solely in terms of access and intellectual property. Our field work shows that while some members of the book sharing community participate for activist or ideological reasons, others do so as collectors, preservationists, curators, or simply readers. Despite romantic notions to the contrary, reading is a social and mediated activity. The reader encounters texts in conversation, through a variety of physical interfaces and within an ecosystem of overlapping communities, each projecting their own material contexts, social norms, and ideologies. A technician who works in a biology laboratory, for example, may publish closed-access peer-review articles by day, as part of his work collective, and release terabytes of published material by night, in the role of a moderator for an online digital library. Our approach then, is to capture some of the complexity of such an ecosystem, particularly in the liminal areas where people, texts, and technology converge.
</div>

## What is Aleph?
One of the largest online libraries in the world.  
40k unique visitors/day
1mil unique visitors main site + mirrors
1mil+ volumes
15mil+ journal articles
~15tb data
$1,900 / year

<div class="notes">
    Who? Where? Why? What can we learn form them as we think about the future of the book / library?
</div>

## Ethics of Piracy Research

<div class="notes">
    Research for this paper was conducted under the aegis of p\*, an academic research collective exploring the impact of peer-to-peer file sharing on the spread of knowledge around the world.^[http://p\*.org. Hashed for peer review only.] One the lab's first tasks was to discuss the ethics of piracy research. The conversation involved students, faculty, librarians, and informal legal council. Our major concern was neutrality: to avoid endangering the communities that we study and to protect the members of the lab from potential infringement. Following a frank discussion and several iterations, we drafted an ethics charter that continues to inform our work today. The charter contains the following provisions:
</div>

- When possible, remain neutral. We neither condone nor condemn piracy.
- We protect our sources and do not retain any identifying personal information.
- We strive for transparency in sharing our methodology, data, and findings with the widest possible audience.
- Credit where credit is due. Our work is clearly attributed to everybody involved.
- We limit our usage of licensed material to the analysis of metadata, with results used for non-commercial, nonprofit, educational purposes.
- Lab participants commit to abiding by these principles as long as they remain active members of the research group.

# Brief History

## Fall of Gigapedia.nu

![Archived version of library.nu, circa 12/10/2010](../figures/figure-1.jpg)

<div class="notes">
    Conceptually, the recent history of online book sharing and unsanctioned, "shadow" libraries^[@liang_shadow_2012] can roughly be divided into two periods. The first is characterized by local, ad-hoc peer-to-peer document exchanges and the subsequent growth of centralized content aggregators. Following trends in the development of the web as a whole, shadow libraries of the second period are characterized by communal governance and distributed infrastructure. Of course all infrastructure is social to an extent. Even private library collections cannot be said to be the work of a single individual. Collective forces shape the books themselves, the shelves, and the cognitive scaffolding that supports reading and interpretation. Yet, there is a palpable difference in both the administrative and the architectural structures governing private collections, public libraries, and torrent trackers (like *Pirate Bay*).^[http://thepiratebay.se/] Shadow libraries of the first period resemble a private collection in that they often emanate from a single authoritative source--a site of collection and distribution associated with an individual collector, sometimes explicitly. The library of Maxim Moshkov, for example, established in 1994 and still thriving at *lib.ru*, is one of the most visible collections of that kind. Despite their success, such libraries are limited in scale by the means and efforts of a few individuals. Due to their centralized architecture they are also susceptible to legal challenges from copyright owners and to state intervention. Shadow libraries responded to these problems by distributing labor, responsibility, and infrastructure, resulting in a system that is more robust, more redundant, and more resistant to any single point of failure or control.
    The case of *Gigapedia* (later *library.nu*) and its related file hosting service *ifile.it* illustrates the successes and failures of the centralized digital library model. Arguably among the largest and most popular virtual libraries online in the period of 2009-2011, the sites were operated by Irish nationals[^LN2] on domains registered in Italy and on the island state of Niue, with servers on the territory of Germany and Ukraine. At its peak, *library.nu* (LNU) hosted more than 400,000 books and was purported to make an "estimated turnover of EUR 8 million (USD 10,602,400) from advertising revenues, donations and sales of premium-level accounts," at least according to a press release made by the International Publishers Association (IPA).
    Its apparent popularity notwithstanding, *Gigapedia* was supported by relatively simple architecture, likely maintained by a single developer / administrator. The site itself consisted of a catalog of digital books and related metadata, including title, author, year of publication, number of pages, description, category classification, and a number of boolean parameters (whether the file is bookmarked, paginated, vectorized, is searchable, and has a cover). The catalog also contained a link to *ifile.it*, a "cyberlocker" service that hosted the actual files themselves.
    On the 15th of February, 2012 the IPA in conjunction with a consortium of international publishing houses,[^LN1] served a judicial cease-and-desist orders on both sites in a Munich court with the help of the German law firm Lausen Rechtsanwalte.  Seventeen injunctions were sought in Ireland, with the consequent voluntary shut-down of both domains, which for a brief time redirected visitors first to *Google Books* and then to *Blue Latitudes*, a *New York Times* bestseller about pirates, for sale on *Amazon*. The relatively brief, by library standards, existence of LNU underscores the weakness of the single-source digital library model. The site flourished as long as it did not attract the ire of the publishing industry. A lack of redundancy in the site's administrative structure paralleled the lack of redundancy on the server level. Once the identity of the operators was established--via Paypal receipts, according to a partner at Lausen Rechtsanwalte--the entire library was forced to shut down. The single point of origin also proved to be the single point of failure for the entire system.
</div>

## Reaction
> I live in Macedonia (the Balkans), a country where the average salary is somewhere around 200eu, and I’m a student, attending a MA degree in communication sci. [...] where I come from the public library is not an option. [...] Our libraries are so poor, mostly containing 30year or older editions of books that almost never refer to the field of communication or any other contemporary science. My professors never hide that they use sites like library.nu [...] Original textbooks [...] are copy-printed handouts of some god knows how obtained original [...] For a country like Macedonia and the Balkans region generally THIS IS A APOCALYPTIC SCALE DISASTER! I really feel like the dark age is just around the corner these days.^[https://web.archive.org/web/20140110050710/http://torrentfreak.com/book-publishers-shut-down-library-nu-and-ifile-it-120215]

> This is the saddest news of the year...heart-breaking...shocking...I was so attached to this site...I am from a third world country where buying original books is way too expensive if we see currency exchange rates...library.nu was a sea of knowledge for me and I learnt a lot from it [...] RIP library.nu...you have ignited several minds with free knowledge.^[<https://web.archive.org/web/20140110050450/http://www.reddit.com/r/trackers/comments/ppfwc/librarynu_admin_the_website_is_shutting_down_due>]

> This was an invaluable resource for international academics. The catalog of libraries overseas often cannot meet the needs of researchers in fields not specific to the country in which they are located. My doctoral research has taken a significant blow due to this recent shutdown [...]  Please publishers, if you take away such a valuable resource, realize that you have created a gap that will be filled. This gap can either be filled by you or by us.^[<https://web.archive.org/web/20140110050450/http://www.reddit.com/r/trackers/comments/ppfwc/librarynu_admin_the_website_is_shutting_down_due>]

> This just makes me want to start archiving everything I can get my hands on.^[<https://web.archive.org/web/20140110050450/http://www.reddit.com/r/trackers/comments/ppfwc/librarynu_admin_the_website_is_shutting_down_due>]

<div class="notes">
    Being a single-source, cyberlocker-based service, *Gigapedia* failed to leverage the good will of the community. As @lobato_cyberlocker_2013 write in their paper on cyberlocker-based media distribution systems, cyberlockers take an "instrumental view" of file sharing, where "no attempt is made to curate, organize, or archive the hosted content." In the words of the authors, the cyberlocker economy "does not foster collaboration or co-creation" making it difficult to support such non-transformative use ethically, and, as we would add, making it impossible to launch a meaningful "rescue" effort to preserve the archive. "This underscores the structural instability of file-sharing communities" . It would be more precise to say that the cyberlocker story underscores the structural instability of single-source media archives (and not file sharing communities in general). Although bereaved readers were concerned about the irrevocable loss of a valuable resource, digital libraries that followed built a model of file sharing that is more robust, more transparent, and more participatory than their *Gigapedia* / LNU predecessors.

    Jens Bammel, Secretary General of the IPA, called the action "an important step towards a more transparent, honest and fair trade of digital content on the Internet,"^[http://web.archive.org/web/20140110160254/http://www.internationalpublishers.org/ipa-press-releases/286-publishers-strike-major-blow-against-internet-piracy] while the rest of the internet mourned the passage of "the greatest, largest and the best website for downloading eBooks"^[http://archive.is/g205] and the burning of the "modern Library of Alexandria."^[https://web.archive.org/web/20140113135846/http://breakingculture.tumblr.com/post/17697325088/gigapedia-rip] Readers from around the world flocked to sites like *Reddit* and *TorrentFreak* to express their support and anger. A reader of *TorrentFreak* writes:
</div>

## Rise of Aleph

![DVD copy of "Traum's library" advertising "more than 167,000 books" in fb2 format. Similar DVDs sell for around 1,000 RUB ($25-30 US) on the streets of Moscow.](../figures/figure-2.jpg)

<div class="notes">
    In parallel with the development of *Gigapedia* / *library.nu*, Russian enthusiasts started work on a meta-library of sorts, under the name of Aleph. Records of Aleph's activity go back at least as far as 2009. Colloquially known as "prospectors," the volunteer members of the Aleph community began by aggregating library collections widely available on the gray market, with an emphasis on academic and technical literature in Russian and English. A similar project (FB) congealed around fiction.

    an archive or archives

- *KoLXo3*, a collection of scientific texts that was at one time distributed on 20 DVDs, overlapping with early Gigapedia efforts;
- *mexmat*, a library collected by the members of Moscow State University's Department of Mechanics and Mathematics for internal use, originally distributed through private FTP servers;
- *Homelab*, *Ihtik*, and *Ingsat* libraries;
- the Foreign Fiction archive collected from IRC #\* 2003.09-2011.07.09 and the Internet Library;
- the *Great Science Textbooks* collection and, later, over 20 smaller miscellaneous archives.^[GN/viewtopic.php?f=8&t=169; GN/viewtopic.php?f=17&t=299]
</div>

# Ecosystem

## Architecture of book sharing

![Aleph anatomy](../figures/figure-3.jpg)

<div class="notes">
    "What do we do?" writes one of the early volunteers (in 2009) on the topic of "Outcomes, Goals, and Scope of the Project." He answers: "we loot sites with ready-made collections,", "sort the indices in arbitrary normalized formats," "for uncatalogued books we build a 'technical index': name of file, size, hashcode," "write scripts for database sorting after the initial catalog process," "search the database," "use the database for the construction of an accessible catalog," "build torrents for the distribution of files in the collection." But, "everything begins with the forum," in the words of another founding member. Aleph, the very name of the group, reflects the aspiration to develop a "platform for the inception of subsequent and more user-friendly" libraries--a platform "useful for the developer, the reader, and the librarian."

    Decentralization on every level.
</div>

## Problems with decentralization

- bit torrent favors popular files
- lack of anonymity 
- unsecure mirrors

<div class="notes">
    Unlike its predecessors, the diffuse nature of the project makes it resilient to any single point of failure, whether in the form of server malfunction, or in the form of legal pressure. Should Aleph servers go offline, the archive would survive "in the cloud" of the *BitTorrent* network. Should the forum (GN) close, another online forum could easily take its place. And should the Aleph "library" distribution portal itself go dark, other mirrors would quickly take its place.

    These two challenges are further exacerbated in the case of Aleph, which uses *BitTorrent* to distribute parts of the archive, and not individual files. (The individual files are rather available from Aleph mirrors directly). These parts are relatively large--around 40-50 megabytes each. Long-term sustainability of Aleph torrent hive therefore requires a very special user, a user interested in downloading the archive as a whole (to make a mirror, for example) and one who has the hardware, the technical expertise, and the internet connection required to sustain this activity.
</div>

## Peer preservation 

- sharing and hoarding
- As the value of the archive increases so do the barriers to participation (sys-admin syndrome). 

## Going forward

- catalog
- server software
- social network data
