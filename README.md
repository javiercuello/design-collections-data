## Design Collections is a website with curated and updated design resources. For now, it consists only about design tools, books and blogs and magazines. In the near future some other sections will be added.

The goal of the site is not to present lots and lots of resources, but somehow recommended items that are good quality, valuable and meaningful to improve your career as designer, and in the meantime, grow as person too.

**Website:**
[http://collections.design](http://collections.design)

# You can contribute, too
If you think you have any design resource (tools, books) that you think are particularly good and you want to recommend, please contribute to this repository by submitting the information.

Below you will find what information is need for each kind of content.

## Tools
The minimun information you need to gather to submit a design tool recommendation is the following:

- Name: The products name

### Basic information
- Color: The background color that will be displayed behind the icon in the cards
- Description: A short text describing the tool (no longer than 130 characters)
- Image: An icon with transparent background (PNG)
- Website: The product's official website

### Availability
Complete if the product is available for:
- Linux
- macOS
- Web
- Windows

### Features
Complete if the product is capable of:
- Animation: You can animate objects on stage
- Code: You can achieve things by coding
- Design: It has functional design features
- Gestures: You can do a prototype that takes into account gestures (swipe, pinch, etc.)
- Transitions: It allows to set animated transitions from one screen to the other

### Pricing
- If it's free
- If not, what's the price
- If it includes the possibility of trying it withour purchasing
- If yes, then if the trial has any kind of limitation (by projects number, features, time, etc.)

Once you gather all this information, you can then submit a tool.

### Example
```json
  {
    "name": "Adobe XD",
    "basic_info":{
      "color": "#2D001D",
      "description": "Adobe XD is made for designers like you, by designers like us.",
      "image": "../data/tools/img/adobe-xd.png",
      "website": "https://www.adobe.com/products/xd.html"
    },
    "availability":{
      "linux": false,
      "macos": true,
      "web": false,
      "windows": true
    },
    "features":{
      "animation": true,
      "code": false,
      "design": true,
      "gestures": true,
      "transitions": true
    },
    "pricing":{
      "free": true,
      "price": "From $0/mo.",
      "trial": true,
      "time": "project limited"
    }
  },
```

## Books
The minimun information you need to gather to submit a design book recommendation is the following:

- Name: The book's short title (not the full version -- without subtitles)

### Basic information
- Author: If several, sepparated by comma
- Description: A short text describing the book (no longer than 260 characters)
- Image: An image of the book's cover (PNG)
- Website: The product's official website

### Pricing
- If it's free
- If not, what's the price

### Publishing
- Year: Year of publication
- Publisher: Company who published the book (also if it's self-published)

### Categories
The book should belong to one or more of the following categories:
- Accesibility
- Creativity
- Entrepreneurship (but related to design)
- General design
- Not design (but related to design)
- Typography
- Usability
- User Experience (UX)

Once you gather all this information, you can then submit a book.

### Example
```json
  {
    "name": "Articulating Design Decisions",
    "basic_info":{
      "author": "Tom Greever",
      "description": "This practical guide focuses on principles, tactics, and actionable methods for presenting your designs. Whether you design UX, websites, or products, you’ll learn how to win over anyone who has influence over the project—with the goal of creating the best experience for the end user.",
      "image": "../data/books/img/articulating-design-decisions.png",
      "website": "http://shop.oreilly.com/product/0636920037422.do"
    },
    "pricing":{
      "free": false,
      "price": "From $23.00"
    },
    "publishing":{
      "year": "2015",
      "publisher": "O'Reilly Media"
    },
    "categories":{
      "accesibility": false,
      "creativity": false,
      "entrepreneurship": false,
      "general": true,
      "notdesign": false,
      "typography": false,
      "usability": false,
      "ux": true
    }
  },
```

## Blogs (and magazines)
The minimun information you need to gather to submit a design book recommendation is the following:

- Name: The blog or magazine name

### Basic information
- Description: A short text describing the book (no longer than 260 characters)
- Image: An image or logo (PNG)
- Website: The product's official website

### Type
- If it's a blog
- If it's a magazine

### Categories
It should belong to one or more of the following categories:
- Digital
- Branding
- General design
- Graphic design
- Illustration
- Not design (but related to design)
- Typography

Once you gather all this information, you can then submit a blog or magazine.

### Example
```json
  {
    "name": "Eye on Design",
    "basic_info":{
      "description": "AIGA Eye on Design covers the world’s most exciting designers—and the issues they care about. We’re published by AIGA, the professional association for design, the oldest and largest not-for-profit design organization in the United States.",
      "image": "../data/blogs/img/eye-on-design.png",
      "color": "#ff8c8c",
      "website": "https://eyeondesign.aiga.org"
    },
    "type":{
      "blog": true,
      "magazine": false
    },
    "categories":{
      "digital": true,
      "branding": true,
      "general": true,
      "graphicdesign": true,
      "illustration": true,
      "notdesign": false,
      "typography": true
    }
  },
```

# Contact and more information
If you have questions or need to know anything, feel free to submit your message via our contact form:
https://designcollections.typeform.com/to/HWyw7P
