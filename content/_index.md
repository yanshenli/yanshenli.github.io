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
      css_class: fullscreen



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
                  <img src="image/AcadTrack.png" 
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
---