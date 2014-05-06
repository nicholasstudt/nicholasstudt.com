---
layout: post
title: Open Source Licensing
tags: ['*nix']
category: 'blog'
---

The "Open Source" label has become so common that users rarely consider
all the implications of the term. In fact, there is no universal
definition of "Open Source." If you are working at home on a personal
workstation with standard product distributions, you may never need to
explore the subtle differences between Open Source variants. But if you
write your own software, or if you dabble in the distribution of
software, you'll need a clear understanding of the various license
options.

In this article, I will discuss some of the prominent interpretations of
the term "Open Source." For the terminology-minded, I will use the term
"open source" when referring to free software and "Open Source" when
referring to the abstract concept. There has been, and will be for the
foreseeable future, debate over the correct use of each wording.

## What Makes a License Open Source?
The first important task when evaluating Open Source licenses is to
define them. Two of the standards organizations overseeing the open
source world are the Open Source Initiative (OSI), a non-profit
corporation that stemmed from the same roots as Debian, and the Free
Software Foundation (FSF). Both OSI and FSF have established
[guidelines](http://www.opensource.org/docs/definition.html) for what
they consider "Open Source."

OSI lists nine guidelines for determining whether a license can be
declared Open Source. The OSI guidelines are slightly at odds with the
Free Software Foundation's definition of what constitutes Open Source.
The FSF takes a more holistic view of the license, specifying four
freedoms that should be considered, along with the the spirit of the
license itself, when deciding whether a license is truly Open Source.
Regardless of the differences between OSI and FSF's methods, the results
are remarkably similar.

The FSF four freedoms are described at the FSF Web site: <http://www.fsf.org/philosophy/free-sw.html>.  The following is a synopsis of the four freedoms (which are numbered zero through three):

 * Freedom 0 lets users run the software for any reason with no limits.
 * Freedom 1 lets users alter the software as they see fit. This, of course, requires the source code.
 * Freedom 2 allows users to give others the software as they received it from the author or other person.
 * Freedom 3 protects the ability to give the alterations granted in Freedom 1 to anyone else.

The FSF also compares other licenses' compatibility with the GPL. The
FSF tends to review every license they can find to see if it is
compatible with other Open Source licenses, and keeps related notes on
their Web site.

## The nine OSI guidelines are as follows:
"1. The license may not restrict any party from selling or giving away the software as a component of an aggregate software distribution containing programs from several different sources. The license may not require a royalty or other fee for such sale."

> This rule helps level the playing field, and prevents a single party from reaping all the benefits of an Open Source product.  This rule also removes the ability of any developer to impose royalty fees as a way to limit what other people can do with the software.

"2. The program must include source code, and must allow distribution in source code as well as compiled form. Where some form of a product is not distributed with source code, there must be a well-publicized means of obtaining the source code for no more than a reasonable reproduction cost--preferably, downloading via the Internet without charge. The source code must be the preferred form in which a programmer would modify the program. Deliberately obfuscated source code is not allowed. Intermediate forms such as the output of a preprocessor or translator are not allowed."

> OSI uses this clause to help stimulate the evolution of an Open Source product. While everyone enjoys the obfuscated C and Perl contest, there are very few people who want to spend their time developing an application that could be easily entered into one of those competitions. This clause also prohibits the release of object files only as "Open Source," as many hardware companies have done. The object files are not easily modifiable, and thus they are not deemed "Open Source." This is compatible with Freedom 1 from the FSF.

"3. The license must allow modifications and derived works, and must allow them to be distributed under the same terms as the license of the original software."

> Everyone makes mistakes. This clause allows other programmers and
> users of Open Source software to fix what the original developer left
> broken, or perhaps hasn't implemented yet. This also guarantees that
> if an Open Source product is modified by someone other than the
> original developers, those developers are allowed to freely distribute
> their changes under the same license. The third "freedom" expressed by
> the FSF would fall under this rule.

"4. The license may restrict source code from being distributed in modified form only if the license allows the distribution of "patch files" with the source code for the purpose of modifying the program at build time. The license must explicitly permit distribution of software built from modified source code. The license may require derived works to carry a different name or version number
from the original software."

> An Open Source license should allow the original developers to release their software in a manner that allows users to know that they have the "official" version, and not Billy's Software Modification. Most of the Open Source licenses do not restrict contributors from releasing the complete source, but it is a valid option if the developers are concerned.

"5. The license must not discriminate against any person or group of
persons."
> Read: Play nice and share with all the other kids on the playground. While not all software can be exported legally from the United States to other parts of the world -- encryption software to Iraq for example -- the license should not restrict this explicitly. The reasoning behind this is that not all countries have the same export laws, and some may be able to legally send the software to places the original developers were not be able to.  

"6. The license must not restrict anyone from making use of the program in a specific field of endeavor. For example, it may not restrict the program from being used in a business, or from being used for genetic research."

> Again, the OSI recommends that an Open Source license "play nice." Open Source software cannot be restricted from use in a commercial environment if the intent is to provide a service to the widest possible audience. This is in direct opposition to most non-Open Source licenses, which are only free for non-commercial use. The FSF's "Freedom 0" is embodied in this requirement as well.

"7. The rights attached to the program must apply to all to whom the program is redistributed without the need for execution of an additional license by those parties."

> This ensures that all parties have the right to pass the software along to other people. There is no need to acquire permission beforehand. Almost all commercial licenses would pass the Open Source test as measured by this clause, assuming they made it through the first six. This also keeps software from being closed up through the use of non-disclosure agreements and the like. The FSF's "Freedom 3" is embodied in this clause.

"8. The rights attached to the program must not depend on the program's being part of a particular software distribution. If the program is extracted from that distribution and used or distributed within the terms of the program's license, all parties to whom the program is redistributed should have the same rights as those that are granted in conjunction with the original software distribution."

> Software can not be restricted to one operating system or one company's distribution of an operating system. This helps to close some license problems that could be hazardous to keeping software Open Source.

"9. The license must not place restrictions on other software that is distributed along with the licensed software. For example, the license must not insist that all other programs distributed on the same medium must be Open Source
software."

> At first glance, this clause seems to prevent the GNU Public License from being an Open Source license. It doesn't.

> The GPL restricts other software from being linked to it unless that software is also under the same or a similar license. The ambiguity comes from the way people think of the distribution of an operating system vs the distribution of an individual program; this blurry distinction is what causes many people to question if the GPL qualifies under this clause, which it does.

> Rather than restricting what programs can be linked to Open Source software, it removes restrictions on what can be put on the same CD or disk as Open Software. It keeps Open Source software from polluting closed-source software that happens to be shipped with it.

The OSI requires that licenses apply for the OSI Certification Mark
[http://www.opensource.org/docs/certification_mark.html](http://www.opensource.org/docs/certification_mark.html).  They also do
not keep a list of licenses that have failed the Certification Mark, or
are not completely Open Source. Neither one is the end-all in deciding
what is or is not Open Source; they simply supply the baseline in a
constantly changing environment.

## Licenses
There are hundreds of software licenses, from the fully closed-source
Microsoft EULA to the opposite extreme, the GPL. Between these lie a
multitude of others; I will focus on the licenses most similar to the
GPL. Since there is some discrepancy in what makes a license Open
Source, only the ones that both OSI and the FSF regard as Open Source
are listed here.

### GNU General Public License
The GNU General Public License
[http://www.fsf.org/copyleft/gpl.html](http://www.fsf.org/copyleft/gpl.html)
is the Open Source license du jour for the FSF and most of the Open
Source License. It gives software developers and users all of the rights
outlined by both the FSF and OSI. The GPL works by putting a copyright
on the software, which the original developers retain, and by
specifically lining out who can copy, distribute or modify the software.
This includes everyone who wants to follow the rules outlined in the
GPL. Running the software is not covered in the GPL, neither is the
output of the program. The output is only covered if it happens to be a
work based on the original software, such as a program that creates
other programs. The GPL also makes mention of software patents, which
are currently rampant in the software industry. If a patented program is
placed under the GPL it should be licensed free for everyone's use,
though the FSF would prefer no patent at all.

Copying, distributing, and modifying the software are all allowed if the
changes and the original software are all available to the public.  The
GPL does not allow non-open source software to be linked against it in
any form, which is the reason for the LGPL. The GPL grants you every one
of the freedoms from the FSF and meets all of the requirements of the
OSI mark; this helps to make it the core of the open source movement in
licenses.

The problems people tend to have with the GPL are the license's viral
nature and RMS's extreme evangelism. The viral nature of the GPL becomes
an issue when GPL software is combined with software of another license.
The GPL "infects" the other software so that it must be released under
the GPL as well. Although this is not necessarily a bad thing, it will
certainly affect the decision to use it in a combined environment. The
solution offered in this case is the GNU Lesser General Public.

### GNU Lesser General Public License
To help the GPL gain usage in even more areas, the GNU Lesser General
Public License [http://www.fsf.org/copyleft/lesser.html](http://www.fsf.org/copyleft/lesser.html) was introduced.
The LGPL was originally the GNU Library General Public License, but the
name was changed to promote use of the GPL. The big difference between
the GPL and the LGPL is that the LGPL allows non-Open-Source software to
link to the libraries with impunity, without suffering the viral effects
of the GPL. However, this is the reason that the FSF recommends using
the GPL over the LGPL. The greatest benefit of the LGPL is the ability
to link it with non-Open-Source software; because of this, LGPL
libraries and software can slowly replace the non-Open-Source libraries
the software may be using.

### BSD License
The BSD license [http://www.xfree86.org/3.3.6/COPYRIGHT2.html#5](http://www.xfree86.org/3.3.6/COPYRIGHT2.html#5) is a
short, concise license which allows redistribution of the source under
the same license. The BSD license is almost identical to the GPL now in
its action, if not wording, since the removal of the advertising clause.
This license does not restrict what software can be linked to it or what
anyone can do with the software after the fact. Almost all of the tcp/ip
software on the internet today started under this license, or was based
on such software. This license recently underwent a small change, which
removed the advertising clause from the original license.  That clause
forced people to state that "This product includes software developed by
the University of California, Berkeley and its contributors." Although
this isn't crippling to the Open Source nature of the license itself, it
was seen as a major hassle for people who marketed the software. The new
versions of this license do not have this restriction. The BSD license
is not viral like the GPL, and is approved by the OSI.

### Artistic License
The Artistic license [http://www.perl.com/language/misc/Artistic.html](http://www.perl.com/language/misc/Artistic.html)
takes most of its fame from being the co-license of Perl. The core of
Perl is released under both the Artistic License and the GPL; users get
to pick which license to use for their situation. The Artistic license
is much like the GPL, though it also allows negotiation with the
copyright holder in order to change the way the license applies in
specific circumstances. This license allows the software to be embedded
in non-open source applications as long the original software is
completely hidden. It also allows executable only distributions as long
as one of 4 conditions are met: you must tell the user where to get the
standard version, accompany the executables with the source code, give
the new executables new names and document these changes in the manual,
or make some other arrangements with the original Copyright holder.
These differences are what causes the FSF foundation to recommend
against utilizing this license, though these differences are what makes
it attractive to people who want the software to be used regardless of
location. Perl is embedded in many commercial applications because of
these features in the Artistic License. The OSI defines the Artistic
License as an Open Source License, but the FSF suggest that people avoid
it because the vagueness of the license might fail to protect your
rights.

### IBM Public License Version 1.0
IBM's Public License
[http://oss.software.ibm.com/developerworks/opensource/license10.html](http://oss.software.ibm.com/developerworks/opensource/license10.html)
meets all of the OSI's approval criteria. The FSF lists the license as
free software, yet notes that it is incompatible with the GPL because
some of the requirements are not part of the GPL. These requirements
center around the patent licenses that are required by the IBM license
but not by the GPL. The IBM license is also subject to the laws of New
York and the United States, as stated in the license itself, which could
pose problems for developers outside of the United States.

### The X11 License
The X11 License [http://www.x.org/terms.htm](http://www.x.org/terms.htm) is used by the The Open
Group for the X Window System. It does not have OSI's certification as
an Open Source license. Because OSI does not list licenses that have not
passed the approval, or have tried, it is not plainly obvious why this
license is not OSI approved. The FSF does recognize it as compatible
with the GPL. The license itself reads very much like the BSD license.

### The Mozilla Public License
The MPL [http://www.mozilla.org/MPL/MPL-1.1.html](http://www.mozilla.org/MPL/MPL-1.1.html) is OSI-approved as
an Open Source license, yet the FSF has some reservations about version
1.0. The 1.0 version of the MPL does not allow GPL'ed software and
MPL'ed software to be linked together because of some of the
restrictions in the MPL. This restriction could also cause problems in
linking the MPL to software that is covered under any other license,
hence the 1.1 revision of the license. The 1.1 version of the license
resolves this issue by offering portions of the code to be under
multiple licenses. The MPL also cleans up some problems that were
present in the Netscape Public License, specifically problems in the NPL
that allowed code to be taken into closed-source projects by Netscape
Corporation. The FSF urges people not to use the MPL because of the
linking problems inherent in the 1.0 version.

## How to Choose the Right License
Choosing the right license for your software is much like finding the
right way to create it in the first place. If the software was developed
for your place of employment you will have different requirements than
if you write it in your spare time. Some of the requirements to keep in
mind are:

 * Should closed-source applications be able to be linked with this software?
 * Does the license need to be acceptable to your manager, and your company?
 * Does the license protect you or your company from getting sued if it doesn't live up to the world's expectations?

There tend to be two camps of thought on this issue. First, there is the
FSF foundation, which wants all software to be covered under the GPL,
and therefore free for everyone to update and use. Second is the OSI,
which just wants more people to use Open Source compatible software.
Both camps are looking for the same goal: get the source and the ability
to use the software to the largest possible audience.

If the social and philosophical issues of Open Source software don't
concern you, then choose any one of these licenses, as they all
accomplish the same feat: software is distributable to everyone, users
can modify the software, and you retain the copyright on your work.
However, if the philosophical issues are a consideration for you,
choosing the right license will require a great deal of thought about
how you view closed-source applications and their use of your software.
(The GPL, for instance, doesn't allow closed-source software to use the
product, while most of the other licenses do not have this restriction.)

## Conclusion
Open Source licenses are growing in number every year, and corporations
are adding their own, as well. Some, like IBM, have met the criteria for
being an Open Source license. Others, like Netscape's, have not fared so
well. If you can't find a license that suits all of your needs, chances
are either you are not looking hard enough, or your requirements cannot
be met by an Open Source software license. Start with the OSI and FSF
guidelines and determine if you are willing to operate within these
restrictions. If so, check the OSI and FSF Web sites to look for leads
on a license that may be right for you.

## Resources
 * <http://www.fsf.org>
 * <http://www.opensource.org>
 * <http://www.fsf.org/copyleft/gpl.html>
 * <http://www.fsf.org/copyleft/lesser.html>
 * <http://www.xfree86.org/3.3.6/COPYRIGHT2.html#5>
 * <http://www.perl.com/language/misc/Artistic.html>
 * <http://oss.software.ibm.com/developerworks/opensource/license10.html>
 * <http://www.mozilla.org/MPL/MPL-1.1.html>

----- 
Originally published in Unix Review, March 2001.
