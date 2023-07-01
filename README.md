# special-spoon
* skip to content
GitHub Archive Program logoReturn to homepage
GitHub Archive Program Invertocat logoReturn to homepage
Our Approach
Greatest Hits
Arctic Vault
Partners
Press
menu iconclose icon
Our Approach
code ascii pattern
We are preserving open source software for future generations with a multi-pronged approach.
This includes partnerships with accessible online archives, such as Software Heritage and the Internet Archive; donations of reels of film on which GitHub’s “greatest hits” have been archived, to the Bodleian Library, the Bibliotheca Alexandrina, and Stanford Libraries; and the 188 reels of film now stored in the Arctic Code Vault in Svalbard, Norway, which preserve a snapshot of every active public GitHub repo as of 02/02/2020.

LOCKSS

Why we use multiple forms of storage
As today’s vital code becomes yesterday’s historical curiosity, it may be abandoned, forgotten, or lost. Worse, albeit much less likely, in the case of global catastrophe, we could lose everything stored on modern media in a few generations. Archiving software across multiple organizations and forms of storage helps to ensure its long-term preservation. Online archivists call this "LOCKSS," for Lots Of Copies Keeps Stuff Safe.

A worrying amount of the world's knowledge is currently stored on ephemeral media: CDs good for a few decades, backup tapes whose notional 30-year lifespans assume strictly controlled heat and humidity. Because (some) hardware can be much longer-lived, there exists a range of possible futures in which working modern computers exist, but their software has largely been lost to bit rot. The GitHub Archive Program includes much longer-term media to address the risk of data loss over time.

storage
THE FUTURE

How the future might use our code
Future historians will be able to learn about us from open source projects and metadata. They might regard our age of open source ubiquity, volunteer communities, and Moore’s Law as historically significant. We are partnering with Stanford Libraries to help archive curated repositories along with the cultural and other context in which they are set, as key elements of wide-ranging historical and social research and analysis.

Because hardware can be much longer-lived than most of today’s storage media, especially older ones and/or those with mask ROM, there exists a range of possible futures in which working modern computers exist, but their software has largely been lost to bit rot. The Archive Program preserves that software.

Even in the near future, storing data with multiple partners provides options to people whose access might otherwise be restricted. If GitHub were to become unavailable in any location, for example due to an internet routing issue, those affected could access public code for their projects using the Internet Archive and Software Heritage Foundation.

There is a long history of lost technologies from which the world would have benefited, as well as abandoned technologies which found unexpected new uses, from Roman concrete, or the anti-malarial DFDT, to the hunt for mothballed Saturn V blueprints after the Challenger disaster. It is easy to envision a future in which today’s software is seen as a quaint and long-forgotten irrelevancy, until an unexpected need for it arises. Like any backup, the GitHub Archive Program is also intended for currently unforeseeable futures as well.

Saturn V Rocket
Saturn V

After the Challenger disaster, a hunt for the blueprints of the abandoned Saturn V rocket ensued. They were largely recovered, thanks to the work of archivists.

Library of Alexandria.jpg
Library Of Alexandria

Hundreds of thousands of texts, comprising an enormous amount of classic literature, science, and culture, were lost with the Library of Alexandria.

pantheon
Pantheon

Rome’s 1800-year-old Pantheon remains the largest unreinforced concrete dome in the world, thanks to Roman concrete, a technology whose properties were only rediscovered in 2014.

Pace Layers Strategy
A flexible, durable strategy for archiving code.

We've adopted a “pace layers” strategy for archiving code, inspired by Long Now founder Steward Brand. This approach is designed to maximize both flexibility and durability by providing a range of storage solutions, from real-time to long-term storage. The Archive Program is partitioned into three tiers: hot, warm, and cold.

Hot
// Near real-time
Warm
// Updated monthly to yearly
Cold
// Updated every 5+ years
GITHUB
On every push to GitHub, we replicate your Git data to multiple datacenters around the world. Additionally, we store backups of Git data, Issues, Pull Requests, and all of your data on GitHub in multiple locations. All of this data is available live via the GitHub API.

