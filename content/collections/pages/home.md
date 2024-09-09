---
id: home
blueprint: pages
title: Home
template: home
author: cbc10183-d3d3-44b1-bec1-15f2c88b92d3
updated_by: cbc10183-d3d3-44b1-bec1-15f2c88b92d3
updated_at: 1725891438
seo_title: iPersonal
meta_keywords: 'keywords, keys, tags'
meta_description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis laboriosam repudiandae'
og_title: iPersonal
og_description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis laboriosam repudiandae'
og_image: images/designer-(2).jpeg
twitter_card_type: summary
twitter_site: '@yoursite'
og_site_name: '@revolve314'
content:
  -
    type: set
    attrs:
      id: m0ulv47k
      values:
        type: home_hero
        logo_text: i.Personal
        logo_title: i.Personal
        title_1: "👋 Hello I'm Manup"
        title_2: 'Statamic Magician Based in INDIA'
        image: images/designer.jpeg
        heading: 'Senior Statamic Web Developer & CMS Specialist'
        description: "Expert Statamic Web Developer & CMS Specialist crafting fast, secure, and scalable websites. Proficient in building custom themes, templates, and addons. Passionate about creating engaging digital experiences with Statamic's flexible and user-friendly CMS. Let's bring your online vision to life with tailored Statamic solutions."
        address:
          -
            id: m0ulva2q
            text: 'Trivandrum, Kerala, India'
            icon: 'fas fa-map-marker-alt'
          -
            id: m0ulvawb
            text: manup.rav@gmail.com
            icon: 'fas fa-envelope '
          -
            id: m0ulvc7j
            text: 'http://www.revolve314.com'
            icon: 'fab fa-firefox-browser'
          -
            id: m0ulve2e
            text: '+9189072789865'
            icon: 'fa fa-phone-alt'
        social_links:
          -
            id: m0ulvfaj
            icon: fa-facebook-f
            url: 'https://www.facebook.com/profile.php?id=61564218518984'
          -
            id: m0ulvfz8
            icon: fa-youtube
            url: 'https://www.youtube.com/@statamiccmsrevolve3148'
          -
            id: m0ulvghu
            icon: fa-twitter
            url: 'https://x.com/314_digital'
          -
            id: m0ulvh54
            icon: fa-linkedin-in
            url: 'https://www.linkedin.com/company/recolve-314-digital'
        edit_template: true
        custom_template: |-
          <!-- Header Start -->  
                  <div class="container-fluid" id="ipersonalHome">
                      <div class="container">
                          <div class="row g-0">
                              <div class="col-12 col-lg-3">
                                  <div class="header-content bg-dark h-100 pt-6 pe-6 pb-6">
                                      <a href="/" title="{{logo_title}}" class="navbar-brand d-inline-flex pb-5 wow fadeInUp" data-wow-delay="0.1s">
                                          <h1 class="display-6 text-white mb-0">{{logo_text}}</h1>
                                      </a>
                                      <div class="text-start d-flex flex-column justify-content-center wow fadeInUp" data-wow-delay="0.3s">
                                          <p class="text-white sub-title">{{title_1}}</p>
                                          <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                                      </div>
                                  </div>
                              </div>
                              <div class="col-12 col-lg-9">
                                  <div class="header-img d-flex h-100 pt-6 ps-6 pb-6">
                                      <div class="row g-5">
                                          <div class="col-xl-6 wow fadeInUp" data-wow-delay="0.1s">
                                              <div class="bg-light p-4" style="border-radius: 68% 32% 100% 0% / 0% 75% 25% 100%;">
                                                  <img src="{{ glide:image preset="medium" }}" class="img-fluid w-100" style="border-radius: 68% 32% 100% 0% / 0% 75% 25% 100%;" alt="{{title_1}} {{title_2}}">
                                              </div>
                                          </div>
                                          <div class="col-xl-6 wow fadeInUp" data-wow-delay="0.3s">
                                              <h1 class="display-6 mb-4">{{heading}}</h1>
                                              <p class="mb-4">{{description}}</p>
                                              {{address}}
                                              <div class="d-flex align-items-center mb-2">
                                                  <i class="{{icon}} text-primary me-3"></i>
                                                  <p class="text-dark mb-0">{{text}}</p>
                                              </div>
                                             {{/address}}
                                              <div class="d-flex">
                                                  {{social_links}}
                                                  <a class="btn btn-primary btn-sm-square me-3" href="{{url}}" target="_blank"><i class="fab {{icon}} text-white"></i></a>
                                                  {{/social_links}}
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <!-- Header End -->
  -
    type: set
    attrs:
      id: m0ulxjoo
      values:
        type: about_me
        title_1: 'About Me'
        title_2: 'Specialized Statamic Web Developer & CMS Specialist'
        image: images/about.jpeg
        social_links:
          -
            id: m0ulxtcu
            icon: fa-facebook-f
            url: 'https://www.facebook.com/profile.php?id=61564218518984'
          -
            id: m0ulxu0l
            icon: fa-twitter
            url: 'https://x.com/314_digital'
          -
            id: m0ulxuje
            icon: fa-youtube
            url: 'https://www.youtube.com/@statamiccmsrevolve3148'
          -
            id: m0ulxv11
            icon: fa-linkedin-in
            url: 'https://www.linkedin.com/company/recolve-314-digital'
        description: 'Skilled Statamic Web Developer & CMS Specialist delivering high-performance, user-friendly websites with expert theme development and addon integration services.'
        heading: "Hello, I'm Manup, passionate developer from India"
        details:
          -
            id: m0ulyvqt
            title: Address
            data: 'Trivandrum, Kerala, India'
          -
            id: m0ulyysb
            title: Phone
            data: '+918907289865'
          -
            id: m0ulz4yu
            title: Email
            data: manup.rav@gmail.com
          -
            id: m0ulzc2x
            title: Skype
            data: manup.rav
        button_text: 'Download My CV'
        file: files/ratheesh-raveendran.pdf
        edit_template: true
        custom_template: |-
          <!-- About Start -->  
                  <div class="container-fluid" id="ipersonalAbout">
                      <div class="container">
                          <div class="row g-0">
                              <div class="col-12 col-lg-3">
                                  <div class="about-header bg-dark h-100 pt-6 pe-6 pb-6">
                                      <div class="text-start d-flex flex-column justify-content-center wow fadeInUp" data-wow-delay="0.1s">
                                          <p class="text-white sub-title">{{title_1}}</p>
                                          <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                                      </div>
                                  </div>
                              </div>
                              <div class="col-12 col-lg-9">
                                  <div class="about-content h-100 pt-6 ps-6 pb-6">
                                      <div class="row g-5">
                                          <div class="col-xl-5">
                                              <div class="about-img bg-light p-4 wow fadeInUp" data-wow-delay="0.1s">
                                                  <img src="{{glide:image preset="medium"}}" class="img-fluid w-100" alt="{{title_1}} {{title_2}}">
                                                  <div class="sosial-icon">
                                                     {{social_links}}
                                                      <a class="btn btn-primary btn-sm-square mb-3" href="{{url}}" target="_blank"><i class="fab {{icon}} text-white"></i></a>


                                                     {{/social_links}}
                                                  </div>
                                              </div>
                                          </div>
                                          <div class="col-xl-7 wow fadeInUp" data-wow-delay="0.3s">
                                              <h4 class="mb-4">{{heading}}</h4>
                                              <p class="mb-4">{{description}}</p>
                                              <div class="col-8">

                                              {{details}}
                                              <p><strong class="fw-bold text-dark">{{title}} :</strong>{{data}}</p>


                                              {{/details}}


                                          
          </div>

                                              
                                              <a href="{{file}}" target="_blank" class="btn btn-primary py-2 px-4"> <i class="fas fa-download me-2"></i>{{button_text}}</a>
                                          </div>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <!-- About End -->
  -
    type: set
    attrs:
      id: m0upmr7c
      values:
        type: education_experience
        title_1: Education
        title_2: 'My Academic Qualification'
        qualifications:
          -
            id: m0upmt1f
            school_college: Oxford
            year: 2008-2010
            course_name: 'MSC Science'
            description: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corrupti, a quasi velit sint atque non saepe quaerat ducimus, nobis error cupiditate, nisi repudiandae dignissimos magnam? Dicta ab possimus tempora nobis.'
            type: new_set
            enabled: true
          -
            id: m0upmut0
            school_college: Oxford
            year: 2008-2010
            course_name: 'MSC Science'
            description: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corrupti, a quasi velit sint atque non saepe quaerat ducimus, nobis error cupiditate, nisi repudiandae dignissimos magnam? Dicta ab possimus tempora nobis.'
            type: new_set
            enabled: true
          -
            id: m0upmw4q
            school_college: Oxford
            year: 2008-2010
            course_name: 'MSC Science'
            description: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corrupti, a quasi velit sint atque non saepe quaerat ducimus, nobis error cupiditate, nisi repudiandae dignissimos magnam? Dicta ab possimus tempora nobis.'
            type: new_set
            enabled: true
        edit_template: false
        custom_template: |-
          <!-- Education Start -->
                  <div class="container-fluid">
                      <div class="container">
                          <div class="row g-0">
                              <div class="col-lg-3">
                                  <div class="education-header bg-dark h-100 pt-6 pe-6 pb-6">
                                      <div class="text-start d-flex flex-column justify-content-center wow fadeInUp" data-wow-delay="0.1s">
                                          <p class="text-white sub-title">{{title_1}}</p>
                                          <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                                      </div>
                                  </div>
                              </div>
                              <div class="col-lg-9">
                                  <div class="education-content h-100 pt-6 ps-6 pb-6">
                                      <div class="row g-4">
                                          {{qualifications}}
                                          <div class="col-12">
                                              <div class="education-item rounded p-4 h-100 wow fadeInUp" data-wow-delay="0.1s">
                                                  <div class="d-flex align-items-center mb-3">
                                                      <p class="fs-5 mb-0 me-4">{{school_college}}</p>
                                                      <div>
                                                          <span class="fa fa-calendar me-1"></span> {{year}}
                                                      </div>
                                                  </div>
                                                  <h4 class="mb-3">{{course_name}}</h4>
                                                  <p class="mb-0">{{description}}</p>
                                              </div>
                                          </div>
                                          {{/qualifications}}
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <!-- Education End -->
  -
    type: set
    attrs:
      id: m0upq70o
      values:
        type: education_experience
        title_1: Experience
        title_2: 'My real work experience'
        qualifications:
          -
            id: m0upnats
            school_college: 'Revolve 314 Digital'
            year: 2008-2010
            course_name: 'Senior Developer'
            description: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corrupti, a quasi velit sint atque non saepe quaerat ducimus, nobis error cupiditate, nisi repudiandae dignissimos magnam? Dicta ab possimus tempora nobis.'
            type: new_set
            enabled: true
          -
            id: m0upnlxn
            school_college: 'ABC Pvt Ltd'
            year: 2008-2010
            course_name: 'Project Manager'
            description: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corrupti, a quasi velit sint atque non saepe quaerat ducimus, nobis error cupiditate, nisi repudiandae dignissimos magnam? Dicta ab possimus tempora nobis.'
            type: new_set
            enabled: true
          -
            id: m0upntzn
            school_college: 'Quilon Limited'
            year: 2008-2010
            course_name: 'Junior Developer'
            description: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corrupti, a quasi velit sint atque non saepe quaerat ducimus, nobis error cupiditate, nisi repudiandae dignissimos magnam? Dicta ab possimus tempora nobis.'
            type: new_set
            enabled: true
        edit_template: true
        custom_template: |-
          <!-- Education Start --> 
                  <div class="container-fluid">
                      <div class="container">
                          <div class="row g-0">
                              <div class="col-lg-3">
                                  <div class="education-header bg-dark h-100 pt-6 pe-6 pb-6">
                                      <div class="text-start d-flex flex-column justify-content-center wow fadeInUp" data-wow-delay="0.1s">
                                          <p class="text-white sub-title">{{title_1}}</p>
                                          <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                                      </div>
                                  </div>
                              </div>
                              <div class="col-lg-9">
                                  <div class="education-content h-100 pt-6 ps-6 pb-6">
                                      <div class="row g-4">
                                          {{qualifications}}
                                          <div class="col-12">
                                              <div class="education-item rounded p-4 h-100 wow fadeInUp" data-wow-delay="0.1s">
                                                  <div class="d-flex align-items-center mb-3">
                                                      <p class="fs-5 mb-0 me-4">{{school_college}}</p>
                                                      <div>
                                                          <span class="fa fa-calendar me-1"></span> {{year}}
                                                      </div>
                                                  </div>
                                                  <h4 class="mb-3">{{course_name}}</h4>
                                                  <p class="mb-0">{{description}}</p>
                                              </div>
                                          </div>
                                          {{/qualifications}}
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <!-- Education End -->
  -
    type: set
    attrs:
      id: m0uq2a7y
      values:
        type: my_skills
        title_1: 'My Skills'
        title_2: 'My Capabilities'
        skills:
          -
            id: m0uq2cgg
            name: Wordpress
            percent: '60'
            icon: fa-wordpress
          -
            id: m0uq2ebv
            name: Figma
            percent: '75'
            icon: fa-figma
          -
            id: m0uq32mm
            name: Sketch
            percent: '68'
            icon: fa-sketch
          -
            id: m0uq3guw
            name: Elementor
            percent: '75'
            icon: fa-elementor
          -
            id: m0uq3zzs
            name: Javascript
            percent: '60'
            icon: fa-js-square
          -
            id: m0uq4ife
            name: 'HTML & CSS'
            percent: '100'
            icon: fa-html5
        edit_template: false
        custom_template: |-
          <!-- Skills Start -->
                  <div class="container-fluid">
                      <div class="container">
                          <div class="row g-0">
                              <div class="col-lg-3">
                                  <div class="skills-header h-100 bg-dark pt-6 pe-6 pb-6">
                                      <div class="text-start d-flex flex-column justify-content-center wow fadeInUp" data-wow-delay="0.1s">
                                          <p class="text-white sub-title">{{title_1}}</p>
                                          <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                                      </div>
                                  </div>
                              </div>
                              <div class="col-lg-9">
                                  <div class="skills-content h-100 pt-6 ps-6 pb-6">
                                      <div class="row g-4">
                                          {{skills}}
                                          <div class="col-6 col-md-4 col-lg-4 col-xl-3">
                                              <div class="skills-item text-center rounded p-4 h-100 wow fadeInUp" data-wow-delay="0.1s">
                                                  <div class="text-primary text-center mb-3"><span class="fab {{icon}} fa-3x"></span></div>
                                                  <div class="counter-counting d-flex justify-content-center">
                                                      <h4 class="display-6" data-toggle="counter-up">{{percent}}</h4>
                                                      <h4 class="display-6">%</h4>
                                                  </div>
                                                  <p class="mb-0">{{name}}</p>
                                              </div>
                                          </div>
                                          {{/skills}}
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <!-- Skills End -->
  -
    type: set
    attrs:
      id: m0usm41b
      values:
        type: services
        title_1: 'My Services'
        title_2: 'What I do for you'
        services:
          -
            id: m0usm62h
            icon: 'fas fa-bezier-curve'
            title: 'Creative Design'
            description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis laboriosam repudiandae'
            items:
              -
                id: m0usmzo7
                item_name: Figma
              -
                id: m0usn0gu
                item_name: Sketch
              -
                id: m0usn161
                item_name: 'Adobe XD'
            type: services
            enabled: true
          -
            id: m0usmaza
            icon: 'fas fa-laptop-code'
            title: 'Statamic CMS Development'
            description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis laboriosam repudiandae'
            items:
              -
                id: m0usnc9m
                item_name: SSG
              -
                id: m0usnew9
                item_name: E-Commerce
              -
                id: m0usnihh
                item_name: Gatsby
            type: services
            enabled: true
          -
            id: m0usnu2b
            icon: 'fab fa-app-store'
            title: 'Mobile Applications'
            description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis laboriosam repudiandae'
            items:
              -
                id: m0usocih
                item_name: Android
              -
                id: m0usod8p
                item_name: Apple
              -
                id: m0usoea3
                item_name: Microsoft
            type: services
            enabled: true
        edit_template: true
        custom_template: |-
          <!-- Service Start --> 
                  <div class="container-fluid" id="ipersonalService">
                      <div class="container">
                          <div class="row g-0">
                              <div class="col-lg-3">
                                  <div class="service-header h-100 bg-dark pt-6 pe-6 pb-6">
                                      <div class="text-start d-flex flex-column justify-content-center wow fadeInUp" data-wow-delay="0.1s">
                                          <p class="text-white sub-title">{{title_1}}</p>
                                          <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                                      </div>
                                  </div>
                              </div>
                              <div class="col-lg-9">
                                  <div class="service-content h-100 pt-6 ps-6 pb-6">
                                      <div class="row g-4">
                                          {{services}}
                                          <div class="col-12">
                                              <div class="service-item p-4 wow fadeInUp" data-wow-delay="0.1s">
                                                  <div class="row g-4 align-items-center">
                                                      <div class="col-xl-2">
                                                          <i class="{{icon}} fa-3x"></i>
                                                      </div>
                                                      <div class="col-xl-3">
                                                          <a href="#" class="h4 mb-0">{{title}}</a>
                                                      </div>
                                                      <div class="col-xl-4">
                                                          <p class="mb-0">{{description}}</p>
                                                      </div>
                                                      <div class="col-xl-3">
                                                         {{items}}
                                                          <p><i class="fa fa-check me-2"></i>{{item_name}}</p>
                                                         {{/items}}
                                                      </div>
                                                  </div>
                                              </div>
                                          </div>
                                          {{/services}}
                                        
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <!-- Service End -->
  -
    type: set
    attrs:
      id: m0ut2m5w
      values:
        type: portfolio
        title_1: Portfolio
        title_2: 'My Recent Works'
        portfolio:
          -
            id: m0ut2ohm
            service: 'Web Development'
            description: 'Software Design for ABC Corporation'
            image: images/designer-(3).jpeg
            type: new_set
            enabled: true
          -
            id: m0ut4kn8
            service: 'Web Development'
            description: 'Software Design for ABC Corporation'
            image: images/designer-(2).jpeg
            type: new_set
            enabled: true
          -
            id: m0ut4uk3
            service: 'Web Development'
            description: 'Software Design for ABC Corporation'
            image: images/about.jpeg
            type: new_set
            enabled: true
        edit_template: false
        custom_template: |-
          <!-- Portfolio Start -->
                  <div class="container-fluid">
                      <div class="container">
                          <div class="row g-0">
                              <div class="col-lg-3">
                                  <div class="portfolio-header h-100 bg-dark pt-6 pe-6 pb-6">
                                      <div class="text-start d-flex flex-column justify-content-center wow fadeInUp" data-wow-delay="0.1s">
                                          <p class="text-white sub-title">{{title_1}}</p>
                                          <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                                      </div>
                                  </div>
                              </div>
                              <div class="col-lg-9">
                                  <div class="portfolio-content h-100 pt-6 ps-6 pb-6">
                                      
                                      {{portfolio}}
                                      <div class="portfolio-item py-5 border-bottom wow fadeInUp" data-wow-delay="0.1s">
                                          <div class="row g-4 align-items-center">
                                              <div class="col-xl-6">
                                                  <h4 class="text-body">{{service}}</h4>
                                                  <h1 class="display-6 mb-0">{{description}}</h1>
                                              </div>
                                              <div class="col-9 col-xl-4">
                                                  <div class="portfolio-img">
                                                      <div class="portfolio-img-inner">
                                                          <img src="{{ glide:image preset="portfolio" }}" class="img-fluid" alt="Image">
                                                      </div>
                                                  </div>
                                              </div>
                                              <div class="col-3 col-xl-2">
                                                  <div class="view-img">
                                                      <a href="{{image}}" class="btn btn-primary btn-lg-square"  data-lightbox="Portfolio-1"><i class="fas fa-plus"></i></a>
                                                  </div>
                                              </div>
                                          </div>
                                      </div>
                                      {{/portfolio}}
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <!-- Portfolio End -->
  -
    type: set
    attrs:
      id: m0uw6teg
      values:
        type: blog_listing
        title_1: Blog
        number_of_items: 4
        more_button_link: /blog
        edit_template: true
        custom_template: |-
          <!-- Blog Start --> 
          <div class="container-fluid" id="ipersonalBlog">
              <div class="container">
                  <div class="row g-0">
                      <div class="col-lg-3">
                          <div class="blog-header h-100 bg-dark pt-6 pe-6 pb-6">
                              <div class="text-start d-flex flex-column justify-content-center wow fadeInUp"
                                  data-wow-delay="0.1s">
                                  <p class="text-white sub-title">{{title_1}}</p>
                                  <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                              </div>
                          </div>
                      </div>
                      <div class="col-lg-9">
                          <div class="blog-content h-100 pt-6 ps-6 pb-6">
                              <div class="row g-4">

                                  {{ collection:blog paginate="{{number_of_items}}" as="posts"  status:is="published" sort="date:desc"}}

                                  {{ if no_results }}
                                  <p>Aww, there are no results.</p>
                                  {{ /if }}

                                  {{ posts }}

                                  <div class="col-xl-6">
                                      <div class="blog-item wow fadeInUp" data-wow-delay="0.1s">
                                          <div class="row g-4">
                                              <div class="col-4">
                                                  <div class="blog-item-img bg-dark h-100">
                                                      <a href="#">
                                                          <img src="{{glide:image preset="portfolio"}}" class="img-fluid w-100 h-100"
                                                              style="object-fit: cover;" alt="{{title}}">
                                                      </a>
                                                  </div>
                                              </div>
                                              <div class="col-8">
                                                  <div class="h-100">
                                                      <p class="text-body mb-3"><i class="fa fa-calendar-alt me-2"></i> {{date | format('d  F Y')}}</p>
                                                      <a href="{{url}}" class="d-inline-block h4 mb-4">{{title}}</a>
                                                      <div class="py-2 px-3 bg-light d-flex justify-content-between">
                                                          <p class="mb-0 text-body">By <a href="#" class="h6">{{author.name}}</a></p>
                                                          <p class="mb-0 text-body">In <a href="#" class="h6">{{category}}</a></p>
                                                      </div>
                                                  </div>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  {{ /posts }}






                                 


                                  {{if more_button_text}}
                                  <div class="col-12 wow fadeInUp" data-wow-delay="0.9s">
                                      <div class="blog-btn d-flex justify-content-center">

                                          <a href="{{more_button_link}}" class="btn d-inline-block p-0">{{more_button_text}}</a>
                                      </div>
                                  </div>
                                  {{else}}
                                  {{ paginate }}
                                 <p>{{ if prev_page }} <a href="{{ prev_page }}" class="justify-content-start">⬅ Previous</a>{{/if}}&nbsp;&nbsp;&nbsp;&nbsp;{{ if next_page}}<a class="justify-content-end" href="{{ next_page }}">Next ➡</a>{{/if}}</p>
                                  {{ /paginate }}
                                  {{/if}}


                                  {{ /collection:blog }}




                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- Blog End -->
        title_2: 'Recent Posts'
        more_button_text: 'View All Blog Posts'
  -
    type: set
    attrs:
      id: m0uzvx3w
      values:
        type: testimonial
        title_1: Testimonial
        title_2: 'What People Says'
        testimonials:
          -
            id: m0uzwbez
            client_name: 'David Hanson'
            location: 'London, Uk'
            testimonial: 'Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old.'
            image: images/about.jpeg
            type: new_set
            enabled: true
          -
            id: m0uzwuoo
            client_name: 'Giedrius Kodiyak'
            location: 'Minneapolis USA'
            testimonial: 'Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old.'
            image: images/designer.jpeg
            type: new_set
            enabled: true
          -
            id: m0uzxdes
            client_name: Markelliew
            location: 'Melbourne, Australia'
            testimonial: 'Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old.'
            image: images/designer.jpeg
            type: new_set
            enabled: true
          -
            id: m0uzyzsd
            client_name: Armando
            location: 'Loca, USA'
            testimonial: 'Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old.'
            image: images/designer-(2).jpeg
            type: new_set
            enabled: true
        edit_template: false
        custom_template: |-
          <!-- Testimonial Start -->
          <div class="container-fluid">
              <div class="container">
                  <div class="row g-0">
                      <div class="col-lg-3">
                          <div class="testimonial-header h-100 bg-dark pt-6 pe-6 pb-6">
                              <div class="text-start d-flex flex-column justify-content-center wow fadeInUp"
                                  data-wow-delay="0.1s">
                                  <p class="text-white sub-title">{{title_1}}</p>
                                  <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                              </div>
                          </div>
                      </div>
                      <div class="col-lg-9">
                          <div class="testimonial-content h-100 pt-6 ps-6 pb-6">
                              <div class="testimonial-carousel owl-carousel bg-light wow fadeInUp" data-wow-delay="0.1s">
                                
                                {{testimonials}}
                                  <div class="testimonial-item"
                                      data-dot="<img class='img-fluid' src='{{ glide:image preset="testimonial" }}' alt='{{client_name}}'>">
                                      <div class="row gy-4 gx-2 mb-4">
                                          <div class="col-sm-6">
                                              <div class="d-flex justify-content-sm-end">
                                                  <div class="testimonial-inner-img border border-primary border-3 me-4"
                                                      style="width: 100px; height: 100px;">
                                                      <img src="{{ glide:image preset="testimonial" }}" class="img-fluid"
                                                          style="object-fit: cover;" alt="">
                                                  </div>
                                              </div>
                                          </div>
                                          <div class="col-sm-6">
                                              <div>
                                                  <h5 class="mb-2">{{client_name}}</h5>
                                                  <p class="mb-0">{{location}}</p>
                                              </div>
                                          </div>
                                      </div>
                                      <div class="text-sm-center">
                                          <p>{{testimonial}}
                                          </p>
                                          <div class="d-flex justify-content-sm-center">
                                              <i class="fas fa-star text-primary"></i>
                                              <i class="fas fa-star text-primary"></i>
                                              <i class="fas fa-star text-primary"></i>
                                              <i class="fas fa-star text-primary"></i>
                                              <i class="fas fa-star text-primary"></i>
                                          </div>
                                      </div>
                                  </div>
                                  {{/testimonials}}
                                
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- Testimonial End -->
  -
    type: set
    attrs:
      id: m0v0kt7g
      values:
        type: contact_us
        title_1: 'Contact Me'
        title_2: 'Lets Collaborate'
        description: 'In publishing and graphic design, Lorem ipsum is a placeholder text commonly used to demonstrate the visual form of a document or a typeface without relying on meaningful content. Lorem ipsum may be used as a placeholder before the final copy is available.'
        contact_details:
          -
            id: m0v0l2pp
            icon: 'fas fa-map-marker-alt'
            title: Address
            data: 'Trivandrum, Kerala, India'
            type: new_set
            enabled: true
          -
            id: m0v0lg13
            icon: 'fas fa-envelope'
            title: Email
            data: manup.rav@gmail.com
            type: new_set
            enabled: true
          -
            id: m0v0lw97
            icon: 'fa fa-phone-alt'
            title: Phone
            data: '+918907289865'
            type: new_set
            enabled: true
        google_map_iframe: |-
          <iframe class="rounded w-100" style="height: 400px;"
                                                  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d387191.33750346623!2d-73.97968099999999!3d40.6974881!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c24fa5d33f083b%3A0xc80b8f06e177fe62!2sNew%20York%2C%20NY%2C%20USA!5e0!3m2!1sen!2sbd!4v1694259649153!5m2!1sen!2sbd"
                                                  loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        edit_template: true
        custom_template: |-
          <!-- Contact Start -->
          <div class="container-fluid" id="ipersonalContact">
              <div class="container">
                  <div class="row g-0">
                      <div class="col-lg-3">
                          <div class="contact-header h-100 bg-dark pt-6 pe-6 pb-6">
                              <div class="text-start d-flex flex-column justify-content-center wow fadeInUp"
                                  data-wow-delay="0.1s">
                                  <p class="text-white sub-title">{{title_1}}</p>
                                  <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                              </div>
                          </div>
                      </div>
                      <div class="col-lg-9">
                          <div class="contact-content h-100 pt-6 ps-6 pb-6">
                              <div class="bg-light p-4">
                                  <div class="row g-5">
                                      <div class="col-xl-5 wow fadeInUp" data-wow-delay="0.1s">
                                          <p class="mb-4">{{description}}</p>
                                          {{contact_details}}
                                          <div class="d-flex mb-4">
                                              <div class="btn-xl-square bg-primary text-white me-3">
                                                  <i class="{{icon}}"></i>
                                              </div>
                                              <div>
                                                  <h4>{{title}}</h4>
                                                  <p class="mb-0">{{data}}</p>
                                              </div>
                                          </div>
                                          {{/contact_details}}
                                      </div>
                                      <div class="col-xl-7 wow fadeInUp" data-wow-delay="0.3s">
                                          <div>
                                              {{form:contact_us}}
                                              <div class="row g-3">


                                                  {{ if success }}
                                                  <div class="text-success">
                                                      {{ form_success_message }}
                                                  </div>
                                              {{ /if }}
                                                 {{ if errors }}
                                                      <div class="text-danger mb-3">
                                                          {{ errors }}
                                                              {{ value }}<br>
                                                          {{ /errors }}
                                                      </div>
                                                  {{ /if }}



                                                  {{ fields }}
                                                  {{if type=="textarea"}}


                                                  <div class="col-12">
                                                      <div class="form-floating">
                                                          <textarea name="{{handle}}" class="form-control border-0"
                                                              placeholder="{{placeholder}}" id="{{handle}}"
                                                              style="height: 120px"></textarea>
                                                          <label for="message">{{placeholder}}</label>
                                                      </div>
                                                  </div>


                                                  {{elseif handle=="subject"}}
                                                  <div class="col-12">
                                                      <div class="form-floating">
                                                          <input type="{{type}}" class="form-control border-0" id="{{handle}}"
                                                              name="{{handle}}" placeholder="{{placeholder}}">
                                                          <label for="subject">Subject</label>
                                                      </div>
                                                  </div>
                                                  {{else}}
                                                  <div class="col-lg-12 col-xl-6">
                                                      <div class="form-floating">
                                                          <input type="{{type}}" class="form-control border-0" id="{{handle}}"
                                                              name="{{handle}}" placeholder="{{placeholder}}">
                                                          <label for="name">{{placeholder}}</label>
                                                      </div>
                                                  </div>
                                                  {{/if}}
                                                  {{ /fields }}
                                                

                                                  <div class="col-12">
                                                      <button type="submit" class="btn btn-primary w-100 py-3">Send
                                                          Message</button>
                                                  </div>
                                              </div>
                                              {{/form:contact_us}}

                                          </div>
                                      </div>
                                      <div class="col-12 wow fadeInUp" data-wow-delay="0.5s">
                                          <div class="rounded">
                                              {{google_map_iframe}}
                                          </div>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- Contact End -->
        form_success_message: 'Thanks for Contacting me, I will respond in 24 Hours'
  -
    type: paragraph
---
