+++
title = "「」 review/批評/비평"
description = ""                                                    # For Schema.org; OpenGraph; Twitter Cards; and post summary

date = "{{ .Date }}"                                        # manually adjust to local timezone
#lastmod = "2022-04-07T17:53:01"                                     # manually adjust to local timezone

#aliases = [""]
slug = ""
translationKey = ""
relCanonical = ""                                                   # the actual URL of the post; also used for disqus ID and url
#disqus_url = ""                                                    # automatic in YourOnly.One setup
#disqus_identifier = ""                                             # highly recommended by Disqus; automatic in YourOnly.One setup

channels = [""]
#categories = [""]                                                   # taxonomy
#keywords = [""]                                                     # meta keywords
#series = [""]                                                       # subset of series taxonomy
#tags = [""]                                                         # taxonomy

comments = true
#weight = ""                                                        # post weight, if we want granular control of post order

#featured = true
#math = true
toc = true

#audio = [""]                                                        # used by og:audio, etc.
images = [""]                                                       # used by og:images, etc.; first image is cover image
#videos = [""]                                                       # used by og:video, etc.

type = "review"                                                           # article, sitepage, review

draft = true

#license = ""                                                       # only set if the post license is not the same as the site license

contenttypes = ["CriticReview"]                                                 # Semantic Web JSON-LD
[semweb]                                                            # Semantic Web JSON-LD
  type = "Book, Movie, TVSeries"                                    # choose one

# For adaptations
#[semweb.product.isbasedon]
#  name = ""
#  alternatenames = [""]
#  sameas = [""]

#[semweb.product.isbasedon.author]
#  name = ""
#  alternatenames = [""]
#  sameas = [""]

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
#[[authors]]
#  person = ""
#  #id = ""
#  name = "ᜌᜓᜃᜒ (Yuki | 雪亮)"
#  url = ""
#  avatar = ""
#  rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "YOOki Chronicles / YOOkiクロニクル / YOOki 연대기"
#  url = "https://im.youronly.one/yuki/"
#  avatar = "https://rsc.youronly.one/img/y/Yuki_flag-square-300x.webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "Confident Traveler / 自信のある旅行者 / 자신감있는 여행자"
#  url = "https://im.youronly.one/confidentraveler/"
#  avatar = "https://rsc.youronly.one/img/y/Confident_Traveler-logo-01-1500x.webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "Faithful Athlete / 忠実なアスリート / 충실한 운동 선수"
#  url = "https://im.youronly.one/faithfulathlete/"
#  avatar = "https://rsc.youronly.one/img/y/Faithful_Athlete-logo-02-1500x.webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "Love and Relationship / 愛と関係 / 사랑과 관계"
#  url = "https://im.youronly.one/love/"
#  avatar = "https://rsc.youronly.one/img/y/Love_and_Relationship.webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "Snoworld / 雪の世界 / 스노우 월드"
#  url = "https://im.youronly.one/snoworld/"
#  avatar = "https://rsc.youronly.one/img/y/snoworld-square.webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "techmagus / ハイテク マギ / 테크 마구스"
#  url = "https://im.youronly.one/techmagus/"
#  avatar = "https://rsc.youronly.one/img/y/techmagus-Architetto-Esperiment-chimico.webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "Verses.Space (KWWP)"
#  url = "https://verses.space"
#  avatar = "https://rsc.youronly.one/img/y/KWWP-logo-01-1280wh-transparent.webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "Way of Believers / 信者の道 / 테크 마구스"
#  url = "https://im.youronly.one/way/"
#  avatar = "https://img.youronly.one/works/FlagMenorah-Proto-(CC0).webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "Health Welfareness / 健康福祉 / 건강 복지"
#  url = "https://health.youronly.one"
#  avatar = "https://rsc.youronly.one/img/y/CHANGE_THIS.webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "Wealth Welfareness / 富と福祉 / 부 복지"
#  url = "https://wealth.youronly.one"
#  avatar = "https://rsc.youronly.one/img/y/CHANGE_THIS.webp"
#  #rel = "noopener external nofollow"

#[[authors]]
#  person = "yuki"
#  #id = ""
#  #name = "Yūgen Bard / 幽玄吟遊詩人 / 幽 玄 음유 시인"
#  url = "https://im.youronly.one/yugenbard/"
#  avatar = "https://rsc.youronly.one/img/y/Yūgen_Bard-logo-01-1500x.webp"
#  #rel = "noopener external nofollow"
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
  height=""
  width=""
  class=""
  style=""
  type=""

  isrepresentativeofpage=false

  src=""
  link=""
  linkrel=""
  thumbnailurl=""

  title=""
  caption=""
  alt=""
  embeddedtextcaption=""
  inlanguage=""

  datecreated=""
  datepublished=""

  objheight=""
  objwidth=""

  infoalign=""

  licensecode=""
  licenseurl=""
  licensename=""

  acquirelicensepage=""
  copyrightnotice=""
  credittext=""

  attribto=""
  attriburl=""
  attribrel=""

  cc0country=""
  cc0countrycode=""
  cc0countryurl=""

  contentloc=""
  contentlocurl=""
  contentlocrel=""
  contentreferencetime=""
>}}

## Music / 音楽 / 음악

## Production / 製作 / 제작

## Verdict / 評決 / 평결

## Other markdown codes
[SOME_LINK](https://example.com)

[POST_TITLE]({{< ref "/FILENAME.md" >}} "TITLE_ATTRIBUTE")

## Official trailer / 公式予告編 / 공식 예고편
{{< video
  height=""
  width=""
  class=""
  style=""
  platform=""

  id=""
  linkrel=""
  isplaylist=false
  isloop=false
  starttime=""
  endtime=""

  title=""
  caption=""
  inlanguage=""

  datecreated=""
  datepublished=""

  director=""
  musicby=""

  objframesize=""
  objquality=""
  objheight=""
  objwidth=""

  infoalign=""

  licensecode=""
  licenseurl=""
  licensename=""

  acquirelicensepage=""
  copyrightnotice=""
  credittext=""

  attribto=""
  attriburl=""
  attribrel=""

  cc0country=""
  cc0countrycode=""
  cc0countryurl=""

  contentloc=""
  contentlocurl=""
  contentlocrel=""
  contentreferencetime=""
>}}

## OST
{{< music src="https://open.spotify.com/embed/playlist/CHANGE_THIS" >}}

## Attribution, Usage, &amp; Leave your links
Simply follow the attribution shown underneath each photo, or whichever is acceptable within the bounds of CC-BY-SA 4.0 International license. In addition to that, I would also appreciate if you leave your links below or in Instagram, who knows, I might mention your site (and usage) one day.

-------

{{< image
  type="imagecoverattrib"

  isrepresentativeofpage=false

  link=""
  linkrel=""
  thumbnailurl=""

  title=""
  caption=""
  alt=""
  embeddedtextcaption=""
  inlanguage=""

  licensecode=""
  licenseurl=""
  licensename=""

  acquirelicensepage=""
  copyrightnotice=""
  credittext=""

  attribto=""
  attriburl=""
  attribrel=""

  cc0country=""
  cc0countrycode=""
  cc0countryurl=""
>}}

-------

注意：Google翻訳
고시 : Google 번역
