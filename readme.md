Hi Team!

Here are the four simple steps for the elements we update to make the Free Ship No Min happen for the site. It’s actually even easier to do now than when I started drafting this email in January

first we will start by scheduling the Headband message that Michael G or Aney/Estelle sends us (if you don’t have it, ask for it!)

https://preview.indigo.ca/Admin/ContentDetails.aspx?id=43947&language=4105
check first that is not scheduled to do something else! If it is you’ll have to back whatever that is out, so please check with Michael G and/or Aney & Estelle what it is

PLEASE NOTE!!
You’ll see that the free shipping message is repeated in English, that second one is for any geo-targeting that might be happening.

EG: this is what is up at the moment:
```
<div class="headband  slider">
<div><a href="/freeshipping"><span>Free Shipping</span> to any store & on all orders<span> over $25*</span></a></div>
<div class="geotarget"><a href="/freeshipping"><span>Free Shipping</span> to any store & on all orders<span> over $25*</span></a></div>
</div>
```

You need to update both instances, so it would be like this (it should link to /free-ship-no-min which is a page that MG handles):
```
<div class="headband  slider">
        <div><a href="/free-ship-no-min">Free Shipping <span>NO MINIMUM</span> to Wednesday</a></div>
        <div class="geotarget”><a href="/free-ship-no-min">Free Shipping <span>NO MINIMUM</span> to Wednesday</a></div>
</div>
```
FYI: do NOT change the HB title in extra tools (Header Marketing Messages)

Workarea link for scheduling it:
https://preview.indigo.ca/WorkArea/workarea.aspx?page=content.aspx&TreeVisible=Content&action=viewStaged&id=43947&LangType=4105&menuItemType=viewproperties

please note, sometimes there are other messages in the HeadBand, but it’s only the free ship and the geotarget ones you need to update

do the same steps for french (which will link to /fr-ca/expedition-gratuite-aucun-minimum). French does not have a geotarget message

now for the free ship page
https://preview.indigo.ca/en-ca/freeshipping/ 

First, update the banner:
https://preview.indigo.ca/Admin/ContentDetails.aspx?id=18427&language=4105
no need to schedule, just publish! It’s hidden when not in use. The banner links to /free-ship-no-min 
(and same again in french! links to /fr-ca/expedition-gratuite-aucun-minimum)

Then the legal that appears below the banner (If the legal wasn’t sent to you with the banner links, you can find it in the brief on PWF. It’s basically just updating the dates in the legal that is there)
https://preview.indigo.ca/Admin/ContentDetails.aspx?id=13974&language=4105
again, hit publish – it’s hidden! Repeat in French

and finally, schedule the Control Block (take the scheduling time from the HeadBand)
work area:
https://preview.indigo.ca/WorkArea/workarea.aspx?page=content.aspx&TreeVisible=Content&action=viewStaged&id=31556&LangType=4105&menuItemType=viewproperties
use the history function to back to the last __freeship: NO MIN: ON

clear the scheduling that might be there and then schedule it to go live & publish!! that’s it!!!
Do the same for French!!!

And lastly, when you get in the day after the no min is live, turn back and schedule the Control Block to go back to the most recent __freeship: NO MIN: OFF (same for French!!!) clear scheduling, add new scheduling for when the offer ends – it’ll be in the legal, hit publish and forget about it

SO EASY!!

---
if you get lost or go too far back in history for the Control Block, here are the styles for the ON/OFF switch
For ENGLISH:

NO MIN: ON styles are:
```
<style type="text/css">
    .freeShipHdr, .freeTitle {display:none;}
    .noMinLegal {font-size: 12px; line-height: 20px;}
    .shipping span {display:none;}
</style>
```

And the NO MIN: OFF
```
<style>
    .noMinBanner, .noMinLegal {display:none;}
</style>
```

Until they update the French content to match the English,
The ON/OFF styles are slightly different:

NO MIN: ON
```
<style type="text/css">
    .freeShip25 {display:none;}
    .noMinLegal {font-size: 12px; line-height: 20px;}
</style>
```
NO MIN: OFF
<style type="text/css">
    .noMinBanner, .noMinLegal, .noMin {display:none;}
</style>



