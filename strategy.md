---
title: Human Colossus Foundation - License Strategy
tags: Papers
---

# HCF License Strategy

Human Colossus Foundation (HCF) aims to develop and provide an implementation of the core components of Dynamic Data Economy[^dde]. Taking into consideration long-term vision and commitment HCF seeks for finding the best approach for licensing strategy to assure sustainable development in a spirit of: with community for the community.

Our goal was to find a licensing strategy which can cover:
- a unified approach to all work items which we are working on 
- facilitate the broad adoption of implemented components
- protecting our community 
- sustainable development

## Unified Approach

Human Colossus Community developes variation of artifacts including software, related documentation, handbooks, standard specifications, education materials, etc. Some of those components are crossing each other, e.g. piece of code in specification or a documentation within software package. To make ours and users life easier we wanted avoid using multiple license for each separate item. Having one license which would reflect our values and support easy distribution of those components further is very important not only from organization point of view but as well from perspective of adoption and development where developers don't need to worry about cross checking licenses for each individual item which they are working on. Having umbrella license which can cover all speeds up development and simplify the rules for contributors.

## Broad adoption

Driving end–user adoption is a multi–year, multi–dimensional challenge that we need to face and address. In context of the technology which we are building our "end-users" are companies, organizations, and individuals who would like to build upon our work new solutions, provide services and extend work which we initiated. Giving our users possibility to integrate our work within their products (no matter of what license they use) would be major factor. Adoption is crucial aspect of every new technology and ideas, but as everything needs to be done wisely. Most of our work is around protocol and low level components of the infrastructure. To assure broad adoption of those technology we need to facilitate interoperability and make sure that different implementation would not fragment the market draining companies resources and slowing down the adoption. 
We would like to assure that implementation of the core components would help to drive one common solution that in long term companies can relay on. 

## Protecting Community

We build with community for the community! We need to remember that tons of hours and resources is and will be spent to build ecosystem of DDE. All that would be possible thanks to our community which is investing in the vision which we are sharing. To make sure that this effort can continue as it goes, we need to a licence strategy which would protect community in case of groups of individuals and/or entities which would be interested to use the effort to build upon it without sharing anything back. 

## Sustainable development

Long term vision requires long term planning. To achieve this vision we are looking for a strategy which allows us to create ecosystem which would enforce sustainable development. We need to remember that in modern world there is no such thing like "I did it", it is always combined effort of everyone around you, who provided you base line to start with. Sometimes we need to be more humble about our contribution. We add bits by bits to our ecosystem and growth it that way. License strategy should reflect that and allow to growth our community in sustainable way.


# Summary

Based on years of experiences of our experts we evaluated different licensing strategies for our work, taking into consideration abve goals. We found that the EUPL1.2+[^eupl] is the most suitable to address needs of our community and allow us to move forward.

- **Unified approach**: EUPL from 1.2+ allows to license "the work"[^eupl12] which gives us possibility to have umbrella license for any type of the work which we do, including source code, documentation, specification and more.
- **Broad adoption**: EUPL allows to link[^viral] it with any type of the source code including proprietary software and other open source license in the same time streamlining implementation by forcing to publish any modification of that work limiting the risk of market fragmentation by trying to leverage custom modification which are not available to everyone.
- **Protect community**: EUPL protect work already done and force community to share back any modification of "the Work" to the community assuring that their work would be available for everyone.
- **Sustainable development**: EUPL is copyleft, if the original work, even modified or improved, is re-distributed, the same licence must be applied. EUPL is compatible with a lot of open source licenses as well as allow for linking it with any other.

In addition the EUPL is unique for several reasons:

- For the first time, a public body  of the size of the European Commission has officially developed and approved a Free/Open Source Licence for the release of its software, and authorises the use of the Licence by any other stakeholder.
- The EUPL has identical value in 23 linguistic versions (all EU languages, except Gaelic). No similar example exists in the world of Free/Open licences.
- The EUPL has considered the specificity and diversity of Member States Law and the Community Law (copyright terminology, information, warranty, liability, applicable law and jurisdiction).
- The EUPL covers not only the classical software distribution, but also the "communication to the public" through remote access, or the provision of SaaS (software as a service) through the Internet. On this specific point, the EUPL is like the AGPL.
- The EUPL is not viral: according to the provision of European Law (Directive EC 2009/24 recitals 10 & 15), static and dynamic linking can be implemented with other programs without barriers or conditions. This ensures better legal security compared to licences that are not always operating under European Law.   
- The EUPL ensures downstream compatibility with the most relevant other reciprocal licences (including the most intensively used, the General Public licence or GPL). Its unique compatibility provisions create a new category of F/OSS licence: "Copyleft compatible" (other are: "Strong copyleft", "Weak copyleft" and "Without copyleft")  


### FAQ

