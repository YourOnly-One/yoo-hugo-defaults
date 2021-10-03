+++
title = "「」 review/批評/비평"
description = ""                                                    # For Schema.org; OpenGraph; Twitter Cards; and post summary

date = "{{ .Date }}"                                        # manually adjust to local timezone
#lastmod = "2021-04-07T17:53:01"                                     # manually adjust to local timezone

#aliases = [""]
slug = ""
translationKey = ""
relCanonical = ""                                                   # the actual URL of the post; also used for disqus ID and url
#disqus_url = ""                                                    # automatic in YourOnly.One setup
#disqus_identifier = ""                                             # highly recommended by Disqus; automatic in YourOnly.One setup

channels = [""]
categories = [""]                                                   # taxonomy
keywords = [""]                                                     # meta keywords
series = [""]                                                       # subset of series taxonomy
tags = [""]                                                         # taxonomy

comments = true
#weight = ""                                                        # post weight, if we want granular control of post order

#featured = true
#math = true
toc = true

#videos = [""]                                                       # used by og:video, etc.
#audio = [""]                                                        # used by og:audio, etc.
images = [""]                                                       # used by og:images, etc.; first image is cover image

draft = true

#license = ""                                                       # only set if the post license is not the same as the site license

contenttypes = ["CriticReview"]                                                 # Semantic Web JSON-LD
[semweb]                                                            # Semantic Web JSON-LD
  type = "Book, Movie, TVSeries"                                    # choose one

# If different from our website
#[semweb.publisher]
#  name = ""
#  sameas = [""]

# If different from default author
#[semweb.author]
#  sameas = [""]

# For adaptations
#[semweb.product.isbasedon]
#  name = ""
#  alternatenames = [""]
#  sameas = [""]

#[semweb.product.isbasedon.author]
#  name = ""
#  alternatenames = [""]
#  sameas = [""]

# Video URLs can be any, YouTube provided as a guide only
[semweb.video]
  name = ""
  description = "「CHANGE_THIS」 trailer/予告編/예고편"
  uploaddate = ""
  thumbnailurl = "https://img.youtube.com/vi/CHANGE_THIS/hqdefault.jpg"
  contenturl = "https://www.youtube.com/watch?v=CHANGE_THIS"
  embedurl = "https://www.youtube-nocookie.com/embed/CHANGE_THIS"

[semweb.review]
  snippet = ""
  rating = ""

[semweb.product]
  name = ""
  #alternatenames = [""]
  sameas = [""]
  countryoforigin = ""
  description = ""
  datepublished = ""
  categories = [""]

# For TVSeries
#[semweb.product.season]
#  name = "Season 1 / シーズン1 / 시즌 1"
#  totalepisodes = ""
#  start = ""
#  end = ""

# For TVSeries and if reviewing an episode
#[semweb.product.season.episode]
#  epnumber = ""
#  name = "Episode"
#  datepublished = ""

# Duplicate for more Actor entries
[[semweb.actor]]
  name = ""
  #alternatenames = [""]
  sameas = [""]

# Duplicate for more Character entries
[[semweb.character]]
  name = ""
  #alternatenames = [""]
  sameas = [""]

# Duplicate for more Director entries
[[semweb.director]]
  name = ""
  #alternatenames = [""]
  sameas = [""]

