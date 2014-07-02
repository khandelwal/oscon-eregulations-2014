
## RULES

Life is about rules. Every one of you, since the age of two, has been exposed
to rules. I grew up in a reasonably strict household, so there were many rules
I had to follow. 

## FEDERAL REGULATIONS ARE UBIQUITOUS

Regulations exist in many aspects of our lives. Many of you took a commerical
airplane flight this week, to come to Portland and attend this conference. If
you remember, you sat in your own seat (cramped as it was), and were required
to buckle your seat belt during take off and landing. You did not stand, as
some airlines would perhaps like for you to do, as this would allow them to fit
EVEN more people into the back of the plane. 

Sitting in your seat is safe, and putting on your seat belt is safer, and the
airlines (if they want to fly the friendly American skies) are required by
regulation (a rule if you will), to provide you with both. 

# 14 CFR

Title 14 (Aeronautics and Space), part 121 of the Code of Federal Regulations
deals with "Operating Requirements: domestic, flag and supplemental
operations". In particular, paragraph 311 talks about seats and safety belts. 

## 14 CFR TEXT 

This regulation text right here is why you didn't stand on your flight holding
on to a hand rail, on your way here. 

## 12 CFR 

Here's another regulation, one that deals with the availability of credit. 

## 12 CFR TEXT

Between these two examples you get a sense of the breadth of topics that
regulations cover, and the sorts of things they may pertain to. 

## WHAT IS A REGULATION?

Let's talk about what a regulation is really briefly. This is my simplistic
developer view of this domain, and if you talked to a lawyer, you'd get a much
more nuanced view. For our purposes here today, those nuances aren't relevant. 

## CONGRESS ENACTS LAWS

The United States Congress enacts laws. You've all heard of bills (they are
talked about often in the news), and when those bills are approved they become
laws also known as statutes. 

## Statutes are implemented by regulations

Congress in those statutes, provides the relevant federal agencies (like the
EPA, and the FAA) to  actual implement the details of the law. So an example
would perhaps be that Congress enacts a statute that specifies that factories
must reduce carbon emissions by 80%. That statute would give the EPA the
authority to figure out and implement the details of how to make that work. 

## Regulations specify 

(Just read this out)

## 37,022

That's how many changes to regulations were made in the past 10 years. That's a
lot of changes, an average of 3700 a year, and having read a handful of those,
they are long and complex. having read a very small fraction of  those




## 37,022

Between fiscal years 2004 and 2013 (an approximately 10 year period), federal
government agencies put out 37,022 final rules. Think of a final rule as a
change to a regulation. 

## REGULATIONS ARE HARD TO READ

Most lawyers, when they read the law, read it in PDFs in this three column
format with a small font size. This is a document that has a well-defined
hierarchy. This hierarchy is not visually represented here. As a person who
programs in Python, the lack of indentation is disturbing.

There is an online version of the Code of Federal Regulations. It's a little
more structured, but it has some of the same problems. The Code of Federal
Regulations is an index of the regulations organized by topic. So, earlier when
we were talking about seat belts in airplanes, that was Title 14 (Aeronautics
and Space). 

Many words in a regulation are specifically defined for the regulation.
However, the defined terms are not called out in the text. The list of words
that are defined is usually housed in one section of a regulation but these
definitions words can also be dispersed throughout. You basically have to
memorize the list of terms that are defined before reading any paragraph. The
definitions are also scoped in the sense they they can be redefined for a
particular section. 

Regulations sometimes have a section at the bottom, that goes over the entire
regulation, explaining the intent of specific sections. This is called
Supplement I. It's really important because it contains the official
interpretation of paragraphs of the regulation. It's meant to be read side by
side with the regulation text. But it's all the way on the bottom. Also,
because it explains the law, it's typically very long. In a particular
regulation I looked at, it was approximately 62.5% of the regulation. But it
doesn't have it's own table of contents to make it easier to only read
particular parts.

## REGULATIONS ARE HARD TO FIND

Final rules are amendments to regulations. These rules are published in the
Federal Register which can be thought of as a journal or blog for the United
States Government. What this means though, is that often we only ever have a
list of changes to a regulation, and not the full compiled version of the
regulation. This makes it hard to see what changes are going to be effective
soon, or even how the regulation evolved. 

## YOU CAN NOT TRAVEL BACK IN TIME

Past versions of a regulation are extremely hard to find. So, if you are
wanting to know what regulation was in effect on a particular date - that's
almost impossible to figure out without a whole lot of manual work.

