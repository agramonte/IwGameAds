IwGameAds
=========

Current status:
Working on Marmalade: 6.3.1

Tested Ad Networks: MMedia, Inner-Active.

I have been using the Pocketters Limited iwgameads-sdk for a while now. I tend to upgrade my Marmalade sdk as soon as the new version comes out (or as soon as I can). As of version 6.2.x of Marmalade due to the changes to the 2D engine, working with iwgameads-sdk required declaring a directive in the MBK to use the non-float methods. 

Although this approach would be suficient for many, some of the advertisers URL have become out of date as well and the data that they return wouldn't be parsed correctly. Since I was not able to send my bug fixes or improvements (the link is broken on the page), I decided to create this repository. 

This is no way an attempt to co-op other people's code. I can't find the actual license for the iwgameads SDK other then a statement that it is open source. That being said, if at any time Pocketters Limited or DrMop wants this repo taken down, I will gladly do so.

My changes are limited to making it work correctly with the latest version of Marmalade and in the 2D engine. I have no plans to add enhancements or new features. Although I do plan to add at least one new ad provider. If you find a defect in that limited scope, I will gladly look at it when time permits.

In no way am I or these changes associated with drmop or Pocketters Limited. You can still find the current version of IwGame here: www.drmop.com/index.php/iwgameads-sdk