GH TORRENT
GHTorrent monitors the GitHub public event timeline, archives those events, and makes them queryable using BigQuery. You can also download snapshots by hour, day, or month.

GH ARCHIVE
GHArchive monitors the GitHub public event timeline, archives those events, and recursively crawl and archive their contents and dependencies. Those archives will then be made available for download on a daily or monthly basis.

INTERNET ARCHIVE
The Internet Archive’s well-known Wayback Machine will crawl GitHub’s public repositories—including new repositories, issues, pull requests, wikis, and more—and store copies on hard drives in San Francisco and other locations. These archives will be publicly available via git and https.

SOFTWARE HERITAGE FOUNDATION
The Software Heritage Foundation will crawl GitHub on a regular basis and add its public repos to their archive, to which they provide public API access.

ARCTIC WORLD ARCHIVE
On February 2, 2020, GitHub will capture a snapshot of every active public repository, to be preserved in the GitHub Arctic Code Vault. This data will be stored on 3,500-foot film reels, provided and encoded by Piql, a Norwegian company that specializes in very-long-term data storage. The film technology relies on silver halides on polyester. This medium has a lifespan of 500 years as measured by the ISO; simulated aging tests indicate Piql’s film will last twice as long.

BODLEIAN LIBRARY
Oxford University’s Bodleian Library will provide redundancy for the Arctic Code Vault by keeping GitHub’s 10,000 most-starred and most-depended-upon repositories in their depository as duplicate Piql film reels.

BIBLIOTHECA ALEXANDRINA
The Bibliotheca Alexandrina will provide redundancy for the Arctic Code Vault by keeping open source’s “greatest hits” containing 17,000 of the most-starred and most-depended-upon repositories in their depository as duplicate Piql film reels.

STANFORD LIBRARY
Stanford Library will provide redundancy for the Arctic Code Vault by keeping open source’s “greatest hits” containing 17,000 of the most-starred and most-depended-upon repositories in their depository as duplicate Piql film reels.

PROJECT SILICA: MICROSOFT RESEARCH
The GitHub Archive Program is partnering with Microsoft’s Project Silica to ultimately archive all active public repositories for over 10,000 years, by writing them into quartz glass platters using a femtosecond laser.

TOOLS FOR THE FUTURE

How we’re ensuring the future can use our software
We assembled a GitHub Archive Program advisory panel, including experts in anthropology, archaeology, history, linguistics, archival science, futurism, and more, to advise us on what content should be included in the archive and how to best communicate with its inheritors.

A thousand years is a very long time. Ancient ruins such as Angkor Wat, Great Zimbabwe, and Macchu Picchu had not yet been built a thousand years ago. Nevertheless, we can consider and plan for a broad range of possibilities over the next 1,000 years. This program builds on the best ideas we have today.

The introduction to the archive will include technical guides to QR decoding, file formats, character encodings, and other critical metadata so that the raw data can be converted back into source code for use by others in the future. The archive will also include a Tech Tree—a roadmap and Rosetta Stone for future curious minds inheriting the archive’s data.

An overview of the archive and how to use it, the Tech Tree will serve as a quickstart manual on software development and computing, bundled with a user guide for the archive. It will describe how to work backwards from raw data to source code and extract projects, directories, files, and data formats.

Inspired by (and including elements of) the Long Now’s Manual for Civilization, the archive will also include information and guidance for applying open source, with context for how we use it today, in case future readers need to rebuild technologies from scratch. Like the golden records of Voyager 1 and 2, it will help to communicate the story of our world to the future.

In the range of possible futures in which humanity has working modern computers, but no software to run on them, the archive and its Tech Tree could be extremely valuable. However, the value is more likely to be historical, perhaps ensuring that today’s technology is not lost by a tomorrow that carelessly considers it irrelevant—until an unexpected use for our software is discovered.

FAQ
Exploreoutgoing link icon
Join GitHuboutgoing link icon
Become a Partneroutgoing link icon
