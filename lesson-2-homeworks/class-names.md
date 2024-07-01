### Words Frequently Used in CSS Classes

## Images

`image`, `img`, `picture`, `pic` — image

`icon` — icon

`logo` — logo

`userpic`, `avatar` — userpic, small user image

`thumbnail`, `thumb` — thumbnail, reduced image

## Text

`title`, `subject`, `heading`, `headline`, `caption` — title

`subtitle` — subtitle

`slogan` — slogan

`lead`, `tagline` — lead paragraph in text

`text` — text content

`desc` — description, variant of text content

`excerpt` — text excerpt, usually used before "Read more..." link

`quote`, `blockquote` — quote

`snippet` — code example

`link` — link

`copyright`, `copy` — copyright

## Lists

`list`, `items` — list

`item` — list item

## Blocks

`page` — root element of the page

`header` — header (of the page or element)

`footer` — footer (of the page or element)

`section` — content section (one of several)

`main`, `body` — main part (of the page or element)

`content` — content of the element

`sidebar` — sidebar (of the page or element)

`aside` — block with additional information

`widget` — widget, for example, in the sidebar

## Layout

`wrapper`, `wrap` — wrapper, usually outer

`inner` — inner wrapper

`container`, `holder`, `box` — container

`grid` — layout (of the page or element) in a grid format (usually contains `row` and `col`)

`row` — row container

`col`, `column` — column container

## Controls

`button`, `btn` — button, for example, for form submission

`control` — control element, such as "Next/Previous" arrows in a photo gallery, slider control buttons

`dropdown` — dropdown list

## Media Queries

`phone`, `mobile` — mobile devices

