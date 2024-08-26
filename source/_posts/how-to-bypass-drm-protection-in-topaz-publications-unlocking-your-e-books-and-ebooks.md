---
title: "How to Bypass DRM Protection in Topaz Publications: Unlocking Your E-Books and eBooks"
date: 2024-08-20T09:38:14.358Z
updated: 2024-08-21T09:38:14.358Z
categories:
  - epubor
thumbnail: https://thmb.techidaily.com/843c206a00e28cb365bf9ba5dd05332331c8b283e7e323acfc8d381ef1640599.jpg
---

## How to Bypass DRM Protection in Topaz Publications: Unlocking Your E-Books and eBooks

## Topaz DRM Removal, Remove DRM from Topaz/TPZ/AZW1 on Kindle

Posted by [Ada Wang](https://plus.google.com/+AdaWang/posts) on 4/19/2019 9:23:50 AM.

3 [(0 comments)](http://www.epubor.com/#comment-area) 



![follow](http://www.epubor.com/images/follow.png)

Somebody asked how to remove DRM from kindle topaz books. Here is the full guide for removing topaz DRM and converting topaz files to epub, pdf etc.

###  What's Topaz 

Topaz is an Amazon format for Kindle devices. It differs from the AZW format in that as it can have embedded fonts in the file itself. A .tan sidefile is used to store metadata and bookmarks and other user generated content on the eBook. The metadata is used to help the library mode to reference information about the eBook itself.   
  
While not much is currently known about the internal format used in a Topaz file is that, there is some likelihood that it is related to the standard AZW format. It uses a different compression than standard MOBI files and it can have embedded fonts in the file allowing more complex display using font sets and characters that are not standard to Amazon Kindle. It is also likely to remove other restrictions found in MOBI files such as image size limitations although some of these may have been removed in AZW as well.   
  
According to one publishing industry blogger, Topaz is an implementation of the open EPUB standard. It follows the OEBPS 2.0 specs, and probably the later IDPF guides. It’s a proprietary implementation which means they use ePUB as the source but then convert it to their internal format.  
  
**AZW1** \- an eBook in the Topaz (TPZ) format that has been delivered via Whispernet.   
**TPZ** \- an eBook in the Topaz format that has been delivered via Internet download. 

Tips

* [Best tools to remove DRM from Kindle (TOPAZ/AZW) with high quality](https://tools.techidaily.com/epubor/products/)
* [Calibre helps you to convert Kindle books to EPUB free](https://tools.techidaily.com/epubor/products/)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
### **How to use Topza DRM Removal to remove drm from topaz/azw1/tpz**

**1\. Authorize** your copy of Kindle for PC and "Sync and check for new items".

Install **Kindle for PC** and authorize your copy.

**2: Load Kindle eBooks.**  
View the book in Kindle for PC. (In other words, make sure it is downloaded to your computer, not in “Archived Items”.)

**3\. Run [TPZ DRM Removal](https://tools.techidaily.com/epubor/ultimate/)to remove drm from kindle(topaz , tpz, azw1).**   
[](https://tools.techidaily.com/epubor/ultimate/) [](https://tools.techidaily.com/epubor/ultimate/) A dialog window will pop up:  
Browse for input directory, default as "..\\My Documents\\My Kindle Content\\".

![Kindle TopAZ DRM Removal](https://www.epubor.com/images/kindledrmremoval.jpg "Kindle DRM Removal")

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
Epubor Ultimate can help you remove DRM from AZW,AZW1, PRC, Mobi, TopAZ(.tpz) books with ease, which requires you to set the "**Optional Setting**".

![Kindle TPZ DRM Removal](https://www.epubor.com/images/kindledrmremoval-setting.jpg "Kindle DRM Removal")

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
**Removing DRM from Topaz files**, Kindle tpz DRM Removal requires your **kindle.info** file which can be found in something like:  
\\...\\Amazon\\Kindle For PC\\  
where ... varies by platform but is "Local Settings\\Application Data" on XP.

![Kindle.info](https://www.epubor.com/images/kindle.info.jpg "Kindle DRM Removal")

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
After removing topaz/azw1/tpz DRM, you can use Calibre to convert books files, [Download the best ebook converter Calibre](https://tools.techidaily.com/epubor/products/).

#### **Topaz: I used the tools on a Kindle file, and got back three files instead of one. Which one is the de-drmed ebook?**

The Topaz file format contains two versions of the book plus a composite xml description of the book.

The \_SVG file is a zip archive of the scalable vector graphics (svg) image of each page of the book. Each image is comprised of a list of glyphs and positions. It is pretty much an exact copy of the original book, but made of up of images, not text.

The second version is the text version, unchecked by human eye. It contains the usual kinds of errors you’d expect in OCRed text. This is the version used to create the HTML “\_nodrm” zip archive. Neither DeDRM nor Calibre are causing the errors – the errors are in the OCR stored in the original ebook.

The third file contains the XML files which truly are the Topaz internal format.

If you want to understand this format better, unzip this file and open any of the xml files with a text editor.

You can import the HTML version (\_nodrm.zip) into Calibre to convert it to epub, mobi, etc as it is easily reflowable and convertible but it may need spellchecking and hand editing to clean it up the OCR errors. You can also import the set of SVG images into Calibre or other PDF creation software and convert them to an image-only based PDF.

[](https://tools.techidaily.com/epubor/ultimate/) [](https://tools.techidaily.com/epubor/ultimate/) 

Keywords: Topaz DRM Removal, TPZ DRM Removal,Kindle DRM Removal, AZW1 DRM Removal

![author](https://www.epubor.com/images/uppic/1-22-2013 12-03-06 AM.png)

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
[Ada Wang](https://plus.google.com/+AdaWang/posts) works for Epubor and writes articles for a collection of blogs such as ebookconverter.blogspot.com.

SHARING IS GREAT!

[Tweet](https://twitter.com/share) 

[SAVE PAGE AS PDF](https://tools.techidaily.com/epubor/products/) 



0 Comments

[reply](https://tools.techidaily.com/epubor/products/) [reply](https://tools.techidaily.com/epubor/products/) 

Leave a comment

| Rating |  |
| ------ |  |

| YourName | \*  1 to 50 chars |
| -------- | ----------------- |

| email | Internet Email |
| ----- | -------------- |

| Comments | UBB Editor |
| -------- | ---------- |

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>