## DEMOCRACY

You as an ordinary citizen can comment on these regulations, and perhaps change
the course of the law. That's a pretty exciting and powerful concept. 

Let's walk through the process of what commenting would be like:

You would first have to read the Federal Register almost daily to be informed
of upcoming changes. There is no topic-based subscription. 

Once you've found the notice, you would then have to read potentially 100s of
pages of text and comprehend all of those words to understand the change being
made. Then you'd go to another rather poorly designed website to comment on the
change. 

You can not select particular paragraphs or sentences you are commenting on.
All you are provided with is one text box to comment on the entire set of
changes. This makes it hard to provide specific, detailed feed back. It also
makes it hard on the person at the receiving end of the comment to interpret
what you're saying. 

Citizen participation is very low, and this is not suprising. 

## Everything is broken 

Since a lot of us are developers, let's summarize some of these problems. 

(go through problems)

So, everything really is broken. 

If you think about these problems, you'll quickly realize that as developers
these problems look familiar. We've all built systems that have one or more of
these features. 

There aren't many developers who work in this space. This space that's at the
intersection of regulations and software development. 

## OSS VENN DIAGRAM 

Open source meetups and conferences are great because at some point someone
brings up open source licenses and we're automatically back at this
intersection. 

I invite you all to come help improve the regulation space. It definitely needs
more developers who can transform how regulations are written, read, analyzed
and complied with. 

## TEXT TO DATA

And to start solving some of these problems what we need is this regulation
content in a decent digital/electronic format, so that we can start improving
things. We need all this text turned into actionable data. 

## NO REASONABLE DIGITAL VERSION

However, I've got some bad news for you. There is no reasonable digital format
that these regulations are in either. 

If we did have the regulations and notices in a format that's easily digestible
by software, we could not only solve most of the problems I've mentioned
previously, but also create some really interesting things. 

## Legalese to Plain English Converter

We could to the automatic conversion or summarization of regulations into plain
English. This is something that's very necessary as there is too much material
to do this manually, and automatiohn would really help this along. I think
there some really interesting natural language processing challenges here. 

## Analytics and Heat Maps

Using analytics and generating content heatmaps on each of the regulations
would let us know which sections or paragraph sare read the most, or even read
over and over again - indicating that the  text needs to be either explained
more, or even rewritten. 

## Annotations 

Because the regulations are long and relatively complex documents, it would be
nice to be able to add your own notes as you read paragraphs. It would be even
nice then to be able to share those annotations with your peers. 

## Does this regulation apply to me?

Automatic ways of determining which regulations or which parts of a regulation
apply to a particular stakeholder. Maybe you're an airline (and not an aiport)
and need to know which regulations apply specifically to you. 

## Authoring tools

Better authoring tools are also necessary. They'll prevent duplication of
content, can automatically determine readability issues, and can eliminate
errors. 

## Text to Data 

And now I've taken you through the journey that some of my colleagues and I
went through about a year aga. We thought about the problems with the current
offering of online regulations, and thought deeply about the world that could
be. To build anything, we first needed to build something that would take
regulation text and turn it into data, and it's that piece I want to spend some
time talking about to you folks today. 



---- 

I'd like to take the time today and walk you through how regulation text gets
processed through our system for display. 

Here's a typical screen from our application. We're showing a section
of the regulation with all sorts of additional information. We've got a
clearly defined hierarchy in the text, official interpretations inline with the
paragraphs they refer to, internal citations, defined terms highlighted, a link
to the section by section analysis for this section amongst other things.
Building this page from regulation text, is an automated process. Let's
walk through what it takes to build this page like this one. 

There are three major steps to eRegs. We go through multiple phases of parsing
to extract and create the data that we need for our application. The data
generated are stored in our API which we turn around and use to display the
regulation. 

Let's talk about parsing. 