1. Is EUPL alone compatible with proprietary software?
	> Yes[^1][^viral], you can use EUPL library in your proprietary application without need to release or share your code. Virality does not exist legally in Europe, even for the GPLv3 or AGPLv3 cause a probelm with questionable usage. Patrice-Emmanuel Schmitz provide[^viral_2] nice summary of that subject, he is a lawyer that participated in drafting EUPL, where he clearly question the legality of "strong" copyleft licenses in Europe.
2. Does the EUPL close the SaaS/ASP loophole?
	> Yes: the definitions in article 1 of the EUPL (unmodified in all EUPL versions so far) assimilates "communication to the public" to "distribution" and therefore targets and covers SaaS (software as a service) and the ASP (application service provider) activity.
Article 1 defines as "- Distribution or Communication: any act of selling, giving, lending, renting, distributing, communicating, transmitting, or otherwise making available, on-line or off-line, copies of the Work or providing access to its essential functionalities at the disposal of any other natural or legal person.".
 Therefore on this specific point, the EUPL is similar to the AGPL. 
3. Google banned[^google] EUPL to use internally for their products, so probably it is bad? 
	> Google banned EUPL based on assumption that EUPL == AGPL[^googleagpl], which is a false. (it seems that even big guys sometimes makes mistake). They argue that AGPL is bad because:
	
	> The license places restrictions on software used over a network which are extremely difficult for Google to comply with. Using AGPL software requires that anything it links to must also be licensed under the AGPL. Even if you think you aren’t linking to anything important, it still presents a huge risk to Google because of how integrated much of our code is. The risks heavily outweigh the benefits.
	> The primary risk presented by AGPL is that any product or service that depends on AGPL-licensed code, or includes anything copied or derived from AGPL-licensed code, may be subject to the virality of the AGPL license. This viral effect requires that the complete corresponding source code of the product or service be released to the world under the AGPL license. This is triggered if the product or service can be accessed over a remote network interface, so it does not even require that the product or service is actually distributed. Because Google's core products are services that users interact with over a remote network interface (Search, Gmail, Maps, YouTube), the consequences of an engineer accidentally depending on AGPL for one of these services are so great that we maintain an aggressively-broad ban on all AGPL software to doubly-ensure that AGPL could never be incorporated in these services in any manner.

4. How EUPL protect against patent claims?
	
	> EUPL covers the scope of the rights granted by the Licence in regards of patents in section 2:
	> > The Licensor grants to the Licensee royalty-free, non-exclusive usage rights to
any patents held by the Licensor, to the extent necessary to make use of the
rights granted on the Work under this Licence.

	
	> Patents on computer programs are not allowed in European law “as such”, but in practice, patents have been granted that cover functionalities in many common software applications. Patents pose a specific risk to the development of software because they protect the idea or the method and not simply the form, as copyright does. It is therefore possible to infring some patent without copying anything or without even knowing it. However, users are rarely subject to legal action for patent infringement. Developers and software licensors must almost always be notified first, prior to legal action seeking damages, thus giving them an opportunity to replace or remove the functionality that is possibly patented. The risk is therefore related to higher costs for replacing this functionality, rather than the direct costs of being subjected to patent lawsuits. In the practice, risks appear to be higher for proprietary software, where commercial interests are higher, than for Open Source distribution. Known software patents, such as MP3 audio or the LZW data compression have halted software development specific areas, but no Free / Open Source software has yet been subject to legal action for patent infringement.

In conclusion, when public administrations are using or distributing their own specific software under the EUPL, the risk from legal action related to patent infringement, while not zero, is very low.


## References

[^1]: https://joinup.ec.europa.eu/collection/eupl/news/eupl-and-proprietary-commer
[^viral]: https://joinup.ec.europa.eu/collection/eupl/news/why-eupl-not-viral-l
[^3]: https://joinup.ec.europa.eu/collection/eupl/news/meaning-copyleft
[^4]: https://joinup.ec.europa.eu/solution/eupl-freeopen-source-software-licence-european-union/about
[^viral_2]: https://fr.slideshare.net/OpenWorldForum/eole-owf-12-viral-licences-myth-or-reality-patriceemmanuel-schmitz-eole20121
[^google]: https://opensource.google/documentation/reference/thirdparty/licenses#european_union_public_licence_eupl_not_allowed
[^googleagpl]: https://opensource.google/documentation/reference/using/agpl-policy
[^8]: https://www.eclipse.org/legal/epl-2.0/faq.php#h.lgjcpvoq08a9
[^9]: https://joinup.ec.europa.eu/collection/eupl/how-use-eupl#section-17
[^dde]: https://humancolossus.foundation/blog/dde-launch
[^eupl]: https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12
[^freevs]: https://www.baozi.technology/floss-business-ethics-part-1-definitions-and-context
[^eupl12]: https://joinup.ec.europa.eu/collection/eupl/news/understanding-eupl-v12