`phablet` — large screen phones (6-7")

`tablet` — tablets

`notebook`, `laptop` — laptops

`desktop` — desktop computers

## Sizes

`tiny`, `xs` — tiny, extra small

`small`, `sm` — small

`medium`, `base` — medium

`big`, `large`, `lg` — large

`huge`, `xl` — huge

`narrow` — narrow

`wide` — wide

## Miscellaneous

`search` — search

`socials` — block of social media icons

`advertisement`, `adv`, `commercial`, `promo` — advertisement block (blocked by Adblock, not recommended for internal advertisement blocks)

`features`, `benefits` — list of main features of a product or service

`slider`, `carousel` — slider, interactive element with content scrolling

`pagination` — pagination

`user`, `author` — user, author of a post or comment

`meta` — block with additional information, such as tags and dates in a post

`cart`, `basket` — cart

`breadcrumbs` — breadcrumb navigation

`more`, `all` — link to full information

`modal` — modal (dialog) window

`popup` — popup window

`tooltip`, `tip` — tooltip

`preview` — preview, excerpt, for example, of news or a post, usually consists of a title, description, and image, with a link to the full version

`overlay` — overlay layer, for example, for image darkening or creating modal windows

## States

`active`, `current` — active element, such as the current menu item

`visible` — visible element

`hidden` — hidden element

`error` — error status

`warning` — warning status

`success` — success status

`pending` — pending state, for example, before changing the status to error or success

## Examples of Usage

### Simple List

```html
<ul class="list">
  <li class="item">First</li>
  <li class="item">Second</li>
  <li class="item">Third</li>
</ul>
```

### User Picture (Userpic)

```html
<div class="user">
  <img class="user-img" src="userpic.png" alt="Dormidont Petrovich">
  <a class="user-link" href="#">Dormidont Petrovich</a>
</div>
```

### Gallery

```html
<div class="gallery">
  <ul class="gallery-list">
    <li class="gallery-item">
      <img class="gallery-img" src="flowers.jpg" alt="Blooming like never before">
    </li>
    <li class="gallery-item">
      <img class="gallery-img" src="trees.jpg" alt="Park 'Three Pines'">
    </li>
  </ul>
</div>
```

### Navigation

```html
<nav class="nav">
  <a class="nav-link nav-link-active">Home</a>
  <a class="nav-link" href="#">Secondary</a>
  <a class="nav-link" href="#">Third to Last</a>
</nav>
```

```html
<nav class="nav">
  <ul class="nav-list">
    <li class="nav-item nav-item-current">
      <a class="nav-link">Home</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#">Articles</a>
    </li>
  </ul>
</nav>
```

### Widget in Sidebar

```html
<div class="widget">
  <h4 class="widget-title">Growing Jelly</h4>

  <div class="widget-_content">
    <p>To grow a sociable, friendly jelly,
    we will need a roll of foam rubber, two kilograms of sugar,
    three eggs, and half a teacup of acetone.</p>

    <a class="widget-link" href="#">Don't read further...</a>
  </div>
</div>
```

### News Block

```html
<div class="news">
    <h3 class="news-title">Yesterday's News</h3>

    <ul class="news-list">
        <li class="news-item item-news">
            <h4 class="item-news-title">Speed Skating Competition Among Vobla</h4>
            <div class="item-news-text">
              <p>The team of kilkas from Petrozavodsk won</p>

              <a href="#" class="item-new-link">Read more</a>
            </div>
        </li>

        <li class="news-item item-news">
            <h4 class="item-news-title">Scientists Clarified the Role of a File in Nail Care</h4>
            <div class="item-news-text">
              <p>British scientists highly appreciated the contribution
                of the file in growing one-and-a-half-meter nails.</p>

              <a href="#" class="item-news-link">Don't read further</a>
            </div>
        </li>
    </ul>
</div>
```

### Simple Blog Post

```html
<article class="article">
  <h3 class="article-title">Finding Chakras in a Bunch of Parsley</h3>
  <time class="article-datetime">May 32, 10:87</time>

  <div class="article-author author-article">
    <img class="author-article-img" src="userpic.png" alt="Kleshnya Andreevna">
    <a class="author-article-link" href="#">Kleshnya Andreevna Dolgorukaya</a>
    <div class="author-article-desc">Our chakra expert</div>
  </div>

  <div class="article-content">
    Go to the market and buy a bunch of parsley from the old ladies, about 100 grams.
    Sort it out well, clean off the bugs and caterpillars. Give the bugs to the cat to play with,
    and put the caterpillars in a pot with cacti, let one be John,
    the other Billy, and now you have the Wild West in your pot. Return
    to the bunch of parsley. Look at it gently and scratch
    it behind the ear, you can scratch yourself or the cat. Tie it with a satin ribbon,
    be sure to make a bow. Congratulations! Now you have a fully
    domesticated bunch of parsley that will happily follow you
    around and plant its seeds in your slippers.
  </div>
</article>
```

### Complex Blog Post

```html
<article class="entry">
  <header class="entry-header">
    <h3 class="entry-title title-entry">
      <a class="title-entry-link" href="#">Rubber Duckies as a Way

 of Self-Discovery</a>
    </h3>

    <time class="entry-datetime">May 32, 10:87</time>
  </header>

  <div class="entry-author author-entry">
    <img class="author-entry-img" src="userpic.png" alt="Vasilisa Sergeevich">

    <a class="author-entry-link" href="#">Vasilisa Sergeevich</a>
  </div>

  <div class="entry-content">
    Take a box with fifty rubber duckies from the attic,
    left over from the New Year's celebration. From the duckies
    and burning candles, lay out a pentagram on the floor of the room.
    Sit in the middle in a lotus position, take
    a German-Brazilian dictionary in each hand, clear your throat, take a deep
    breath and loudly and confidently,
    with full commitment, say "Quack!"
  </div>

  <div class="entry-tags tags-entry">
    <h4 class="tags-entry-title">Tags</h4>

    <ul class="tags-entry-list">
      <li class="tags-entry-item">
        <a class="tags-entry-link" href="#">DIY circle dance</a>
      </li>
      <li class="tags-entry-item">
        <a class="tags-entry-link" href="#">porcelain slippers</a>
      </li>
      <li class="tags-entry-item">
        <a class="tags-entry-link" href="#">shoe polish in cooking</a>
      </li>
    </ul>
  </div>

  <div class="entry-actions actions-entry">
    <ul class="actions-entry-list">
      <li class="actions-entry-item actions-entry-item-read">
        <a class="actions-entry-link" href="#">238 answers</a>
      </li>
      <li class="actions-entry-item actions-entry-item-write">
        <a class="actions-entry-link" href="#">Write to Sportloto</a>
      </li>
      <li class="actions-entry-item actions-entry-item-share">
        <a class="actions-entry-link" href="#">Share</a>
      </li>
    </ul>
  </div>
</article>
```