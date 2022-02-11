## Cards Project

#### Setup

- create folder (10-cards)
- create index.html, general structure
- give it a title (cards project)
- create css file (main.css)
- link to css file in html (head element)

#### Assets

- get two images from pexels site
- font awesome cdn link (v6)

#### HTML

- section with class "blogs"
  - div with class "section-title"
    - h2 with text "latest blogs"
  - div with class "blogs-center"
    - article with class "blog"
      - img
      - div with class "blog-content"
        - span with text and any icon
        - h3
        - p (lorem15)
        - a (href="#") "read more"
    - repeat

#### Reset

- reset (remove default styles)

#### Variables

:root {
--primary: #645cff;
--primary-dark: #3c3799;
--grey-light: #f1f5f9;
--grey: #64748b;
--grey-dark: #0f172a;
--fluid-width: 90vw;
--max-width: 1170px;
--black: #222;
--white: #fff;
--letter-spacing: 2px;
--border-radius: 0.15rem;
--shadow-light: 0 5px 15px rgba(0, 0, 0, 0.1);
--shadow-dark: 0 5px 15px rgba(0, 0, 0, 0.2);
--transition: 0.3s ease-in-out all;
}

#### Styles

- body(fonts,line-height,background,color)
- .blogs (padding)
- .section-title(text-align,text-transform,letter-spacing,margin-bottom)

- .blogs-center (width,max-width,margin)
- .blog(background,padding,border-radius,box-shadow,transition,margin-bottom)
- .blog:hover(box-shadow)

- .blog-img (width,display,object-fit,border-radius,margin-bottom)

- .blog-content(padding-bottom)
- .blog-content span (text-transform,color,letter-spacing,font-weight)
- .blog-content h3 (text-transform,letter-spacing,margin)
- .blog-content p(color,margin-bottom)
- .blog-content a(text-transform, color, letter-spacing, font-weight)