# For /yuki/ choose one and remove everything else
#[author]
#  #name = ""
#  #email = ""
#  homepage = ""
#  avatar = ""
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "YOOki Chronicles / YOOkiクロニクル / YOOki 연대기"
#  #email = ""
#  homepage = "https://im.youronly.one/yuki/"
#  avatar = "https://rsc.youronly.one/img/y/Yuki_flag-square-300x.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "Confident Traveler / 自信のある旅行者 / 자신감있는 여행자"
#  #email = ""
#  homepage = "https://im.youronly.one/confidentraveler/"
#  avatar = "https://rsc.youronly.one/img/y/Confident_Traveler-logo-01-1500x.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "Faithful Athlete / 忠実なアスリート / 충실한 운동 선수"
#  #email = ""
#  homepage = "https://im.youronly.one/faithfulathlete/"
#  avatar = "https://rsc.youronly.one/img/y/Faithful_Athlete-logo-02-1500x.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "Love and Relationship / 愛と関係 / 사랑과 관계"
#  #email = ""
#  homepage = "https://im.youronly.one/love/"
#  avatar = "https://rsc.youronly.one/img/y/Love_and_Relationship.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "Snoworld / 雪の世界 / 스노우 월드"
#  #email = ""
#  homepage = "https://im.youronly.one/snoworld/"
#  avatar = "https://rsc.youronly.one/img/y/snoworld-square.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "techmagus / ハイテク マギ / 테크 마구스"
#  #email = ""
#  homepage = "https://im.youronly.one/techmagus/"
#  avatar = "https://rsc.youronly.one/img/y/techmagus-Architetto-Esperiment-chimico.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "Verses.Space (KWWP)"
#  #email = ""
#  homepage = "https://verses.space"
#  avatar = "https://rsc.youronly.one/img/y/KWWP-logo-01-1280wh-transparent.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "Way of Believers / 信者の道 / 테크 마구스"
#  #email = ""
#  homepage = "https://im.youronly.one/way/"
#  avatar = "https://img.youronly.one/works/FlagMenorah-Proto-(CC0).webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "Health Welfareness / 健康福祉 / 건강 복지"
#  #email = ""
#  homepage = "https://health.youronly.one"
#  avatar = "https://rsc.youronly.one/img/y/CHANGE_THIS.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "Wealth Welfareness / 富と福祉 / 부 복지"
#  #email = ""
#  homepage = "https://wealth.youronly.one"
#  avatar = "https://rsc.youronly.one/img/y/CHANGE_THIS.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"

#[author]
#  #name = "Yūgen Bard / 幽玄吟遊詩人 / 幽 玄 음유 시인"
#  #email = ""
#  homepage = "https://im.youronly.one/yugenbard/"
#  avatar = "https://rsc.youronly.one/img/y/Yūgen_Bard-logo-01-1500x.webp"
#  #emoji = ""
#  #descriptionshort = ""
#  #descriptionlong = ""
#  #motto = ""
#  #locationorigin = ""
#  #locationcurrent = ""
#  #rel = "me noopener"
+++

SUMMARY

<!--more-->

> ***TAGLINE***

## Synopsis / 筋書き / 개요

[^a]: SOURCE_NAME: [「PRODUCT_TITLE」 synopsis/筋書き/개요](LINK); [CC-BY-SA 3.0 Unported License](https://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License)

## Story / 物語 / 이야기

## Performance / 演技 / 공연

## Image code
{{< image
  type="image"

  imgheight=""
  imgwidth=""

  imgsrc=""
  imglink=""
  imgrel="noopener external nofollow"

  imgtitle=""
  imgcaption=""
  imgalt=""

  attribalign=""

  licensecode=""
  licenseurl=""
  licensename=""

  attribto=""
  attriblink=""
  attribrel="noopener external nofollow"
>}}

## Music / 音楽 / 음악

## Production / 製作 / 제작

## Verdict / 評決 / 평결

## Other markdown codes
[SOME_LINK](https://example.com)

[POST_TITLE]({{< ref "/FILENAME.md" >}} "TITLE_ATTRIBUTE")

## Official trailer / 公式予告編 / 공식 예고편
{{< youtube id="CHANGE_THIS" title="「CHANGE_THIS」 trailer/予告編/예고편" >}}

## OST
{{< music src="https://open.spotify.com/embed/playlist/CHANGE_THIS" >}}

## Attribution, Usage, &amp; Leave your links
Simply follow the attribution shown underneath each photo, or whichever is acceptable within the bounds of CC-BY-SA 4.0 International license. In addition to that, I would also appreciate if you leave your links below or in Instagram, who knows, I might mention your site (and usage) one day.

-------

{{< image
  type="imagecoverattrib"

  imglink=""
  imgrel="noopener external nofollow"

  imgtitle=""
  imgcaption=""

  licensecode=""
  licenseurl=""
  licensename=""

  attribto=""
  attriblink=""
  attribrel="noopener external nofollow"
>}}

-------

注意：Google翻訳
고시 : Google 번역
