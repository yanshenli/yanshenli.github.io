---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: markdown
    content:         
      # title:  流体物理与界面科学实验室
      # subtitle: 'PFIS Lab'
      text: |-
              <!-- Text with background box container -->
              <div style="position: center; 
                        display: inline-block;
                        margin: 10px;                    /* Control outer spacing */
                        --text-color:rgb(255, 255, 255);           /* Custom text color */
                        --bg-color: rgba(187, 187, 187, 0); /* Background color/transparency */
                        --bg-width: 90%;               /* Background width */
                        --bg-height: 75%;               /* Background height */
                        --text-size: 1.7rem;             /* Font size control */
                        --x-position: 20px;               /* Horizontal adjustment */
                        --y-position: 220px;             /* Vertical adjustment */">
                
                <!-- Background rectangle -->
                <div style="position: absolute;
                          top: 50%;
                          left: 50%;
                          width: var(--bg-width);
                          height: var(--bg-height);
                          background: var(--bg-color);
                          transform: translate(-50%, -50%);
                          z-index: 0;
                          border-radius: 0px;">          <!-- Optional rounded corners -->
                </div>

                <!-- Text content -->
                <div style="position: relative;
                          z-index: 1;
                          color: var(--text-color);
                          font-size: var(--text-size);
                          padding: 1.2em;
                          transform: translate(var(--x-position), var(--y-position));
                          font-family:  'Gill Sans', 'Inter var','Open Sans', 'Arial Nova','Roboto', 'Trebuchet MS','Century Gothic', BlinkMacSystemFont, 'Segoe UI', sans-serif;">
                  "God made the bulk; surfaces were invented by the devil." &nbsp –– Wolfgang Pauli  <br> <br>
                  Here, we study them both.
                </div>
              </div>
            
    design:
      columns: '1'
      background:
        image: 
          # Name of image in `assets/media/`.
          filename: HomepageBanner.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 1
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: false
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: bottom
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: false
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['29vh', '0', '29vh', '0']
      # css_class: fullscreen



  - block: markdown
    content:
      text: |-
            <!-- Horizontal container using flexbox for side-by-side layout -->
            <div style="display: flex;                   /* Enable flexbox layout */
                      align-items: center;            /* Vertical alignment (center) */
                      gap: 0px;                      /* Space between image and text */
                      padding: 0px 0;                /* Vertical padding */" >

            <!-- Image Container -->
            <div style="flex: 0 0 auto;               /* Don't grow or shrink */
                        width: 45%;                 /* Image container width */
                        padding-top: 0px;            /* Top padding for image */
                        padding-left: 0px;
                        padding-right: 0px;
                        padding-bottom: 0px;         /* Bottom padding for image */ ">
                <img src="image/LOGO.png"               /* Replace with your image path */
                      alt="Logo"
                      align="left"
                      style="width: 100%;               /* Image fills container width */
                            height: auto;              /* Maintain aspect ratio */
                            object-fit: cover;         /* Image cropping mode */">
            </div>

            <!-- Text Container -->
            <div style="flex: 1;                     /* Take remaining space */
                        padding-top: 00px;            /* Top padding for image */
                        padding-left: 30px;           /* Text container padding */
                        padding-right: 0px;
                        padding-bottom: 30px;
                        font-size: 22px;             /* Base text size */
                        # font-family: 'Helvetica Neue', 'Chalkboard', 'Gill Sans', 'Helvetica', 'times', '手札体-简';
                        line-height: 1.5;            /* Text line spacing */
                        text-align: left;            /* Text alignment */"> 
                <h2 style="font-size: 32px;           /* Heading size */
                        margin-bottom: 5px;         /* Space below heading */ 
                        text-align: center; 
                        font-family: 'Helvetica Neue';
                        color: black;            <!-- Title color -->">
                        <strong style="font-family: 'shouzhati', 'Xingkai', SimSun">流体与界面科学实验室</strong>
                </h2>
                <p style="color: black;
                        text-align: center;           <!-- Inherits from parent color -->
                        font-family: 'Chalkboard', sans-serif;">          
                  <en style="font-family: 'Hannotate SC', 'Chalkboard', sans-serif">Fluids and Interface Science (FIS) Lab</en>
                </p> 
              <p style="color: black;">          <!-- Inherits from parent color -->

            本实验室主要研究**流体**以及涉及**界面**的**力学**问题。包括*多相多组分流体，界面流动，固液浸润，液滴*，详情请见[研究方向](/research)。

            课题组长：[李延深](/author/李延深)，副教授、博导，入选**国家引才计划青年项目**(2021)、中科院人才计划项目、小米青年学者项目，中国科学院大学领雁金奖获得者。

            **清华大学**学士、博士。博士师从郑泉水院士，深受其创新教育理念的熏陶。荷兰特文特大学博士后，合作导师为 <em style="font-family: 'Gill Sans', times new roman">Detlef Lohse</em> 教授（荷兰、德国、美国多院院士）。

            在 <em style="font-family: 'Chalkboard', times new roman">PNAS, PRL, JFM</em> 等**流体力学**、**物理学**领域的顶级期刊发表多篇论文，成果得到 <em style="font-family: 'Chalkboard', times new roman">Nature、Physics、Chemistry World、Europhysics News, FYFD</em> 等知名学术媒体高亮报道。详情请见[论文发表](/publication/)。
              </p> 
            </div>
            </div> 

    design:
      background:
        color: rgb(255, 255, 255)
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['100px', '0', '0px', '0px']

  - block: markdown
    content:         
      text: |-
              <p align="center">
                  <img src="image/AcadTrack7.png" 
                      width="95%" 
                      style="display: inline-block; border: 0">
              </p>

    design:
      background:
        color: rgb(255, 255, 255)
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['40px', '0', '60px', '100px']

  - block: hero
    content:
      title:
      cta:
        label: 查看团队成员
        url: "./people/"
        # icon_pack: fas
        # icon: download
      # cta:
      #   label: 我看看
      #   url: "./people/"
      # Optionally, add an alternative CTA link
      cta_alt:
        label: 加入我们
        url: "./recruit/"
      subtitle:
      # text: |
      #    {{% cta cta_link="./people/" cta_text="查看团队成员 →" %}}  &nbsp {{% cta cta_link="./recruit/" cta_text="加入我们 →" %}}
    design:
      columns: '1'
      background:
        color: rgb(255, 255, 255)
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '00px', '40px', '40%']


  - block: markdown
    content:         
      # title:  研究亮点
      # subtitle: 'FIS Lab'
      text: |-
              
              <a href="../research/">
              <h1 style="color: white;" align="center">           
                  研究亮点
              </h1>
              </a>
            
    design:
      background:
        color: '#555'
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '00px', '0']
    
  - block: slider
    id: highlight
    content:            
      slides:
      - title: 
        content: |-
              <p align="center">
                <a href="https://doi.org/10.1038/d41586-019-01302-7" target="_blank" style="display: inline-block">
                  <img src="/image/homepageimage/NatureHighlight.jpg" 
                      width="34%" 
                      style="display: inline-block; border: 0">
                </a>
              </p>
        align: center
        background:
          color: '#555'
      - title: 
        content: |-
              <p align="center">
                <a href="https://physics.aps.org/articles/v12/s45" target="_blank" style="display: inline-block">
                  <img src="/image/homepageimage/PhysicsHighlight.jpg" 
                      width="39%" 
                      style="display: block; border: 0">
                </a>
              </p>
        align: center
        background:
          color: '#555'
      # - title: 
      #   content: |-
      #         <p align="center">
      #           <a href="https://doi.org/10.1051/epn/2017505" target="_blank" style="display: inline-block">
      #             <img src="/image/homepageimage/EurophysicsNews.jpg" 
      #                 width="33%" 
      #                 style="display: inline; border: 0">
      #           </a>
      #         </p>
      #               <p style="color: white;" align="center">  
      #     # <a href="../research/monostable/">         
      #     # To Research
      #     # </a>
      #     # </p>
      #   align: center
      #   background:
      #     color: '#555'
      - title: 
        content: |-
            <!-- Inline image with text flow -->
            <span style="display: inline-block;           /* Enables text wrapping */
                        vertical-align: middle;          /* Aligns with text baseline */
                        margin-right: ;              /* Space after image */
                        line-height: normal;           /* Prevents spacing issues */">
              <a href="https://doi.org/10.1051/epn/2017505" 
                style="display: inline-block;            /* Maintains image dimensions */
                        border: none;                     /* Remove link border */">
                <img src="/image/homepageimage/EurophysicsNews.jpg"
                    style="display: inline-block;        /* Inline layout */
                            width: 22vw;                 /* Fixed width (easier for inline) */
                            height: auto; 
                            vertical-align: middle;       /* Image/text alignment */
                            margin: 0;                  /* Remove default image margins">
              </a>
            </span>
              <!--[见研究方向](../research/monostable)  -->

            <!-- Inline image and text container with padding control 
            <span style="display: inline-block;
                        vertical-align: middle;
                        margin-right: 10px;
                        line-height: normal;
                        padding-right: 30px;            /* Right padding control */
                        box-sizing: border-box;       /* Include padding in width calc */">
              <a href="YOUR-LINK-URL" 
                style="display: inline-block;
                        border: none;
                        padding: 5px;                   /* Padding around image link */">
                <img src="/image/homepageimage/NatureHighlight2.jpg"
                    style="display: inline-block;
                            width: 400px;
                            height: auto;
                            vertical-align: middle;
                            margin: 0;
                            padding: 2px;              /* Image internal padding */"> 
              </a>
            </span>
            <div style="padding-right: 15%;              /* Text right-screen padding */
                        display: inline;               /* Maintain inline flow */">
            Your text here will wrap with the image. Add more content...
            </div>-->

        align: center
        background:
          color: '#555'
        # link:

        #   url: ../contact/
      
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '70vh'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  # - block: markdown
  #   id: 
  #   content:
  #     title: 画廊
  #     subtitle:
  #     image:
  #       filename: 
  #     text: |
  #           {{< gallery album="" resize_options="800x800">}}

  #     gallery_item:
  #       - album: "/assets/media/albums/gallery/"
  #         image: coders.jpg
  #         caption: Write your image 1 caption here
  #       - album: "/assets/media/albums/gallery/"
  #         image: contact.jpg
  #         caption: Write your image 2 caption here
  #       - album: "/assets/media/albums/gallery/"
  #         image: icon.png
  #         caption: CAS
  #       - album: "/assets/media/albums/gallery/"
  #         image: ucasnight.jpeg
  #         caption: ucas
  #       - album: "/assets/media/albums/gallery/"
  #         image: welcome.jpg
  #         caption: Write your image 1 caption here

  # - block: hero
  #   id: hero
  #   content:
  #     title: |
  #           流体物理与界面科学实验室
  #     image:
  #       filename: UCASnightMaingate.jpeg
  #     text: |
  #       <br>
  #        流体物理与界面科学实验室主要研究舰船动力系统、电子设备 & 数据中心等的高效换热；芯片、高性能合金制造等国家亟需的重要领域；以及流体相关的基础科学问题，包括固液浸润、多相多组分流体，以及界面流动等。
  
  # - block: collection
  #   id: news
  #   content:
  #     title: 新闻
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       folders:
  #         - x-post
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     # order: desc
  #     page_type: post
  #   design:
  #     view: showcase
  #     ## view can be: card, showcase, compact, stream
  #     columns: '1'
  #     # For the Showcase view, do you want to flip alternate rows?
  #     flip_alt_rows: false

  # - block: markdown
  #   content:         
  #     # title:  流体物理与界面科学实验室
  #     # subtitle: 'PFIS Lab'
  #     image:
  #       filename: icon.png
  #     text: |
  #           # 流体物理与界面科学实验室

  #           ## PFIS Lab

  #           流体物理与界面科学实验室主要研究舰船动力系统、电子设备 & 数据中心等的高效换热；芯片、高性能合金制造等国家亟需的重要领域；以及流体相关的基础科学问题，包括固液浸润、多相多组分流体，以及界面流动等。
  #           {style="color: red"}

  #           ![xxx](/assets/media/UCASnightMaingate.jpeg)
  #           [UCAS](https://www.ucas.edu.cn)

  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: right
  #         # could be cover, contain and 
  #         size: cover
  #         text_color_light: false
  #     spacing:
  #     # Customize the section spacing. Order is top, right, bottom, left.
  #       padding: ['20px', '0', '20px', '0']
  #     # css_class: fullscreen

  # - block: markdown
  #   content:

  # - block: collection
  #   content:
  #     title: Posts test
  #     text: "xxx"
  #     # count: 5
  #     filters:
  #       folders:
  #         - x-post
  #       # publication_type: 'article'
  #   design:
  #     view: showcase
  #     fill_image: true
  #     columns: '1'
  #     # For the Showcase view, do you want to flip alternate rows?
  #     flip_alt_rows: false
    

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="查看团队成员 →" %}}
  #   design:
  #     columns: '1'

  # - block: markdown
  #   content:
  #     text: |
  #           ## 教育与工作经历

  #           - 2021.12 – 至今                  中国科学院大学，副教授

  #           - 2017.09 – 2021.10              荷兰特文特大学，博士后

  #           - 2011.09 – 2017.07              清华大学，博士
            
  #           - 2007.09 – 2011.07              清华大学，学士

  #           ## 奖励与荣誉

  #           - 2024      国科大青教赛三等奖
  #           - 2023      小米青年学者
  #           - 2023      中国科学院大学领雁金奖（引航奖）
  #           - 2021      国家级青年人才项目

  #           ## 教授课程
  #           {style="color: red"}

  #           界面流动与润湿（研究生）；2023夏季学期、2024春季学期、2025春季学期
            
  #           Red colored text 
  #           {style="color: red"}

  #           {{< math >}}
  #           $$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
  #           1-p_{0}^{*} & \text{if }k=0.\end{cases}$$
  #           {{< /math >}}

  #           {{% callout note %}}
  #           A Markdown callout is useful for displaying notices, hints, or definitions to your readers.
  #           {{% /callout %}}
          





   


  # - block: experience
  #   content:
  #     title: 教育与工作经历
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many experience `items` below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: 副教授，博导
  #         company: 中国科学院大学
  #         company_url: ''
  #         company_logo: 
  #         location: California
  #         date_start: '2021-12-13'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:

  #             * Analysing
  #             * Modelling
  #             * Deploying
  #       - title: Professor of Semiconductor Physics
  #         company: University X
  #         company_url: ''
  #         company_logo: 
  #         location: California
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'


  # - block: hero
  #   content:
  #     title: Your Hero Title
  #     image:
  #       # Reference an image in your `assets/media/` folder
  #       filename: /image/AcadTrack.png
  #     # Add your Call-To-Action (CTA) button and optional icon
  #     cta:
  #       label: Get Started
  #       url: https://wowchemy.com/templates/
  #       icon_pack: fas
  #       icon: download
  #     # Optionally, add an alternative CTA link
  #     cta_alt:
  #       label: Ask a question
  #       url: https://discord.gg/z8wNYzb
  #     # Optionally, add a note under the Call-To-Action button
  #     cta_note:
  #       label: >-
  #         <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>          
  #     # Add your Hero text here
  #     text: |-
  #       **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

  #       **Easily build anything with blocks - no-code required!**

  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

  #       <!--Custom spacing-->
  #       <div class="mb-3"></div>
  #       <!--GitHub Button JS-->
  #       <script async defer src="https://buttons.github.io/buttons.js"></script>        
  #   design:
  #     # Choose an optional background color, gradient, image, or video
  #     background:
  #       gradient_end: '#1976d2'
  #       gradient_start: '#004ba0'
  #       text_color_light: true


