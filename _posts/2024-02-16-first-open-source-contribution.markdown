---
layout: post
title:  "Making my first open source contribution"
date:   2024-02-16 00:00:00 -0000
---

## Thoughts on open source contributions

I've had admiration for open source since my high school and college years. I used to read books such as The Cathedral and the Bazaar by Eric S. Raymond. I read posts by Richard M. Stallman and other prominent open source developers. I read stories about how Mark Shuttleworth sold his company and invested a small fortune on Ubuntu, the latest Linux distribution.

I admired open source developers, and I've always thought about contributing in some form or capacity, but until 2018, I had never done it. I had the motivation, but I always thought I didn't have good enough ideas. Ideas that would materialize into a finalized product and be used by millions.

I also contemplated what kind of personal gain would I get from open source. For most open source developers, there is no direct monetary gain. It is incredibly hard to start a successful company out of open source. Some of them do it as a hobby. Some of them do it with the hopes of getting a job. Some others do it to "scratch an itch", creating something that solves a problem for them.

## Leading up to my first contribution

I worked every day on a code base with hundreds if not thousands of files of source code and dozens of directories. My OS of choice was Ubuntu. I would often use Meld, a "visual diff and merge tool" to diff different versions of the code base. One pain point using Meld, is that Meld would expand every single directory, making it hard to focus on specific directories to compare. I would have to manually collapse all non-relevant directories until I only saw the directories I wanted to focus on. This was painful, it usually took a long time to do, and I had to do it repeatedly.

Here came my "scratch an itch" idea. I wanted a feature to collapse all directories recursively from the diff view, and expand all directories back. I searched in Meld's issue tracker for similar requests, and I found other users discussing the idea. This gave me extra motivation to work on it.

Meld showing expanded view
![Meld showing expanded view](/assets/images/meld-expanded.png)

## My Experience

I downloaded Meld's source code and spent a few days trying to understand the code base, making a proof of concept of the new feature. I cleaned up the code, and when I was done, I sent a merge request [Meld Merge Request 13](https://gitlab.gnome.org/GNOME/meld/-/merge_requests/13) on Gitlab. The project maintainer, Kai Willadsen, to my surprise, was quick to reply. He made some minor code comments which I promptly fixed, and an explanation of the use case, which I replied to. After this brief exchange, the code was merged!

The whole process was straightforward, and Kai made it easy for me to contribute. I felt proud about it, here I was, not just solving a problem for myself, but giving back to open source.

Meld showing collapse and expand actions:
![Meld showing collapse action](/assets/images/meld-collapse-action.png)
![Meld showing expand action](/assets/images/meld-expand-action.png)

## What could I have done better?

If I were to start again, I would first ask the project maintainer if they would accept a new feature I thought about before spending too much time implementing it. This might have saved me dozens of hours in another feature I wanted to implement, but never heard back from the maintainers, but that's a story for another day: [GNOME Nautilus - Jump to File](https://gitlab.gnome.org/GNOME/nautilus/-/issues/1157)

## Will I continue to contribute to open source?

Sure thing, working on that was fun. If I want to continue working on open source, I would probably try to make sure what I work on falls under at least one of the following categories:

* It scratches my own itch. Meaning, it would be something I use frequently.
* It makes a change in the world, hopefully, providing a feature that helps a lot of lives in the world.
* It advances my career goals. Including, learning technologies I will use at work, or that I would like to use at work.
* I can make money directly from a project.

I've thought about the last point, making money from a project. I have the belief this is an incredibly difficult feat to pull off, so my work would most likely fall under the other categories.