Regulations are fairly well structured documents. Each section is numbered
(we're looking at section 4 here), and then each paragraph addressable in a
well-structured scheme. Here we have 1005.4 (a)(1), 1005.4(a)(2), and
1005.4(b). Our parser takes each paragraph of the regulation, and puts it into
a data structure. Once we have a paragraph level representation of the
regulation, we can start parsing additional things, and doing other
computations (such as creating diffs). 

How do you conceptually store each paragraph of the regulation? Any structured
document like a regulation can be represented as an n-ary tree. The root node
is the part number of the regulation, it's children are the various
sections, and so on. A tree representation like this allows us to individually
access each paragraph, but still reconstruct the document easily.  The first
phase of our parser takes the regulation plain-text, and determines the tree
representation. We use JSON to represent the tree. If you read this slide
bottom to top, you get a better sense of the tree structure. 

Now that we've got the basic structure of a regulation, let's go back to a
regulation paragraph and note all the additional bits of information that need
to be parsed out. We have key terms (a subject summary for each paragraph),
terms that have been defined in the regulation, internal citations and external
citations. Each paragraph has multiple types of data, and multiple occurrences. 

Each bit of extra data is represented as a layer. A layer is a key-value pair
between paragraphs and (for example) the location of key terms. All a layer
does is specify where some extra bit of information exists. We use layers
extensively to represent all the bits of data that are extracted from, but
aren't the pure regulation text. The second phase of parsing goes through the
regulation tree and creates layers items for each paragraph. Layers are
intended to be combined with the regulation tree to create an enhanced
regulation viewing experience. 

Most of the data we extract is from the regulation text. But when we start
dealing with the timeline of a regulation, or a section by section analysis of
paragraphs we have to start parsing documents that are created during the rule
making process. These documents are called notices and are published in the
Federal Register. Phase 3 of parsing is extracting information from the XML
representation of these notices. 

The parser is run once for every version of the regulation, and extracts all
the data we need. The parser populates our Django application that runs our
data API. 

Once our data is being served by the API, we can actually start displaying a
regulation paragraph. Taking a look at the markup between a single regulation
paragraph provides a good representation of what's happening behind the scenes.
The bits in red are the actual regulation text, the rest is markup from all the
layers we apply to the paragraph. 

Applying layers is hard because layers are nested, and there are multiple
layers per paragraph. When a layer is being applied, what we're actually doing
is replacing the text at a location in the paragraph with new (marked up) text.
The location of a word changes as a layer is applied to preceding words.  We've
got some fairly complex code that accomplishes this, and delivers the markup to
the interactive part of our application. 

A primary feature of eRegulations is the ability to view past, current, and
future versions of a regulation. Previously, the source content that was fed to
the parser to generate each version was created manually. The most significant
change we made over the past six months was to automate this process.

Each version of a regulation consists of a series of Federal Register (FR)
final rule notices applied to the previous version of the regulation. Each
notice describes changes to individual paragraphs of the regulation (think of
it like a diff).

A change can add, revise, delete, or move a paragraph and looks something like
this.

Lines 1 and 2 describe which paragraph has changed, and how it has changed
(known as the amendatory instructions). Line 3 shows you how paragraph 1026.35
(e) reads after the revision. A notice can contain multiples of these changes.

Each version of a regulation on our platform is represented on the back end as
a data structure (more specifically an ordered n-ary tree) that represents the
entire regulation at that point in time. For each version of Regulation E, we
manually read each FR notice and meticulously compiled plaintext versions that
were fed to our parser to generate the tree structure. This was possible since
in Regulation E we have three versions consisting of eight FR notices.
Regulation Z, on the other hand, has 12 versions and 23 notices. Manual
compilation of versions would be inefficient and more prone to error. It also
is not a sustainable solution going forward. We wanted to be able to simply
start the parser when the next Regulation E or Z notice was published –
without having to manually apply the changes from the new notice.

We now automatically compile regulation versions. Each FR notice is processed
by parsing the amendatory instructions (what has changed) and the actual
changes (how it has changed), matching those up, and compiling the changes into
a new version. Each FR notice has a corresponding XML representation – this
also drove the conversion of our parser from being text-based to XML-based.
This resulted in a far more sustainable application requiring less manual
intervention to add an additional regulation.

An individual regulation paragraph can change in a limited number of ways. A
paragraph can be added, revised, moved, or deleted. Usually, these changes are
written with reasonably consistent phrasing – making parsing them
tractable. However, sometimes there are exceptions when the change is not
expressed as clearly as possible. Adding rules to the code for these exceptions
would have diminishing returns in the sense that the effort of getting the code
correct, tested and ensuring that it doesn’t break any of the other
parsing, would far outweigh the benefits of the unique rule. To handle those
special cases, we built a mechanism to allow us to keep local copies of the XML
notices taken from the Federal Register and make changes to that copy to make
it easier to parser. The parser looks first in our local repository of notices
to see if a copy of a required notice exists, before downloading it from the
Federal Register. This enabled us to gracefully handle phrases that aren’t
used frequently enough to warrant their own custom rule.

And now, we have text as data, and a platform on which to solve many of the
problems I talked about earlier. 
