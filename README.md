# LingBuzz Archive

Michael Yoshitaka ERLEWINE <mitcho@mitcho.com>

[LingBuzz](http://ling.auf.net/lingbuzz) is a manuscript and preprint repository for the field of linguistics and has become a valuable community resource. Citation of pre-publication manuscripts from LingBuzz occur with some regularity, often referring to the LingBuzz entry number. ([More on LingBuzz](http://ling.auf.net/buzzdocs/)) Unfortunately the LingBuzz server is sometimes inaccessible and there have been periods in the past where the server has been completely down for extended periods of time. This archive is meant as a public "backup" of these files.

The archive is organized into folders, corresponding to LingBuzz entry numbers and URLs. In each folder, there is a `index.html` page, which is a recently downloaded copy of the entry's HTML page, and each revision as a separate file (`v1.pdf`, `v2.pdf`, etc.). The archive does not contain any material which is not publicly available on the LingBuzz site.

# [👉 Enter the archives 📚](https://github.com/mitcho/lingbuzzarchive/tree/archive)

Technical detail: This is the `master` branch. The archives are on the [`archive` branch](https://github.com/mitcho/lingbuzzarchive/tree/archive).

If you are glad this exists, you might also like my [LingBuzz RSS feed](https://github.com/mitcho/lingbuzzrss) and [twitter account](https://twitter.com/LingBuzz).

# Q&A

## Will search engines link to the files in this archive?

No. Search engines (should) respect [GitHub's `robots.txt` file](https://github.com/robots.txt) which disallows the crawling of files stored here. (Technical details: `master` branches on GitHub get crawled by search engines, which is why I put the archive in a branch called `archive`.)

## Can I download this entire archive?

Yes. GitHub offers [a ZIP archive](https://github.com/mitcho/lingbuzzarchive/archive/archive.zip) of the current archive, but be careful because this file will be huge. A better idea is to [clone this repository](https://help.github.com/articles/cloning-a-repository/) locally, after which you can use the Git software to efficiently keep your local copy up-to-date in the future.

## How does this work?

I wrote a script called [lingcrawl](https://github.com/mitcho/lingcrawl) which systematically reads LingBuzz and downloads all the files missing in the local archive. I then push the files in my local archive up to this GitHub repository.

## How often is this archive updated?

Right now updating is manual. I will probably automate this soon, so it happens maybe once a week. (Overwhelming the LingBuzz server with frequent requests from my crawler would be counterproductive.)