# gallery_item:
# - album: "/assets/media/albums/gallery/"
#   image: coders.jpg
#   caption: Write your image 1 caption here
# - album: "/assets/media/albums/gallery/"
#   image: contact.jpg
#   caption: Write your image 2 caption here
# - album: "/assets/media/albums/gallery/"
#   image: icon.png
#   caption: CAS
# - album: "/assets/media/albums/gallery/"
#   image: ucasnight.jpeg
#   caption: ucas
# - album: "/assets/media/albums/gallery/"
#   image: welcome.jpg
#   caption: Write your image 1 caption here


# banner:
#   image: 'icon1.jpg'
#   caption: 'Image credit: [**Geo**](https://github.com/gcushen/)'
---


<!-- Horizontal container using flexbox for side-by-side layout
<div style="display: flex;                   /* Enable flexbox layout */
          align-items: center;            /* Vertical alignment (center) */
          gap: 10px;                      /* Space between image and text */
          padding: 20px 0;                /* Vertical padding */" >

<!-- Image Container -->
<!-- <div style="flex: 0 0 auto;               /* Don't grow or shrink */
            width: 45%;                 /* Image container width */
            padding-top: 20px;            /* Top padding for image */
            padding-left: 0px;
            padding-right: 0px;
            padding-bottom: 30px;         /* Bottom padding for image */ ">
    <img src="image/LOGOv3.png"               /* Replace with your image path */
          alt="Logo"
          align="right"
          style="width: 50%;               /* Image fills container width */
                height: auto;              /* Maintain aspect ratio */
                object-fit: cover;         /* Image cropping mode */">
</div> -->

<!-- Text Container 
<div style="flex: 1;                     /* Take remaining space */
            padding-top: 00px;            /* Top padding for image */
            padding-left: 30px;           /* Text container padding */
            padding-right: 0px;
            padding-bottom: 30px;
            font-size: 24px;             /* Base text size */
            line-height: 1.5;            /* Text line spacing */
            text-align: left;            /* Text alignment */  "> 
    <h2 style="font-size: 32px;           /* Heading size */
            margin-bottom: 5px;         /* Space below heading */ 
            color: white;            <!-- Title color -->">
      <!-- 流体与界面科学实验室
    </h2>
    <p style="color: white;">          <!-- Inherits from parent color -->
      Fluids and Interface Science (FIS) Lab 
    </p> -->
</div>
</div> -->